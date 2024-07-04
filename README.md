## Pandas for Data Analysis

Presented: July 2, 2024 at PyRVA, Richmond

## Setup

You'll first need to create a virtual environment

    $ python -m venv .venv --prompt=my-env
    $ source .venv/bin/activate
    (my-env) $ 

then install the dependencies 

    (my-env) $ python -m pip install -r requirements.txt

then you are ready to run the jupyter notebook (or jupyter lab)

    (my-env) $ jupyter lab

this should open in your default browser but it also prints a link which you
can copy and paste into a browser window.  Then open the
`pandas-data-analysis.ipynb` file in the notebook and away you go.  If you have
never navigated a jupyter notebook before here is a link to a [quick cheat
sheet](https://www.edureka.co/blog/wp-content/uploads/2018/10/Jupyter_Notebook_CheatSheet_Edureka.pdf)

When you are finished with the environment, you can deactivate it

    (my-env) $ deactivate
    $

or simply close the terminal.   NOTE: It is also possible to edit and run the
notebook in [PyCharm Professional](https://www.jetbrains.com/pycharm/), if you
own a license to it. 

## Data

The NVIDIA data set was downloaded from Kaggle, but is quite small and easily
stored in the repo.  However, the data set for the FIFA players is quite large
(14 M) so it wasn't included in the repo, you can download it from this link: 

- [fifa_players_22.csv](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset?resource=download): FIFA player rankings for 2022 for all male players
