

Python 3.8.19
adapte los modulos segun lo que pedia el readme para la verion de python
y para funcionar en colab ademas de crear el entorno y activar el kernel para que sea visible en conda
instale tensorboard (!pip install)

```
conda env list
conda activate py38
conda create -n py38 python=3.8.19
pip install -r requirements.txt
pip install ipykernel
pip install tensorboard
python -m ipykernel install --user --name py38 --display-name "py38"

```
```
// conda remove --name ENVIRONMENT --all

conda remove --name py38limu --all
```

C:\Users\stfgp\Documents\Proyectos\LIMU-BERT-Public

