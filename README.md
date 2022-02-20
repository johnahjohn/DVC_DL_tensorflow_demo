# DVC - DL - TF
#download data --> source

### commands -
'''bash
create a new env
conda create --prefix ./env python=3.7 -y
activate new env
source activate ./env
'''

# init DVC
'''bash
git init
dvc init
'''

# create empty files -
'''bash
mkdir -p src/utils config
touch src/__init__.py src/utils/__init__.py param.yaml dvc.yaml config/config.yaml src/stage_01_load_save.py src/utils/all_utils.py setup.py .gitignore
''' 

# install src
#pip install -e .