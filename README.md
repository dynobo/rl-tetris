# rl-tetris

Reinforcement Learning - Playing Tetris

***Work in progress***

## Setup env

### Jupyter lab extensions (TODO: script)

jupyter labextension install \
    @ijmbarr/jupyterlab_spellchecker@0.1.5 \
    @jupyterlab/toc@2.0.0-rc.0 \
    @krassowski/jupyterlab_go_to_definition@0.7.1 \
    jupyterlab-flake8@0.4.1 \
    @lckr/jupyterlab_variableinspector@0.3.0 

### Autoformatter (commands need to be in correct order)

jupyter labextension install @ryantam626/jupyterlab_code_formatter@0.7.0
pipenv install jupyterlab_code_formatter==0.7.0
jupyter serverextension enable --py jupyterlab_code_formatter