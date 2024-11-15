Prequisites:
    sudo apt-get install curl
    curl -O https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh
    bash Anaconda3–2020.11-Linux-x86_64.sh


$ conda create -n aml -y Python=3.8
 
$ conda activate aml
 
$ conda install nb_conda
 
$ pip install azureml-sdk[notebooks]
 
$ jupyter notebook  --ip 0.0.0.0