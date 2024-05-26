### **Comprobacion de nombre!**

<img src="/img/1.png" alt="logo"></img>


### **Paso 0 : Instalar WSL**
- Arrancamos Powershell **como Administradores supremos** e instalamos WSL usando el comando `wsl --install`. ¡Por defecto, se nos plantará **Ubuntu** en la máquina!

  <img src="/img/2.png" alt="logo"></img>

### **1- ¿Qué más hay en el menú?**
- Chequeamos otras distribuciones disponibles con el comando `wsl --list --online`.

```powershell
wsl --list --online
```

  <img src="/img/3.png" alt="logo"></img>


### ** 2- Instalar Ubuntu/Debian**
-  Bucamos por **Debian** en la lista con `wsl --install -d Debian`.

```powershell
wsl --install -d Debian
```
  <img src="/img/66.png" alt="logo"></img>

- En Este Caso lo tenemos instalado ya

- El Ubuntu viene instalado por defecto cuando se instala el WSL pero en caso que queremos instalar otra version de Ubuntu hacemos lo siguiente :

    <img src="/img/4.png" alt="logo"></img>


### ** 3- Reinicia y listo**
- Luego de instalar ambas distribuciones, es hora de **reiniciar** el PC. Al encenderlo de nuevo, nos pedirá usuario y contraseña de nuestro Ubuntu.

```powershell
Restart-Computer 
```


### ** 4- ¡Debian/Ubuntu en escena!**
- Para lanzar Debian o Ubuntu, simplemente tecleamos su nombre del SO 'Debian' o 'ubuntu' en Powershell. Nos solicitará usuario y contraseña y ¡listo para la acción!

    <img src="/img/deb.png" alt="logo"></img>


### ** 5- Comprobando existencia**
- Nos aseguramos de que Ubuntu esté instalado y corriendo con `wsl -l -v`.

```powershell
wsl -l -v
```
   <img src="/img/5.png" alt="logo"></img>

