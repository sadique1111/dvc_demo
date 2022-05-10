create env
```bash
conda create -n wineq python=3.7 -y

activate env
conda activate wineq

create requirments.txt file in vs code
touch requirments.txt

write all the package name in requirments.txt file that you need to install and save it.
dvc
dvc[gdrive]
sklearn

install requirments.txt
pip install -r requirments.txt

create README file
touch README.md

history (it will show all the command that you executed in the current shell)

initialize the git
git init

initialize dvc
dvc init

add data to dvc
dvc add data_given/wine_quality.csv

put data in staging area
git add .

commit the whole project
git commit -m "updating read file"