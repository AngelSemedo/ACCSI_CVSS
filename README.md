# ACCSI_CVSS
Aplicación web para generar incidencias en Jira con base en una vector string de CVSS

## Instrucciones
La aplicación está preparada para su importación directa en un entorno web2py, a continuación se detalla el procedimiento.

### Requisitos
- Python 2.7 o superior
- Librerías **requests** y **json**, recomendable instalar mediante pip
- Versión *Source Code* de web2py ([enlace de descarga](https://mdipierro.pythonanywhere.com/examples/static/web2py_src.zip))
- Navegador web

### Instalación
1. Ejecutar el fichero web2py (python web2py.py -a <contraseña de administrador>)
2. Acceder a la dirección localhost:8000 desde nuestro navegador
3. En la pantalla de bienvenida, acceder a **Mis sitios** (*My sites*)
4. En el menú lateral de la derecha, rellenar los campos de la sección **Suba e instale una aplicación empaquetada** (*Upload and install packed application*), indicando el nombre deseado para la aplicación. Seleccionar el fichero web2py.app.cvss.w2p para su subida.

- Para acceder a la aplicación, ir a la dirección http://localhost:8000/<nombre de la aplicación>/default/index 
  - (p.e., http://localhost:8000/cvss/default/index)
- Para editar la aplicación, acceder a la consola de administrador (**Mis sitios** / *My sites*), localizar nuestra aplicación y seleccionar **Editar** (*Edit*) en el menú **Gestionar** (*Manage*)
