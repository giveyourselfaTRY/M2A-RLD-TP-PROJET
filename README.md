# M2A-RLD-TP-PROJET
TP PROJETS POUR LE COURS DE RLD

##TP PROJET2
![image](https://github.com/user-attachments/assets/0bde7bf0-4f00-44c4-940d-1c0a82187797)
在from bbrl_utils.algorithms import EpochBasedAlgo这里遇到安装问题，
经过查看https://gymnasium.farama.org/main/api/wrappers/misc_wrappers/，在报错的时候点击进入/usr/local/lib/python3.10/dist-packages/bbrl/agents/gymnasium.py，
修改最后两行为：
from gymnasium.wrappers import Autoreset
from gymnasium.wrappers import RecordVideo

