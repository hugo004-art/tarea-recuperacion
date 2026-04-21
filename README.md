# Informe de recuperación

### Error simulado
Se eliminó el archivo `errores.sh` y se realizó un commit del borrado, haciendo que el archivo desapareciera de la rama principal de trabajo.

### Comandos utilizados
1. `git reflog`: Para localizar el código hash del momento previo al desastre (`607d10c`).
2. `git checkout 607d10c -- errores.sh`: Para rescatar el archivo y traerlo de vuelta al presente.

### Aprendizaje
He aprendido que Git funciona como una caja negra de un avión; mientras hayamos hecho un commit en algún momento, la información es recuperable gracias al registro del reflog.
