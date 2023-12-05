# Traer una rama nueva y posicionarse en ella:
git fetch --all
git checkout [nombre-rama]
git pull

# Flujo de trabajo con ramas:
git checkout -b [nombre-rama]   # Crear una nueva rama y posicionarse en ella
git add [ruta]                  # Agregar cambios al área de staging
git commit -m "Mensaje del commit"  # Hacer commit de los cambios

# Repetir el añadir y hacer commit según sea necesario:
git add [ruta]
git commit -m "Otro mensaje del commit"

# Push y merge:
git push origin [nombre-rama]   # Empujar la rama local al repositorio remoto

# Fusionar en la rama principal (esto generalmente se hace mediante una pull request en la interfaz de GitHub o GitLab)
