## Curso de Frontend profesional

# Instalacion
```
   npm install fronted
```
# Imagenes
Las Imagenes se debe exportar al doble de resolucion a como las vamos a usar:
***Ejemplo***
uso: 
     width:45px
     height:45px

la exportamos desde cualquier herramienta grafica que se use 
( Photoshop cmd + alt + shift + s ). Width: 90px Height:90px ya 
con esto le damos soporte a pantallas con el doble de resolucion. 

# Llave publica
La llave publica nos es util para autenticarnos de manera seguro con algun servidor, en este caso la vamos a usar para autenticarnos con github.
```
ssh-keygen -t rsa -b 4096 -C "fabiorojas7@gmail.com" 
```
el .pub generado lo agregamos en settings / SSH and GPG keys
y damos click en new SSH key.

cuando bloqueamos un usuario por intentar un maximo de intentos permitidos:
ssh -o IdentitiesOnly=yes -i id_rsa root@ip

# License
```
Copyright 2017 FABIO ROJAS

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

```

# Autor
[FABIO ROJAS](https://twitter.com/#hackchan77)