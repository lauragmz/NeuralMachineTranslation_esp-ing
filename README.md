<div class="tip" markdown="1">

# Neural Machine Translation
<div align="justify">

### Reproducibilidad

El entrenamiento de la NMT se realizó usando colab <poner aquí el lugar donde se encuentra el notebook>

### Experimentos

Para realizar experimentos con el modelo entrenado, pudes usar el notebook ` NMT_experimentos `que se encuentra dentro de la carpeta notebooks. Para asegurar el correcto funcionamiento se utiliza un ambiente de `anaconda` y para su instalación se deben seguir los siguientes pasos.

```
conda env create -n NMT -f environment.yml
conda activate NMT
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=NMT
```
Una vez que tienes cargado el ambiente solo debes lanzar `jupyter notebook` y correr los chunks, esto cargara las funciones necesarias y utilizará los pesos guardados en la carpeta ` training_checkpoints`

Para salir del ambiente solo debes utilizar
```
conda deactivate
```

### Colaboradores

+ Laura Gómez Bustamante [lauragmz](https://github.com/lauragmz "github page")
+ Francisco Paz Cendejas [MrFranciscoPaz](https://github.com/MrFranciscoPaz "github page")
+ Marco Julio Monroy Ayala [ronmoy007](https://github.com/ronmoy007 "github page")

</div>
