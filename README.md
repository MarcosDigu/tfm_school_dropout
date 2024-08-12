# Resumen repositorio: 

## 1. Code: 
### 1.1. Pretratamiento de Datos: 
En en esta carpeta habrá un .ipynb para el desarrollo de la función de tratamiento de datos (que deberá beber datos en crudo y exportar datos listos para entrenar) y un .py de la versión usable.

### 1.2. Encontrar el mejor modelo: 
Una vez que tengamos el tratamiento hecho, en esta carpeta estará un .ipynb que cogerá los datos del 1.1. y entrenará varios modelos con ellos junto con su matriz de confusión. 

### 1.3. Búsqueda paramétrica del mejor modelo: 
Una vez hayamos encontrado la mejor arquitectura para nuestros datos, habrá que encontrar la mejor parametrización para el modelo. Este ipynb deberá exportar un .pkl del modelo en cuestión.

## Data: 
Aquí estarán los datos guardados, junto con las tablas que podamos obtener de forma adicional para complementar a la tabla original.

-----------------------------------------------

# Entornos Virtuales
Recordamos las instrucciones para clonar el entorno virtual: 

1. Abrir terminal anaconda
2. conda create --name entorno_tfm python=3.8 (la versión 3.8 de python no suele dar problemas por compatibilidad)
3. Activamos el entorno: conda activate entorno_tfm
4. Importamos las librerías al entorno: pip install -r requirements.txt

Si alguien instala alguna librería nueva, lo suyo sería que actualizara el archivo requirements.txt con el siguiente comando: pip freeze > requirements.txt. Así, cuando otra persona haga un pull con cambios nuevos, traerá también las nuevas librerías y sólo tendrá que añadirlas a su propio entorno.

