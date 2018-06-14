# Platzom

PLatzom es idioma inventado para el curso de [Fundamentos de Javascript,(https://platzi.com/clases/fundamentos-javascript/concepto/creando-un-paquete-para-npm/creando-muestro-paquete/material/) ]  

## Descripción del Idioma
- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas


## Instalación
```
nmp install platzom
```

#Uso
```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```
## Créditos
[Paulina Collaguazo ]  (https://twitter.com/?lang=es)

##Licencia
[MIT](https://opensource.org/licenses/MIT)