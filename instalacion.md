
# Instalación de Linux en Windows con WSL

El Subsistema de Windows para Linux (WSL) permite a los usuarios ejecutar distribuciones de Linux directamente en Windows. Esto permite el uso de aplicaciones y herramientas de línea de comandos de Linux sin la necesidad de una máquina virtual o un arranque dual.

## Requisitos Previos

Necesitas tener Windows 10 versión 2004 o posterior (compilación 19041 o posterior) o Windows 11. Si tienes una versión anterior, consulta las instrucciones de instalación manual.

## Instalación de WSL

Ahora puedes configurar todo lo necesario para WSL con un solo comando. Abre PowerShell o el símbolo del sistema como administrador (haz clic derecho y selecciona "Ejecutar como administrador") y ejecuta:

```powershell
wsl --install
```

	- Para ver la lista de distribuciones disponibles :
	
```powershell
wsl --list --online
```

	- Para instalar Una Distribucion
	
```powershell
wsl --install -d [Distribucion]
```


***

## Cambio de la distribución predeterminada de Linux instalada

Por defecto, la distribución de Linux instalada es Ubuntu, pero puedes cambiarla fácilmente con la opción `-d`.


- Para cambiar la distribución instalada, usa el siguiente comando:

```
wsl --install -d <Nombre de la Distribución>
```
Reemplaza `<Nombre de la Distribución>` con el nombre de la distribución que desees instalar.

- Para ver las distribuciones de Linux disponibles para descargar desde la tienda en línea, ejecuta:
```
wsl --list --online
```
o simplemente:

- Si deseas instalar distribuciones de Linux adicionales después de la instalación inicial, también puedes usar el comando:
```
wsl --install -d <Nombre de la Distribución>
```


