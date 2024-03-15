# Primeras Contribuciones

Dar los primeros pasos puede resultar intimidante. La inexperiencia al colaborar con otros puede llevar a cometer errores, lo cual puede ser desalentador. La misión de este repositorio es facilitar el proceso para que los nuevos contribuidores en el mundo del código abierto aprendan y se involucren.

Aunque leer artículos y ver tutoriales es útil, ¿qué mejor manera de aprender que sumergirse en la práctica? Este proyecto se centra en ser una guía amigable y simplificada para que los principiantes den sus primeras contribuciones. Si estás listo para dar el primer paso, sigue los pasos que se detallan a continuación.

## Bifurca (*Fork*) este repositorio 
<img align="right" width="250" src="./img/Imagen001.jpg" alt="fork de este repositorio" />
Realiza un fork de este repositorio haciendo clic en el botón 'Fork' ubicado en la esquina superior derecha de esta página. Esto generará una copia de este repositorio en tu cuenta de GitHub.


Recuerda que debes seleccionar tu nombre de usuario de github en owner <img align="right" width="250" src="./img/Imagen003.jpg" alt="selecciona el owner" />
<br>
<br>
<br>

## Abre un Codespaces en el repositorio bifurcado

<img align="right" width="250" src="./img/Imagen002.jpg" alt="abre codespaces" />

Ahora abre un codespace de este repositorio haciendo click en los botones de Code y Create codespace on main. 
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

## Crea una rama (*Branch*)

Desde la terminal de tu codespaces, crea una rama (*branch*) usando el comando  `git checkout`:
```
git checkout -b <añade tu nombre>
```

Por ejemplo:
```
git checkout -b pepito-perez
```
## Navega usando la terminal
Usando únicamente la terminal de codespaces, busca un archivo llamado Instrucciones.txt , ábrelo y sigue las instrucciones del mismo.
Una vez hayas terminado continúa con este README.

## Haz los cambios necesarios en Colaboradores.md y confirma (*Commit*) esos cambios

Abre el archivo `Colaboradores.md` añade tu nombre utilizando este formato `[Pepito Perez](https://github.com/Pepito_Perez/)`  <img align="right" width="320" src="./img/Imagen004.jpg" alt="git status" />



Ahora escribe en la terminal `git status`, verás que hay cambios.
<br>
<br>
<br>
<br>
<br>
Agrega esos cambios a la rama (*branch*) que creaste anteriormente usando el comando `git add`:

```
git add Colaboradores.md
```

Ahora haz un *commit* sobre estos cambios ejecutando el comando `git commit`:
```
git commit -m "Añadido <tu-nombre> a la lista de colaboradores"
```
cambiando `<tu-nombre>` con tu nombre.

## Sube (*Push*) tus cambios a GitHub

Haz *push* de tus cambios usando el comando `git push`:
```
git push origin <añade-el-nombre-de-la-rama>
```
Reemplaza `<añade-el-nombre-de-la-rama>` con el nombre de la rama que creaste anteriormente.

## Envía (*Submit*) tus cambios para ser revisados

Si vas a tu repositorio en GitHub, verás un botón `Compare & pull request`. Haz click sobre este botón. <img align="right" width="400" src="./img/Imagen005.jpg" alt="crea pull request" />

<br>
<br>
<br>
<br>
<br>
<br>
<br>


Ahora envía la *pull request*.

<img align="right" width="500" src="./img/Imagen006.jpg" alt="envia pull request" />


<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


## Has terminado

Ahora me tocará a mi revisar tus cambios y fusionarlos (haciendo *merge*) con la rama main de este proyecto. Recibirás una notificación por correo electrónico cuando los cambios hayan sido fusionados.
