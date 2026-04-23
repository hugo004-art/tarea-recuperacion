# Informe de Recuperación

## Error simulado
Se eliminó el archivo `errores.sh` y se realizó un commit del borrado, haciendo que el archivo desapareciera de la rama principal de trabajo.

## Comandos utilizados
1. `git reflog`: Para localizar el código hash del momento previo al borrado "607d10c".
2. `git checkout 607d10c -- errores.sh`: Para rescatar el archivo y traerlo de vuelta.

## Aprendizaje
He entendido como funciona Git, mientras se haya hecho un commit en algún momento, la información todavía se puede recuperar gracias al registro del reflog.
