## Clase 11 Actividad en Python

### Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 
~~~cmd
mkdir python-final
~~~
3. Entramos en ella: 
~~~cmd
cd python-final
~~~
4. Iniciamos el repositorio:
~~~
git init
~~~
5. Creamos un archivo:
~~~
touch finales.py
~~~
6. Abrimos VSC:
~~~
code .
~~~
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
~~~powershell
python -V

python3 -V
~~~
8. Creamos el entorno virtual en Python:
~~~powershell
python3 -m venv venv #Creamos el entorno virtual
~~~
9. Activamos el entorno virtual:
~~~powershell
source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows
~~~
10. Hacemos actualización del pip de Python
~~~powershell
python3 -m pip install --upgrade pip #Actualizamos el pip
~~~
---
### ¿Qué es el pip y porque lo actualizamos?

`pip` es el sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python. La mayoría de los proyectos de Python se distribuyen como paquetes, y `pip` facilita su instalación desde el Python Package Index (PyPI) y otros índices de paquetes.

### Funciones de `pip`

1. **Instalación de paquetes**: Permite instalar paquetes desde PyPI y otras fuentes.
   ```bash
   pip install nombre_del_paquete
   ```

2. **Actualización de paquetes**: Permite actualizar paquetes instalados a la versión más reciente.
   ```bash
   pip install --upgrade nombre_del_paquete
   ```

3. **Desinstalación de paquetes**: Permite desinstalar paquetes instalados.
   ```bash
   pip uninstall nombre_del_paquete
   ```

4. **Listado de paquetes instalados**: Muestra una lista de todos los paquetes instalados en tu entorno.
   ```bash
   pip list
   ```

### ¿Por qué Actualizamos `pip`?

Actualizar `pip` es importante por varias razones:

1. **Nuevas Funcionalidades**: Las nuevas versiones de `pip` pueden incluir nuevas características y mejoras que facilitan la instalación y gestión de paquetes.

2. **Corrección de Errores**: Las actualizaciones suelen incluir correcciones de errores que pueden afectar el rendimiento o la seguridad de `pip`.

3. **Mejoras de Seguridad**: Las nuevas versiones pueden solucionar vulnerabilidades de seguridad que podrían ser explotadas en versiones anteriores.

4. **Compatibilidad**: Mantener `pip` actualizado asegura que sea compatible con las últimas versiones de Python y otros paquetes.
---
