# react-webpack-template-español :0
Este es un template Basico de React explicado en español para toda la comunidad, gratis, solo dame una estrellita y hazle fork de agradecimiento :)
La estructura esta realizada en 3 componentes: Header (navbar), Body y Footer
 [como](https://github.com/gustavms/react-template-espanol).

## Como lo usas

  * Clona el repositorio: `git clone  react-template`
  * Instala las dependencias: `cd react-template && npm install`
  * Inicia el webpack para que escuche el loader(explicado mas abajo): `npm start`
  * Agrega tu codigo dentro de la carpeta disk y abre el archivo `index.html` para que inicie tu navegador web
  * Disfruta :)


## Explicando como funciona webpack

Webpack sirve para transpilar codigo Jsx a Javascript en este caso es2015 que es lo que soportan casi todos los navegadores.
Archivo de entrada es en index.js ubicado en: 
   * entry: "./app/dist/index.js",
 La salida del archivo compilado es:
  output:   "/app/js/index.min.js"

 El loader sirve para cuando usamos webpack watch y cada vez que grabamos codigo (ctrl+s) este se transpila automaticamente toda la carpeta dist al index.min.js para solo actualizar el navegador f5 y se visualiza los cambios ;) . Exitos y a seguir creciendo.