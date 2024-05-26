### **1- ¡A la carga!**
- Arrancamos Powershell **como jefes supremos** e instalamos WSL usando el comando `wsl --install`. ¡Por defecto, se nos plantará **Ubuntu** en la máquina!

### **2- ¿Qué más hay en el menú?**
- Chequeamos otras distribuciones disponibles con el comando `wsl --list --online`.


### ** 3- Expandiendo horizontes**
- También ponemos a **Debian** en la lista con `wsl --install -d Debian`.


### ** 4- Reinicia y listo**
- Luego de instalar ambas distribuciones, es hora de **reiniciar** el PC. Al encenderlo de nuevo, nos pedirá usuario y contraseña de nuestro Ubuntu.

- Una vez hecho esto, ¡Ubuntu estará listo para la acción!


### ** 5- Comprobando existencia**
- Nos aseguramos de que Ubuntu esté instalado y corriendo con `wsl -l -v`.
  
  
### ** 6- ¡Debian en escena!**
- Para lanzar Debian, simplemente tecleamos su nombre en Powershell, Debian. Nos solicitará usuario y contraseña y ¡listo para la acción!


### ** 7- Doble comprobación**
- Finalmente, aseguramos que ambas versiones funcionen y estén operativas con `wsl -l-v`.

