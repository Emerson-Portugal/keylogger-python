# Instalacion de un entorno para el Keylogger

## Requisitos
- Python 


> Lo primero que tenenemos que hacer es descargar o clonal el repositorio, para poder ejecutar el Keylogger, tenemos que desactivar el antivirus y finalmente lo abrimos en editor de codigo.

> Ya en el editor tenemos que descargar las librerias para poder usar el Keylogger, podemos escoger la OPCION 1 o OPCION 2.

### Opcion 1
Crear un entorno Virtualizado, para instalar las librerias

#### Paso 1
Creamos el entorno de Virtualizacion
```python
python -m virtualenv venv
```

#### Paso 2
Activamos el entorno de Virtualizacion
```python
.\venv\Scripts\activate
```

#### Paso 3
Instalamos las librerias
```python
pip install -r ".\requirements.tx
```

### Opcion 2
Instalar toda las librerias de forma local

#### Paso 1
Instalamos las librerias de forma local
```
pip install -r ".\requirements.tx
```