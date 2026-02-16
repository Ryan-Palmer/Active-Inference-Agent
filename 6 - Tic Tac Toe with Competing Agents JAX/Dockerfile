FROM ghcr.io/nvidia/jax:jax-2026-02-15

WORKDIR /src

RUN apt-get update \
    && apt-get install software-properties-common -y \
    && add-apt-repository ppa:dotnet/backports \
    && apt-get update \
    && apt-get install -y dotnet-sdk-9.0

COPY pip-packages.txt pip-packages.txt
RUN pip install --upgrade pip
RUN pip install --upgrade -r pip-packages.txt
RUN rm ./pip-packages.txt

ENTRYPOINT ["jupyter", "lab","--ip=0.0.0.0","--allow-root","--no-browser", "--LabApp.token='dev'"]