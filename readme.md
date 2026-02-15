# Active Inference Agents

A series of notebooks experimenting with [pymdp](https://github.com/infer-actively/pymdp) to create [active inference](https://www.youtube.com/watch?v=bk_xCikDUDQ) agents.

These show emergent problem solving behaviour by trying to balance satisfying their preferences with gaining information about their environment (minimising their [expected free energy](https://direct.mit.edu/neco/article/33/2/447/95645/Whence-the-Expected-Free-Energy)).

Note that the numpy tic tac toe is very slow on a 4 * 4 board (5 mins per turn) but there is a JAX version in the devcontainer/src folder which is much faster, around 3 secs per turn.

<img width="1663" height="766" alt="image" src="https://github.com/user-attachments/assets/31599635-6424-40a4-aeee-518cb0259c6d" />

<img width="1663" height="934" alt="image" src="https://github.com/user-attachments/assets/b9042ffb-79aa-4422-9f36-07af924a2b35" />
