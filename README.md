# Instalación y configuración de Apache

### Introducción
El presente trabajo recoge la instalación y configuración del servidor web Apache, una actividad realizada en el módulo de Desarrollo de Aplicaciones Web del segundo curso del CFGS impartido en el I.E.S. Juan Bosco, situado en Alcázar de San Juan, España. La práctica tenía como objetivo comprender el funcionamiento de un servidor web real y los pasos necesarios para ponerlo en marcha dentro de un entorno académico.
Como antecedente histórico, Apache es un servidor web de código abierto cuyo desarrollo comenzó en 1995, cuando un grupo de desarrolladores decidió continuar el trabajo sobre el servidor NCSA HTTPd, que en aquel momento había dejado de recibir actualizaciones. Su nombre surge tanto como referencia al pueblo nativo Apache como por el juego de palabras “a patchy server”, ya que originalmente se construyó a base de múltiples parches aplicados al código de NCSA.
El servidor web Apache permite que las páginas web funcionen correctamente: recibe peticiones HTTP o HTTPS, las procesa y envía una respuesta al cliente, actuando como enlace entre ambos extremos de la comunicación.

### Alternativas al servidor Apache

* Nginx
   * Muy ligero y eficiente.
   * Maneja gran cantidad de conexiones simultáneas usando pocos recursos.
   * Adecuado como proxy inverso, balanceador de carga y servidor de caché.

* LiteSpeed

   * Solución comercial.
   * Compatible con configuraciones de Apache.
   * Gran rendimiento con PHP.
   * Incluye funciones de seguridad y caché integradas.

* Caddy
   * Servidor moderno y fácil de configurar.
   * HTTPS automático por defecto.
   * Multiplataforma y ligero.

* Microsoft IIS
   * Integración completa con el ecosistema Windows.
   * Administración visual simple.

* Tomcat
   * Especializado en aplicaciones desarrolladas en Java.

* Node.js
   * Aunque no es un servidor web tradicional, permite servir contenido HTTP.
   * Ideal para aplicaciones dinámicas y en tiempo real.
   * Excelente rendimiento en operaciones de entrada y salida.

* Cherokee
   * De código abierto.
   * Sencillo de usar y configurar.
   * Incluye funciones como autenticación, balanceo y proxy.

### Objetivo de la práctica

El objetivo de la práctica consistía en configurar Apache como servidor intermediario que posibilita la comunicación entre un cliente y un servidor. Mediante esta actividad se pretende entender la importancia de un servidor web en una infraestructura y adquirir experiencia directa en su instalación y administración.
### Cuerpo
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/1.png)  
Actualizo apt  
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/2.png)  
Instalo apache2
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/3.png)  
Reviso mi ip
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/4.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/5.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/6.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/7.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/8.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/9.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/10.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/11.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/12.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/13.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/14.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/15.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/16.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/17.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/18.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/19.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/30.png)
![](https://github.com/JosecarlosGlr/PracticaApache/blob/main/31.png)
### Conclusión
La realización de esta práctica ha permitido comprender de forma clara el papel fundamental que desempeña un servidor web dentro de cualquier proyecto online. A través de la instalación y configuración de Apache, se ha podido ver cómo se gestionan las peticiones de los clientes y cómo se establece la comunicación con el servidor para ofrecer contenido de manera eficiente. Además, conocer alternativas como Nginx, Caddy o LiteSpeed ayuda a ampliar la visión sobre las diferentes soluciones existentes en el ámbito profesional. En conjunto, la actividad ha servido para afianzar conceptos esenciales y adquirir experiencia práctica útil para futuros desarrollos web.
### Bibliografía
