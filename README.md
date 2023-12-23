# AI3603-project-gomoku
an AI agent capable of playing the game of Gomoku by implementing a search algorithm

### Requirements
- python 3
- tensorflow 1.X is available now(policy_value_net.py)
- pytorch framework(policy_value_net_pytorch.py) is under construction

### Train
Open a terminal and run `python train.py`

### Start a game
Open a terminal and run `python start.py`

### Start a evaluation session
Open a terminal and run `python game.py`


## Appendix
command for a suitable environment
### Create a new environment
run `conda create tf --all`

### Activate this environment
run `conda activate tf`
or you can try
`conda.bat activate tf`

after using, run `conda deactivate tf`
or you can try `conda.bat deactivate tf`

### removal
if you no longer need this environment,
run `conda remove -n tf --all`

### about NumPy
run `pip install numpy==1.22 -i https://pypi.tuna.tsinghua.edu.cn/simple/`
since tensorflow-intel 2.13.0 requires numpy<=1.24.3,>=1.22, while scipy 1.6.2 requires numpy<1.23.0,>=1.16.5

