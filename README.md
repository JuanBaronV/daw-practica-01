# daw-practica-01
Práctica 01 del módulo de *Despliegue de aplicaciones web*

# Esto es un ecabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6

**Texto en negrita**
*Texto en cursiva*

`ls -la`

```
sudo systemctl start apache2
```
```bash
#!/bin/bash
echo "Hola mundo"
```
```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```
```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```

[Enlace a la página web del IES Celia Viñas](https://iescelia.org)

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

[1]: https://iescelia.org
[2]: https://github.com


![](https://https://github.com/JuanBaronV/daw-practica-01/blob/main/images/FdwnTQvWQAQ8ChE.png)

* Item 1
* Item 2
* Item 3
* Item 4

* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  * Item 2.1
* Item 3
* Item 4

1. Item 1
2. Item 2
3. Item 3
4. Item 4

1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2  
2. Item 2  
  2.1 Item 2.1  
3. Item 3  
4. Item 4  


| Encabezado 1 | Encabezado 2 | Encabezado 3
| --- | --- | --- | ---
| Fila 1.1 | Fila 1.2 | Fila 1.3
| Fila 2.1 | Fila 2.2 | Fila 2.3
| Fila 3.1 | Fila 3.2 | Fila 3.3

Este texto no es una cita.
> Este texto daría como resultado una cita.

<!- Este texto es un comentario y no será renderizado -->