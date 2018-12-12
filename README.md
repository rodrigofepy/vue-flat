
# vue-flat
## Libreria de componentes estilo Flat Design para Vue.
### Una colaboracion del grupo de telegram "Hablemos de Vue.js" para la comunidad y ecosistema de Vue.js. 


<div align="center"><a> <img src="https://github.com/wilmercampagna/vue-flat/blob/master/src/assets/VueFlat.jpg"> </a></div>



## Bienvenidos al proyecto Vue-Flat

Vue flat es una librería de estilos basada en flat design o diseño plano.
Este proyecto es un aporte a la comunidad open source de Vuejs desarrollado por el grupo Hablemos de Vuejs.

### Cómo probar y desarrollar la librería

Guía de uso del entorno de desarrollo

Ver [Guía de uso del entorno de desarrollo](https://www.youtube.com/watch?v=1cQz29xr_1U&t=104s)

### Clonando tu repositorio

Una vez hayas realizado el fork desde el perfil de github de tu referente deberás abrir tu consola de comandos y escribir
```
git clone https://github.com/tuPerfilDeGithub/vue-flat.git
```

### Instalando dependencias
Una vez clonado el repositorio deberás ingresar a la carpeta de vue-flat
```
cd vue-flat
```
Ahora intalas las dependencias con el comando

```
npm i
```
O si usas yarn
```
yarn install
```

Ya instalaste las dependencias del entorno de desarrollo, ahora tendrás que instalar las dependencias del entorno de prueba, para ello ingresa a la carpeta example

```
cd example
```
y nuevamente instalas las dependencias de node.

```
npm i
```
O si usas yarn
```
yarn install
```

Ahora ya estás listo para empezar a desarrollar componentes para el proyecto Vue-Flat, ánimo y mucho exito apreciado amigo.

### Flujo de trabajo con GitHub

Para comenzar primero debes realizar un **Fork** al repositorio del perfil de tu referente (cada referente hará un fork del repositorio oficial). Para esto deberás loguearte en GitHub y verás que en la parte superior derecha hay un botón con la opción Fork, presiónalo y con esto empezaras a realizar un Fork de ese repositorio hacia tu cuenta de GitHub.

Luego, desde la terminal,  deberás clonar tu repositorio forked y nombrar a la carpeta que almacenará tu proyecto con la siguiente instrucción:
```
$ git clone https://github.com/User/vue-flat.git my-proyect
```
Una vez clonado tu nuevo repositorio, ingresa a la carpeta my-proyect:
```
$ cd my-proyect
```
y agrega la URL del repositorio original del proyecto a tu repositorio local:
```
$ git remote add upstream https://github.com/User/RepoOriginal(Forkeado)
```
Con esto le estarás indicando a git que agregue la siguiente ubicación remota y la llamas **upstream**. (Upstream es un término en inglés que se puede interpretar como “principal” o “producción”, solo se usa por estándar).
Puede comprobarlo con el siguiente comando:
```
$ git remote –v
```
Ahora ya estás listo para actualizar tu repositorio desde la ubicación remota:
```
$ git fetch upstream
```
Una vez actualizado, los archivos y commits que agregues deberás unirlos a la **rama develop**, que es la rama que usaras para desarrollar. Para crear esta rama  deberás usar la opción "checkout" de git:
```
$ git checkout -b develop
```
El siguiente paso es unir estos cambios a la rama Master. Para esto primero asegúrate que estas ubicado en la rama Master con el siguiente comando:
```
$ git checkout master
```
Resolve los conflictos de git que se puedan presentar. Una vez que estas en la rama Master fusiona  los cambios:
```
$ git merge develop
```

Luego deberás hacer un pull request al fork del perfil del referente. Para esto ve a GitHub y haz clic en “Pull request”. Puedes hacer clic sobre el icono "Create pull request" para solicitar una fusión, rellena el formulario con los comentarios necesarios y envialo con el botón "Send Pull Request".
Espera  a que tu referente lo revise y apruebe la integracion de tu código a su propio fork.
Por último, tu referente solicitará la integrar todo el codigo de su fork al repositorio oficial, cuyo administrador sera quien apruebe sus cambios, como los de todos los referentes.

### Guía para hacer commits

Usa los siguientes prefijos para nombrar tus commits de acuerdo a los cambios que se estén desarrollando.

[IMP] para mejoras

[FIX] para corregir errores

[REF] para refactorización

[ADD] para agregar nuevos recursos

[REM] para eliminar recursos

[MERGE] para commit de fusión (solo para forward / back-port)