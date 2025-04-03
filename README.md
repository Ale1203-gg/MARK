# DOCUMENTACION EN MARKDOWN
##  Cómo debe ser la documentación en Markdown
 1. Organización de la Documentación
Una buena documentación en Markdown debe incluir:
 * Título y subtítulos bien definidos con #, ##, ###.
 * Código bien formateado para comandos, scripts o configuraciones.
 * Listas ordenadas y no ordenadas para estructurar la información.
 * Negritas y cursivas para resaltar información importante.
 * Tablas y enlaces cuando sea necesario.
* Imágenes para mayor claridad.

  
2. Formato de Texto
**Texto en negrita**  
*Texto en cursiva*  
~~Texto tachado~~  
> Cita o comentario resaltado  
Ejemplo visual:

Markdown es un lenguaje de marcado ligero para documentación.


3. Código y Comandos
Para resaltar comandos en una línea:
`sudo apt update`
Ejemplo:
sudo apt update

Para fragmentos de código o comandos en varias líneas:

```bash
# Actualizar paquetes en Linux
sudo apt update && sudo apt upgrade -y
bash
Copiar
Editar
**Ejemplo visual:**  
```bash
```

4. Listas y Tablas
*  Listas no ordenadas
markdown
Copiar
Editar
- Elemento 1  
- Elemento 2  
- Elemento 3  
Ejemplo visual:

Elemento 1

Elemento 2

Elemento 3

* Listas ordenadas
markdown
Copiar
Editar
1. Primer paso  
2. Segundo paso  
3. Tercer paso  
Ejemplo visual:

Primer paso

Segundo paso

Tercer paso

* Tablas
markdown
Copiar
Editar
| Comando         | Descripción                    |
|----------------|--------------------------------|
| `ls -l`        | Lista archivos en detalle     |
| `cd directorio` | Cambia de directorio          |
| `rm archivo`   | Borra un archivo              |
Ejemplo visual:

Comando	Descripción
ls -l	Lista archivos en detalle
cd directorio	Cambia de directorio
rm archivo	Borra un archivo

 5. Insertar Imágenes y Enlaces
Para agregar enlaces:

[Texto del enlace](https://ejemplo.com)
Ejemplo:
Visita GitHub

Para agregar imágenes:

![Descripción de la imagen](https://ruta-a-la-imagen.com/imagen.png)
