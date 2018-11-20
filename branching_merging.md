# Branching and merging

Los siguientes ejercicios los debes realizar en tu máquina real, no es necesario que los subas a un repositorio en github. Indica los pasos seguidos para realizar cada ejercicio en este mismo fichero.

1. Crea un directorio llamado _**branch_time**_
Se abre un terminal y se escribe el siguiente comando: mkdir + nombre de directorio (en este caso branch_time).
2. Cámbiate a dicho directorio.
Se escribe el comando cd + la direccion del directorio.
3. Inicializa un repositorio vacío.
Se pone el comando git init
4. Crea un fichero llamado first.txt después añade y haz commit con un solo comando.
Se escribe el comando nano + nombre del fichero + .txt (first.txt)
5. Crea una nueva rama llamada _**amazing_feature**_.
Se pone el siguiente comando: git branch + nombre de la rama (amazing_feature)
6. Cámbiate a dicha rama.
Se escribe el comando git checkout + nombre de la rama (amazing_featura)
7. Crea un nuevo fichero llamado best.txt con el contenido "this is the best file".
Se escribe el comando nano + nombre del fichero + .txt (best.txt) y dentro del fichero ponemos: "this is the best file"
8. Añade el fichero al área de preparación.

9. Haz commit del fichero con el mensaje "added best.txt".
se escribe el comando git add added best.text, y a continuacion se escribe el comando git commit -m
10. Vuelve a la rama master.
git checkout NOMBRE_RAMA_ORIGINAL
11. Une (merge) la rama feature a la rama master.
git merge [--no-ff] RAMA ORIGINAL
12. Borra la rama feature.
git branch -d feature
13. Crea la rama _**conflict**_ y cámbiate a ella con un solo comando.
Ponemos en el terminal el comando git checkout -b + nombre de la rama (conflict)
14. Crea tu propio conflicto al mezclar dos ramas! Para ello trabaja en el mismo fichero en dos ramas separadas y une (merge) las dos ramas. Arregla los conflictos y finaliza la unión. En el mundo real nunca intentarás crear un conflicto en una unión de ramas, pero es importante que no te sientas intimidado por los conflictos al realizar una unión de ramas y ser capaz de arreglarlos con confianza.
