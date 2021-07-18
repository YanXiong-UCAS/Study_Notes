# Anaconda安装与操作

## #Windows安装流程







## #Ubuntu安装流程







## #基本操作

- **获取版本号：**

  `conda --version` 或者 `conda -V`

- **获取帮助：**

  `conda --help` 或者 `conda -h`

  查看update命令及remove命令的帮助：`conda update --help` `conda remove -h`

- **创建环境：**

  `conda create --name your_env_name` python=3.6

- **列举当前所有环境：**

  `conda info -envs` 或者 `conda env list`

- **激活并进入指定环境：**

  `conda activate your_env_name`

- **退出当前环境：**

  `conda deactivate`

- **删除指定环境：**

  `conda remove --name your_env_name --all`

- **复制某个环境并创建新的环境：**

  `conda create --name new_env_name --clone old_env_name`

- **列举当前活跃环境下的所有包：**

  `conda list`

- **列举一个非当前活跃环境下的所有包：**

  `conda list -n your_env_name`

- **为指定环境安装某个包：**

  `conda install -n env_name package_name`

- 杀死进程

  `kill -9 1162`  (1162为PID编号)

  
