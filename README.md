<H1>HID - PAYLOAD RUBBER DUCKY - WE 💛 🦆 </H1>
<br>
 <p>¡Buenas tardes, señoras y señores! Ahora que ya tienen el keylogger principal de mi otro repositorio, y veo que siguen leyendo 👨‍💻 empiezan a ser personas de bien.</p>
 <p>Tras un escenario virtualizado, y tras la presentación, de nuestro anterior repositorio, ya estamos listos para proceder a la infección de la supuesta victima, a través de técnicas de ingeniería social, o mediante exploits.</p>
 <br><p>En nuestro procedimiento, usaremos un tipo de exploit, que además, <b>funciona actualmente</b>. Lo que haremos, es emular un dispositivo de interfaz humana (HID). ✅</p><br>
 <p><h3>💻 REQUISITOS </h3></p>  <ul> <li><a href="https://amzn.to/49gn7gZ" target="blank_"> BAD USB CJMCU</a></li> <li><a href="https://amzn.to/47T6dUk" target="blank_">MicroSD</a></li> <a href="https://amzn.to/3uduel2" target="blank_"><li>Lector/grabador MicroSD</li></a> <a href="https://downloads.arduino.cc/arduino-ide/nightly/arduino-ide_nightly-latest_Windows_64bit.zip" target="blank_"><li>Arduino IDE</li></a><a href="https://github.com/Seytonic/Duckduino-microSD/blob/master/Duckduino-microSD/Duckduino-microSD.ino" target="blank_"><li>Sketch teclado</li></a></ul><br>
  <p>Tienes el keylogger listo? tienes un cliente? tienes un rootkit? 👍 Con este payload podrás instalar cualquier script de pruevas aunque este plagado de virus. ⚠ pero he de recordarte que la utilización de este payload es bajo tu propia responsabilidad. </p><br><h3>📀 INSTALACIÓN</h3>
 <ul><li>Vamos al BAD USB CJMCU (nuevo, significa tal cual lo compras)</li> <li>instalamos el paquete oficial de <a href="https://downloads.arduino.cc/arduino-ide/nightly/arduino-ide_nightly-latest_Windows_64bit.zip" target="blank_">Arduino</a></li>
<li>Abrimos Arduino, cargamos el sketch de <a href="https://github.com/Seytonic/Duckduino-microSD/blob/master/Duckduino-microSD/Duckduino-microSD.ino" target="blank_">Duckduino</a>. Cambia la línea 27, y pones <code>Keyboard.begin (KeyboardLayout_es_ES)</code></li> <li>Súbelo a la placa BAD USB CJMCU. 📤</li> <li> Paso final: Usar un SO virtual para la puesta en escena. Cargar el payload.</li></ul><br><h3>⚡FUNCIONAMIENTO</h3><p>Este script solo se ha probado en Microsoft Windows 10, pero creemos que funciona desde su versión 7.</p>
<br>
...............................................................................................................
 <br>         
<h3>🔎 RESULTADO DEL SCRIPT</h3><br>
<p>Ahora tu BAD USB CJMCU, con el sketch de <b>"emulador de dispositivo HID"</b> tendrá la función correcta: al insertarla en cualquier máquina con Windows; ejecutará una serie de comandos, según los atajos de teclado que registremos en un documento de texto con nombre script.txt.</p>
<p>Tengo un payload rubber ducky, de nombre "script.txt": Lo primero que hace es deshabilitará su seguridad, descargará un spyware comprimido, lo descomprimirá, lo ejecutará en el inicio de Windows y borrará los comandos usados.</p>
<p>Yo lo comparto con vosotros, no me hago responsable de vuestro uso, y como persona de bien os o vuelvo a recordar, que siempre que utilizeis este tipo de herramientas, lo hagais en un entorno controlado y ético.</p>
SALUDOS 😉
