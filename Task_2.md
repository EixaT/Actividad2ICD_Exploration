# Crear un entorno con Python
conda create -n <nombre_entorno> python=3.15.2

    *Proyecto creado en la ruta indicada, e instala la libreria panda.*
        conda create -p ./env python=3.12 pandas

# Exportar entorno
conda env export > <name_fichero>.yml

# TASK
## Crear la libreria con versión de py y los paquetes.
`conda create -n datascience_env -c conda-forge python=3.12 numpy pandas matplotlib seaborn scikit-learn jupyterlab -y`

- -y: Acepta las preguntas de confirmación.

## Exportar entorno
`conda env export --no-builds > environment.yml && conda env export --from-history > environment-from-history.yml`

## Exportar entorno con las versiones instaladas
`conda list --explicit > requirement.txt`
`conda export -f conda-lock.yml`

## Usar el requirement.txt

`conda create -n <nombre_entorno> --file requirement.txt`