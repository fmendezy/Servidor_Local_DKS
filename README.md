# Servidor Local de Pruebas Pre-configurado - vRO
*** Sin soporte y descontinuado, última actualización y rev de rA Febrero de 2017, utilizelo solo para aprender y entender.- ***
Un servidor local pre-configurado por mi, para que los nuevos miembros del equipo Valhallen Ragnarok puedan practicar y adentrarse al mundo de *Athena.
Estos archivos estan compartidos de forma publica, sin embargo estan destinados principalmente para el Staff de Valhallen Ragnarok.
https://www.facebook.com/ValhallenRagnarok/
* Si detectas algún error o problema te agradecería pudieras informarlo.
- ¡Gracias por preferir mi trabajo!

#Incluye
- Cliente para el juego.
- Servidor SQL (rASql) pre-cargado con las base de datos.
- Emulador pre-configurado (rAthena).

#Requisitos
1. Tener un PC Windows.
2. Tener un programa GIT para descargar todo el contenido. (Recomiendo TortoiseGIT)
3. Tener Ragnarok Online al menos actualizado hasta Noviembre de 2015.
4. Tener la carpeta "data" vacia. Puedes borrar su contenido, puedes encontrar esta carpeta en donde tienes el juego instalado.
En caso que no la tengas, esta bien.

#Forma de uso
1. Deberás compilar rAthena utilizando Visual Studio Express 2012. Descargar aquí: https://www.microsoft.com/es-cl/download/details.aspx?id=34673 . Si no sabes como compilar más abajo esta una mini guía. (¿Quieres saber como Registrar el programa legalmente y gratis?: https://msdn.microsoft.com/es-es/library/ms246592(v=vs.80).aspx )

2. Deberás abrir rAsql con "mysql_start.bat", presionar cualquier tecla y aceptar el siguiente mensaje con "Yes", luego aparecerá una ventana con el "Session Manager", dale a "New" y ingresa los siguiente User: ragnarok password: ragnarok presiona "Open" y dale a "Yes". Listo, ahora esa ventana déjala minimizada y no la cierres si trabajas en el servidor local.

3. En la carpeta rAthena iniciaremos el emulador abriendo el archivo "runserver.bat", espera que carguen las 3 consolas estas representan el char, login y map server.
Nota: No lo cierres si vas a trabajar en tu servidor local, solo cierralas cuando termines de trabajar.

4. Todo el contenido de la carpeta "Cliente" debe ir en tu carpeta de Ragnarok, para entrar a tu servidor local abre el archivo "Cliente_Local_Server-vRO_Staff.exe"
La cuenta por defecto es:

# Datos de Acceso dentro del Juego
- USUARIO: GM01
- CONTRASEÑA: GM01
- CORREO: a@a.com
- NIVEL DE GM: 99

Nota: Esta habilitado el doble login y la posibilidad de crearte cuentas con _F o _M desde la ventana de inicio de sesión.

# ¿Como compilar?
1. Una vez teniendo instalado Visual Studio Express 2012, vas a la carpeta de tu rAthena, abrir el archivo "rAthena-12.sln" (Se abrirá con el programa Visual Studio).
2. En la parte superior verás las opciones en un menu desplegable "Debug" y a su costado derecho  "Win32", cambia Debug por "Release".
3. En la ventana de soluciones, a la izquierda normalmente, hacer click derecho con el ratón en "Solution 'rAthena-12' (4 Projects)" y hacer click en "Build Solution", con esto compilaras el emulador por primera vez. Si en el futuro vuelves a compilar, presionas siempre "Rebuild Solution"
4. Si el proceso de compilación es satisfactorio, tendrás una notificación de que tres nuevos archivos .EXE estarán en la carpeta raiz de tu emulador rAthena. 

# Más?
¿Dudas?, ¿Consultas? Por favor realicelas en el foro de rAthena.
Me encuentro retirado del Ragnarok Online definitivamente, lamento no poder ayudarte. ¡Si investigas mucho y piensas 3 veces las cosas estoy seguro que lograrás a solucionar cualquier problema con el emulador! Así lo hice yo en 2010... cuando comenzé.
¡Hasta siempre leyendas!
