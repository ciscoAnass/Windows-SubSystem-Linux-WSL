### **1- ¡A la carga!**
- Arrancamos Powershell **como jefes supremos** e instalamos WSL usando el comando `wsl --install`. ¡Por defecto, se nos plantará **Ubuntu** en la máquina!

![Instalación de WSL](images/instalandoubuntu.png)
  
![WSL instalado](images/ubuntuinstalado.png)

### **2- ¿Qué más hay en el menú?**
- Chequeamos otras distribuciones disponibles con el comando `wsl --list --online`.

![Distribuciones](images/distribuciones.png)

### ** 3- Expandiendo horizontes**
- También ponemos a **Debian** en la lista con `wsl --install -d Debian`.

![Instalación de Debian](images/instalaciondebian.png)

### ** 4- Reinicia y listo**
- Luego de instalar ambas distribuciones, es hora de **reiniciar** el PC. Al encenderlo de nuevo, nos pedirá usuario y contraseña de nuestro Ubuntu.

![Reinicio Ubuntu](images/reinicioubuntu.png)

- Una vez hecho esto, ¡Ubuntu estará listo para la acción!

![Ubuntu en acción](images/comandosubuntu.png)

### ** 5- Comprobando existencia**
- Nos aseguramos de que Ubuntu esté instalado y corriendo con `wsl -l -v`.
  
![Ubuntu funcionando](images/ubuntucorriendo.png)
  
### ** 6- ¡Debian en escena!**
- Para lanzar Debian, simplemente tecleamos su nombre en Powershell, Debian. Nos solicitará usuario y contraseña y ¡listo para la acción!

![Debian activo](images/debiancorriendo.png)

### ** 7- Doble comprobación**
- Finalmente, aseguramos que ambas versiones funcionen y estén operativas con `wsl -l-v`.

![Dos versiones](images/dosversiones.png)
