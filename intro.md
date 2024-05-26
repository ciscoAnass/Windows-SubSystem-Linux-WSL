# Introducción a WSL

### Definición y Propósito de WSL
El Subsistema de Windows para Linux (WSL) permite a los desarrolladores ejecutar un entorno GNU/Linux en una máquina Windows, sin la sobrecarga de una máquina virtual.



<img src="/img/bbb.jpg" alt="logo"></img>


-- foto
***
### Diferencias Clave entre WSL 1 y WSL 2
- **WSL 1:** Usa una capa de compatibilidad para ejecutar binarios de Linux. Es más ligero en uso de recursos.
- **WSL 2:** Utiliza un núcleo de Linux real dentro de una máquina virtual ligera, ofreciendo mejoras en rendimiento y compatibilidad.


| Característica          | WSL 1                                          | WSL 2                                        |
|-------------------------|-----------------------------------------------|---------------------------------------------|
| **Arquitectura**        | Capa de compatibilidad para ejecutar binarios de Linux | Núcleo de Linux real dentro de una VM ligera |
| **Rendimiento de E/S**  | Más lento debido a la traducción de llamadas del sistema | Más rápido gracias al uso del núcleo real    |
| **Compatibilidad**      | Menor compatibilidad con aplicaciones de Linux | Mejor compatibilidad con aplicaciones de Linux |
| **Uso de Recursos**     | Menor uso de recursos                          | Mayor uso de recursos debido a la VM        |
| **Inicio**              | Inicio más rápido                             | Inicio más lento debido a la VM             |
| **Redes**               | Comparte la pila de red con Windows            | Tiene una pila de red separada              |

---
