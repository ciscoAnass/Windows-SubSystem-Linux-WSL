### **1- ¿Qué más hay en el menú?**
- Chequeamos otras distribuciones disponibles con el comando `wsl --list --online`.

```powershell
wsl --list --online
```

### ** 2- Expandiendo horizontes**
- También ponemos a **Debian** en la lista con `wsl --install -d Debian`.

```powershell
wsl --install -d Debian
```

### ** 3- Reinicia y listo**
- Luego de instalar ambas distribuciones, es hora de **reiniciar** el PC. Al encenderlo de nuevo, nos pedirá usuario y contraseña de nuestro Ubuntu.

```powershell
Restart-Computer 
```


### ** 4- ¡Debian en escena!**
- Para lanzar Debian, simplemente tecleamos su nombre en Powershell, Debian. Nos solicitará usuario y contraseña y ¡listo para la acción!


### ** 5- Comprobando existencia**
- Nos aseguramos de que Ubuntu esté instalado y corriendo con `wsl -l -v`.

```powershell
wsl -l -v
```

