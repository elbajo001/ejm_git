# Ejemplo de git básico 

// Iniciar un nuevo repositorio (se inicializa una vez por respositorio)
-> git init
// Ver que archivos no han sido registrados
-> git status
// Solo muestra los archivos modificados
-> git status -s
// Agregar todos los archivos para que esté pendiente de los cambios
-> git add .
// Crear commit (fotografía del proyecto en ese momento)
-> git commit -m "primer commit"
// Muestra los commits que se han hecho hasta el momento 
-> git log --oneline
// Viajamos al commit en específico f52f3da y podemos restaurar los archivos
-> git reset --hard f52f3da
// Asignamos el repositorio remoto
-> git remote add origin https://github.com/elbajo001/ejm_git.git
// Subimos los archivos al repositorio remoto
-> git push -u origin master
