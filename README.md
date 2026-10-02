# Parche para traducir al castellano Succubus Nightmare

Este manual detalla paso a paso para parchear el juego Succubus Nightmare e incluir idioma castellano.

---

## Tabla de Contenidos
1. [Requisitos Previos](#1-requisitos-previos)
2. [Parcheo](#2-parcheo)
3. [Solución de Problemas Frecuentes](#3-solución-de-problemas-frecuentes)

---

## 1. Requisitos Previos

1. **parcheador_juegos_unreal_engine5**: Descárgalo [aquí](https://github.com/traductorjuegos/parcheador_juegos_unreal_engine5).
2. **parche_Succubus_Nightmare_ES-es.json**: Incluído en este mismo repo.
---

## 2. Parcheo

1. Ejecuta parcheador_juegos_unreal_engine5
2. Selecciona la ubicación donde has descargado el parche **parche_Succubus_Nightmare_ES-es.json**
3. Selecciona la ubicación donde se encuentra el fichero ejecutable del juego que se llama XX-Win64-Shipping.exe (Donde XX es el nombre del juego). 
  - Generalmente se encuentra dentro de la ruta de instalación, en las subcarpetas NombreDelJuego/Binaries/Win64
4. Marca:
	- Normalizar caracteres especiales
	- Configurar inicio automático en Español
	- Crear copia de seguridad de los paquetes originales
5. Pulsa en PARCHEAR JUEGO.
6. Tras parchear con éxito, pulsa JUGAR.

## 11. Solución de Problemas Frecuentes


### Cuando voy a parchear sale un error y pide clave AES para desencriptar.
* Lamentablemente esa versión del juego está encriptada y si desconoces la clave no podemos hacer nada _legal_ por parchearlo.

### Quiero quitar el parche del juego y dejarlo como estaba antes.
* Si pulsaste la opción _Crear copia de seguridad de los paquetes originales_ cuando aplicaste el parche, abre el parcheador, localiza el ejecutable del juego y pulsa en **Restaurar Original**.

### No restaura bien el original cuando pulso
* Accede a la carpeta de instalación del juego y luego busca el directorio NombreDelJuego/Content/Paks. Si ves un fichero que se llama _NombreDelJuego-Windows.pak_ y otro que se llama _NombreDelJuego-Windows.pak.orig_, borra el fichero _NombreDelJuego-Windows.pak_ y renombra el fichero _NombreDelJuego-Windows.pak.orig_ como _NombreDelJuego-Windows.pak_.
