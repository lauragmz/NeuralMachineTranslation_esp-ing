<div class="tip" markdown="1">

# Neural Machine Translation
<div align="justify">

### Reproducibilidad

Para asegurar el correcto funcionamiento se utilizó un ambiente de `anaconda` y para su instalación se deben seguir los siguientes pasos.

```
conda env create -n NMT -f environment.yml
conda activate NMT
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=NMT
```
Para salir del ambiente solo debes utilizar
```
conda deactivate
```

El entrenamiento de la NMT se realizó usando colab y se sugiere el uso del mismo en caso de querer hacer cambios. Si se desea entrenar de forma local, el ambiente esta preparado para asegurar la reproducibilidad de los resultados y solo será necesario activar el ambiente y utilizar el notebook `MNT_entrenamiento` que se encuentra dentro de la carpeta `notebooks`.

### Experimentos

Para realizar experimentos con el modelo entrenado, pudes usar el notebook ` NMT_experimentos `que se encuentra dentro de la carpeta `notebooks`.

Una vez que tienes cargado el ambiente solo debes lanzar `jupyter notebook` y correr los chunks, esto cargara las funciones necesarias y utilizará los pesos que deberas descargar siguiendo las instrucciones de la carpeta ` training_checkpoints`


### Colaboradores

+ Laura Gómez Bustamante [lauragmz](https://github.com/lauragmz "github page")
+ Francisco Paz Cendejas [MrFranciscoPaz](https://github.com/MrFranciscoPaz "github page")
+ Marco Julio Monroy Ayala [ronmoy007](https://github.com/ronmoy007 "github page")

</div>
