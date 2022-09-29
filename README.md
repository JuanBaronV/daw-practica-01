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


![](https://iescelia.org/web/wp-content/uploads/2012/05/iescelia_1950.jpg)