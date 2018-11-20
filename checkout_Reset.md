# Ejercicios Checkout y Reset

Los siguientes ejercicios los debes realizar en tu máquina real, no es necesario que los subas a un repositorio en github. Indica los pasos seguidos para realizar cada ejercicio en este mismo fichero.

1. Crea un directorio llamado _**destruction**_
Se abre un terminal y se escribe el siguiente comando: mkdir + nombre de directorio (destruction).
2. Cámbiate a dicho directorio
Se escribe el comando cd + la direccion del directorio.
3. Inicializa un repositorio git vacío.
Se pone el comando git init
4. Crea un fichero llamado **stage_me.txt**
Se escribe el comando nano + nombre del fichero + .txt (stage_me.txt)
5. Añade el fichero stage_me.txt al área de preparación (staging area).
git add stage_me.txt
6. Mueve el fichero stage.txt del área de preparación al directorio de trabajo.
git add pull stage_me.txt
7. Añade el fichero stage_me.txt al área de preparación.
git add pull stage_me.txt
8. Elimina el fichero stage_me.txt del área de preparación y del directorio de trabajo.
rm stage_me.txt
9. Crea un fichero nuevo llamado commit_me.txt.
Se escribe el comando nano + nombre del fichero + .txt (commit_me.txt)
10. Añade el fichero commit_me.txt al área de preparación.
git add commit_me.txt
11. Haz un commit con el mensaje "adding commit_me.txt".
git checkout adding commit_me.txt
12. Crea otro fichero llamado second.txt.
Se escribe el comando nano + nombre del fichero + .txt (second.txt)
13. Añade el fichero second.txt al área de preparación.
git add second.txt
14. Haz commit con el mensaje "adding second.txt".
git checkout adding second.txt
15. Muestra los commits previos uno por línea mostrando el identificador únicao (SHA) y el comentario asociado.
Para realizar los siguientes ejercicios debes investigar sobre los parámetros --soft --mixed y --hard del comando git reset.
16. Utilizando git reset, deshaz el commit previo y devuelve los cambios al directorio de trabajo.
git reset commit push
17. Añade el fichero second.txt otra vez al área de preparación.
git add pull second.txt
18. Haz un commit con el mensaje "Trying to commit again".
git add second.txt
git commit -m trying to commit again
19. Utilizando git reset deshaz el commit previo y devuelve los cambios al área de preparación.
git reset commit second.txt
20. Haz commit con el mensaje "Trying to commit again and again".
git add second.txt
git commit -m "trying to commit again and again"
21. Utilizando git reset deshaz el commit previo para que ningún cambio aparezca en el directorio de trabajo.
git reset commit second.txt
22. ¡Date una palmadita en la espalda! ¡Acabas de realizar un flujo de trabajo bastante complejo de git!
    
