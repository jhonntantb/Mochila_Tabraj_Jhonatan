# comandos mas utilizados hasta el momento

## Para manejar carpetas y archivos

- Crear una carpeta

```
$ mkdir nombre_de_la capeta
```

- Crear un archivo

```
$ touch nombre_del_archivo.extención
```

- Listar carpetas dentro del directorio

```
$ ls
```

- Entrar a una carpeta

```
$ cd nombre_de _la _carpeta
```

- salir de la carpeta

```
$ cd ..
```

- Eliminar un archivo

```
$ rm nombre_del _archivo
```

- Eliminar una carpeta o directorio y todo lo que contiene

```
$ rm nombre_de_la_carpeta
```

## Para utilizar git

- Inizializar un repositorio

```
$ git init
```

- Para agregar un archivo al staging area

```
$ git add nombre_del_archivo
```

- Para varios archivos al staging area

```
$ git add .
```

- Para saber el estado de nuestros archivos

```
$ git status
```

- Para hacer un commit

```
$ git commit -m "Mensaje del commit"
```

- Para setear la url de nuestro repositorio remoto

```
$ git remote add origin "url_ del repositorio_remoto"
```

- Para setear nuestros credenciales de manera global

```
$ git config --global user.name "nombre de usuario"
$ git config --global user.mail "email@email.com"
```

- Para ver el historial de commits

```
$ git log
```

- Para pushear nuestro commit al repositorio remoto

```
$ git push
```

- Para actualizar nuestro repositorio local con los cambios que hay en el remoto

```
$ git pull
```

- Para ver las ramas existentes

```
$ git branch
```

- Para crear una nueva rama

```
$ git branch nombre_de_la_rama
```

- Para moverme a una rama

```
$ git checkout nombre_de_la_rama
```
