Welcome to ESE 144! In this github repo, you can find jupyter notebooks and python environments that we will be using in class.

### Getting Started
- install [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main) or [Anaconda](https://www.anaconda.com/)
- install [git](https://git-scm.com/install/)

Clone this repository:
```bash
git clone https://github.com/oalcabes/ESE144-2026.git  
cd ESE144-2026
```

Create the environment from the .yml file:
```bash
conda env create -f environment.yml
```

Activate the environment and make sure your jupyter lab installation can see it:
```bash
conda activate ese144
ipython kernel install --user --name=ese144_kernel
conda deactivate
```
Now, you should be able to type:
```bash
jupyter lab .
```
and navigate to your activities. Once you've opened the activity, you can select the "ese144_kernel" from the top right kernel dropdown menu to use your environment.
