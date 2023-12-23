# AI3603-project-gomoku
an AI agent capable of playing the game of Gomoku by implementing a search algorithm

### Requirements
- python 3
- tensorflow 1.X is available now ([policy_value_net.py](policy_value_net.py))
- pytorch framework ([policy_value_net_pytorch.py](policy_value_net_pytorch.py)) is under construction

### Train
Open a terminal and run<br>
`python train.py`

### Start a game
Open a terminal and run<br>
`python start.py`

### Start a evaluation session
Open a terminal and run<br>
`python game.py`


## Appendix
command for a suitable environment
### Create a new environment
run<br>
`conda create -n tf python=3.6`

### Install tensorflow 1.9.0
We recommend you to visit [https://pypi.tuna.tsinghua.edu.cn/simple/tensorflow/](https://pypi.tuna.tsinghua.edu.cn/simple/tensorflow/) and download one of the following 3 according your device.
```
tensorflow-1.9.0-cp36-cp36m-macosx_10_11_x86_64.whl
tensorflow-1.9.0-cp36-cp36m-manylinux1_x86_64.whl
tensorflow-1.9.0-cp36-cp36m-win_amd64.whl
```
finish downloading, run<br>
`pip install`＋ `file path in your device`
e.g.run<br> 
`pip install D:\Download\myTensorflowWHL\tensorflow-1.9.0-cp36-cp36m-win_amd64.whl`

### Activate this environment
run<br>
`conda activate tf`<br>
or you can try<br>
`conda.bat activate tf`

after using, run<br>
`conda deactivate tf`<br>
or you can try<br>
`conda.bat deactivate tf`

### removal
if you no longer need this environment, run<br>
`conda remove -n tf --all`

### about NumPy
run<br>
`pip install numpy==1.22 -i https://pypi.tuna.tsinghua.edu.cn/simple/`<br>
since tensorflow-intel 2.13.0 requires numpy<=1.24.3,>=1.22, while scipy 1.6.2 requires numpy<1.23.0,>=1.16.5

