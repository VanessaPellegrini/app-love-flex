# Applove

Para trabajar en este proyecto, primero deberás clonarlo:

```sh
git clone https://gitlab.com/laboratoria/app-love-flex.git
```

Luego, para poder trabajar en él y enlazarlo con nuestro repositorio, deberemos ingresar a la carpeta descargada y borrar el .git que nos trae por defecto (tener cuidado con el segundo comando, asegurarse de que esté bien escrito):

```sh
cd app-love-flex
rm -rf .git
```

Por último, una vez creado tu repositorio en Github, simplemente inicializar Git y agregar tu remoto:

```sh
git init
git remote add origin https://github.com/<usuario>/<nombre-repositorio>.git
```

Con estos pasos ya puedes seguir tu workflow de siempre haciendo commits y pusheando a tu repositorio remoto :)