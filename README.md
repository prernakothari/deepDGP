# Reinforcement Learning
## Deep Deterministic Policy Gradients

We present our implementation of an Reinforcement Learning Algorithm called DeepDGP, presented by [Lillicrap et
al.](https://arxiv.org/abs/1509.02971).

### Trained [MuJoCo environments](https://gym.openai.com/envs/#mujoco)

<a href="https://www.youtube.com/embed/C5tIEuEycJY
" target="_blank"><img src="http://img.youtube.com/vi/C5tIEuEycJY/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

### Usage Instruction
We recommend to use python 3.
Install necessary dependencies like openAI-gym by
``` python
pip3 install gym
pip3 install tensorflow
pip3 install tqdm
pip3 install matplotlib
```
To train and run [MuJoCo environments](https://gym.openai.com/envs/#mujoco),
get a one month-trial license from [MuJoCo](http://www.mujoco.org/).
If you are student with .edu address, you can get 1-year MuJoCo license for
free.


``` python
cd src
python3 train.py --env_id='<any openAI-gym continuous environments>' --model_dir=../trained_models/
```

To run our pretrained models
```
cd src
python3 run.py --env_id=Pendulum-v0 --model_dir=../trained_models/Pendulum-v0/
```
