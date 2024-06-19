# Agregar tres líneas al final del archivo README.md
echo -e "\nLínea 1: Esta es una nueva línea.\nLínea 2: Esta es otra nueva línea.\nLínea 3: Esta es la tercera nueva línea." >> README.md

# Verificar los cambios
gato README.md

# Añadir los cambios al área de preparación
git agregar README.md

# Hacer commit de los cambios
git commit -m "Añadidas tres líneas al final de README.md"

# Hacer push de los cambios al repositorio remoto (a la rama main en este caso)
git push origen principal
 ...

<!---
zoujair/zoujair is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
