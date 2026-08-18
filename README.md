# FTP — Investigación y análisis de tráfico de red
### Objetivo
Evaluar una captura de red para determinar la posible existencia de un incidente relacionado al protocolo FTP utilizando la herramienta Wireshark
### Herramientas
<ul>
 <li>Wireshark</li>
 <li>Archivo PCAP</li>
 </ul> 
### Hallazgos y análisis
<ul>
  <li>Se determino el hallazgo de trafico FTP</li>
  <li>Se evidenciaron varios intentos de autenticación</li>
  <li>Se constato un inicio de sesión exitoso</li>
  <li>Se encontraron comandos para listar, descargar y subir archivos</li>
</ul>

### Conclusión
Aprendí que el protocolo FTP transmite los datos sin ningún tipo de cifrado, por lo que, al analizar una captura de red, es posible visualizar información sensible como nombres de usuario, contraseñas y los comandos ejecutados.
