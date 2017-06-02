# Reto S-Curve
## Descripcion
Este es un conjunto artificial creado utilizando la funcion `make_s_curve` de [sklearn.datasets](http://scikit-learn.org/stable/modules/classes.html#samples-generator) y desechando la segunda dimension.

![graph](images/graph.png)

Consiste en 400 datos.

### Ranking
Ver [ranking](https://github.com/cgarciae/supervised-basico-scurve/blob/master/ranking.md).

### Formato Datos
Los datos se encuentran en los siguientes archivos CSV:
* `traning-set.csv`
* `test-set.csv`

### Variables
* Features: Las primeras 2 columnas del csv son las cooredenadas `x` y `ỳ`.
* Lables: La ultima cooredenada es altura.


### Objetivo
Crear un algortimo que tome como input un vector 2D y retone posible altura de ese punto en la curva. Solo se puede utilizar los datos del `traning-set.csv` para entrenar.

El performance se debe medir con respecto a los datos del `test-set.csv` utilizando la metrica [R2](https://en.wikipedia.org/wiki/Coefficient_of_determination).

### Notas Teoricas
* [SVM](https://en.wikipedia.org/wiki/Support_vector_machine)
* [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree_learning)
* [Neural Network](https://en.wikipedia.org/wiki/Artificial_neural_network)

### Solucion
Ver procedimiento de [solucion](https://github.com/colomb-ia/formato-retos#solucion).

##### Requerimientos
*Indica los requerimientos para utilizar el codigo de tu solucion.*

##### Procedimiento
*Indica el procedimiento que se debe seguir para reproducir tu solucion.*

##### Metodo
*Indica el metodo que utilizaste para solucionar el reto.*

##### Resultados
*Indica el metodo que utilizaste para solucionar el reto.*

## Getting Started
Para resolver este reto primero has un [fork](https://help.github.com/articles/fork-a-repo/) de este repositorio y [clona](https://help.github.com/articles/cloning-a-repository/) el fork en tu maquina.

```bash
git clone https://github.com/{username}/supervised-basico-scurve
cd supervised-basico-scurve
```

*Nota: reemplaza `{username}` con tu nombre de usuario de Github.*

### Requerimientos
Para descargar y visualizar los datos necesitas Python 2 o 3. Las dependencias las puedes encontrar en el archivo `requirements.txt`. Puedes instalarlas fácilmente utilizando el commando

```bash
pip install -r requirements.txt
```
Dependiendo de tu entorno puede que necesites instalar paquetes del sistema adicionales, si tienes problemas revisa la documentación de estas librerías.

# Starter Code Python
Para iniciar con este reto puedes correr el codigo de Python en Jupyter del archivo `python-sample.ipynb`. Este código que ayudará a cargar y visualizar algunas imágenes. Las dependencias son las mismas que se instalaron durante la descarga de los datos, ver [Requerimientos](#requerimientos).

Para iniciar el código solo hay que prender Jupyter en esta carpeta

```bash
jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000000 .
```
y abrir el archivo `python-sample.ipynb`.
