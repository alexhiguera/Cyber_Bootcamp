# hacking web

### 1 - INTRODUCCIÓN A LAS APLICACIONES WEB Y BURP SUITE
U1M3 - Ataques Aplicaciones Web
Diferencias GET Y POST
HTTP status code

### 2 - AUTENTICACIÓN Y FUERZA BRUTA
Password Strength

### 3 - INYECCIÓN DE COMANDOS Y WEBSHELL
Command Injection cheetsheet
Código URI

### 4 - INYECCIÓN SQL
Inyección SQL
SQLMap Cheetsheet

### 5 - CROSS-SITE SCRIPTING
U1M3 - Cross-Site Scripting
Inyección Cross-Site Scripting

---

Protocolo HTTP
Mensajes HTTP, peticiones y respuestas
Métodos HTTP
Partes petición HTTP
Ataques aplicaciones web:
  Payload Box
¿Qué es una aplicación web?
Páginas web estáticas vs dinámicas
Pilas Fullstack
Herramientas de desarrollo:
  Chrome
  Mozilla Firefox
Herramientas:
  Dirbuster
  Dirb
  Nikto2
  OWASP ZAP
  Burp Suite
Instalar certificado en el navegador

---
# Recursos I

HTTP - Concepto, para qué sirve y cómo funciona
https://concepto.de/http/?authuser=1

Mensajes HTTP - HTTP | MDN
https://developer.mozilla.org/es/docs/Web/HTTP/Messages?authuser=1

Métodos de petición HTTP - HTTP | MDN
https://developer.mozilla.org/es/docs/Web/HTTP/Methods?authuser=1

Anatomía de una petición HTTP – Felipe Gavilán
https://gavilanch.wordpress.com/2019/01/03/anatomia-de-una-peticion-http/?authuser=1#:~:text=Resumen,de%20estatus%2C%20cabecera%20y%20cuerpo

Los 5 ataques a sitios web más comunes y cómo defenderse de ellos
https://www.websiterating.com/es/online-security/most-common-website-attacks-how-to-defend-against-them/?authuser=1

Payload Box · GitHub
https://github.com/payloadbox?authuser=1

¿Qué es una web app y qué clases hay? - IONOS España
https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/que-es-una-web-app-y-que-clases-hay/?authuser=1

Paginas web dinámicas y estáticas - Irekisoft
https://www.irekisoft.net/servicios-informaticos/paginas-web-dinamicas-y-estaticas/?authuser=1#:~:text=En%20las%20p%C3%A1ginas%20web%20est%C3%A1ticas,es%20f%C3%A1cilmente%20y%20frecuentemente%20modificado

Una introducción a la pila LAMP, LEMP, MEAN, XAMPP, WAMP y AMPPS
https://geekflare.com/es/lamp-lemp-mean-xampp-stack-intro/?authuser=1

Usar herramientas de desarrollo de Chrome para revisar etiquetas - Ayuda de Campaign Manager 360
https://support.google.com/campaignmanager/answer/2828688?hl=es&authuser=1#:~:text=Acceder%20a%20herramientas%20de%20desarrollo,alt%2Bcomando%2Bi%22

¿Cuáles son las herramientas de desarrollo del navegador? - Aprende desarrollo web | MDN
https://developer.mozilla.org/es/docs/Learn/Common_questions/What_are_browser_developer_tools?authuser=1

dirbuster | Kali Linux Tools
https://tools.kali.org/web-applications/dirbuster?authuser=1

dirb | Kali Linux Tools
https://www.kali.org/tools/dirb/?authuser=1

Nikto 2.5 | CIRT.net
https://cirt.net/Nikto2?authuser=1

ZAP
https://www.zaproxy.org/?authuser=1

burpsuite | Kali Linux Tools
https://tools.kali.org/web-applications/burpsuite?authuser=1

Burp Suite I: La Navaja Suiza del Pentester – Follow The White Rabbit
https://fwhibbit.es/burp-suite-i-la-navaja-suiza-del-pentester?authuser=1

Burp Suite for Beginners Part 1: Setup and Target/Proxy Tools ~ Constellations
https://jaimelightfoot.com/blog/burp-suite-for-beginners-setup-and-target-proxy-tools/?authuser=1

Burp Suite for Beginners Part 2: Spider, Intruder and Repeater ~ Constellations
https://jaimelightfoot.com/blog/burp-suite-for-beginners-part-2-spider-intruder-and-repeater/?authuser=1

Burp Suite: Potente herramienta para Pentesting Web. - Backtrack Academy
https://backtrackacademy.com/art

---

# Recursos II


Authentication - OWASP Cheat Sheet Series
https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html?authuser=1

Autenticación vs autorización: Diferencias y ejemplos de cómo funcionan
https://www.redeszone.net/tutoriales/seguridad/diferencias-autenticacion-autorizacion/?authuser=1

Web Authentication Methods Explained - RisingStack Engineering
https://blog.risingstack.com/web-authentication-methods-explained/?authuser=1

Mecanismos de Autenticación Web
https://blog.a3sec.com/autenticaci%C3%B3n-de-acceso-b%C3%A1sica-http?authuser=1

Autenticación HTTP
https://diego.com.es/autenticacion-http?authuser=1

Autenticando una API con JWT · developerro
https://www.developerro.com/2019/03/12/jwt-api-authentication/?authuser=1

Passwortcheck
https://www.passwortcheck.ch/passwortcheck/passwortcheck?authuser=1
Enlace
https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt?authuser=1

GitHub - kaonashi-passwords/Kaonashi: Wordlist, rules and masks from Kaonashi project (RootedCON 2019)
https://github.com/kaonashi-passwords/Kaonashi?authuser=1

Adios Rockyou.txt - Bienvenido Kaonashi.txt – Snifer@L4b's
https://sniferl4bs.com/2020/02/adios-rockyou.txt-bienvenido-kaonashi.txt/?authuser=1

5 Ways to Create Dictionary for Bruteforcing - Hacking Articles
https://www.hackingarticles.in/5-ways-create-dictionary-bruteforcing/?authuser=1

Burp Intruder - PortSwigger
https://portswigger.net/burp/documentation/desktop/tools/intruder/using?authuser=1

Burp Suite brute force HTTP Basic authentication, brute force, brute force burpsuite, burp suite web app
https://securityonline.info/use-burp-suite-brute-force-http-basic-authentication/?authuser=1

hydra | Kali Linux Tools
https://www.kali.org/tools/hydra/?authuser=1

[THC-Hydra] Tutorial (explicación modo de uso) + Video ~ Blackploit [PenTest]
https://www.blackploit.com/2010/10/thc-hydra-tutorial-explicacion-modo-de.html?authuser=1

Hydra: cómo funciona esta herramienta para romper contraseñas
https://www.redeszone.net/tutoria

---

# Recursos III

 INYECCIÓN DE COMANDOS Y WEBSHELLQue es y como prevenir command injection
Métodos command injection
OWASP Command Injection
OS Command Injection
Commix
Qué es Webshell
Ejemplos Webshells
Command Injection Payload List

Qué es Command Injection y cómo prevenirla - Hackmetrix Blog
https://blog.hackmetrix.com/command-injection/?authuser=1

Métodos de ataque: Command Injection - Cristian Thous - Ciberseguridad al alcance de todos
https://cristianthous.com/metodos-de-ataque-command-injection?authuser=1

Command Injection | OWASP Foundation
https://owasp.org/www-community/attacks/Command_Injection?authuser=1

What is OS command injection, and how to prevent it? | Web Security Academy
https://portswigger.net/web-security/os-command-injection?authuser=1

Commix, una completa herramienta para auditar y explotar páginas web
https://www.redeszone.net/2015/07/20/commix-una-completa-herramienta-para-auditar-y-explotar-paginas-web/?authuser=1

GitHub - commixproject/commix: Automated All-in-One OS Command Injection Exploitation Tool.
https://github.com/commixproject/commix?authuser=1

commix | Kali Linux Tools
https://www.kali.org/tools/commix/?authuser=1

Commix-Command Injection Exploiter (Beginner’s Guide) - Hacking Articles
https://www.hackingarticles.in/commix-command-injection-exploiter-beginners-guide/?authuser=1

Web shell: Qué es, cómo funciona y cómo proteger tus sistemas
https://www.redeszone.net/tutoriales/seguridad/que-es-web-shell-ataques-remotos/?authuser=1

awesome-webshell/Readme_en.md at master · alphaSeclab/awesome-webshell · GitHub
https://github.com/alphaSeclab/awesome-webshell/blob/master/Readme_en.md?authuser=1

GitHub - TheBinitGhimire/Web-Shells: Some of the best web shells that you might need!
https://github.com/TheBinitGhimire/Web-Shells?authuser=1

webshell/php/PHPshell/c99 at master · tennc/webshell · GitHub
https://github.com/tennc/webshell/tree/master/php/PHPshell/c99?authuser=1

GitHub - payloadbox/command-injection-payload-list: 🎯 Command Injection Payload List
https://github.com/payloadbox/command-injection-payload-list?authuser=1

Reverse shells · GitHub
https://gist.github.com/sckalath/67a

---

# Recursos IV

 INYECCIÓN SQL
Aprende SQL en 10 minutos
Fundamentos de Bases de Datos
Tipos de datos
Curso básico de SQL
Ataques SQL Injection y Contramedidas
Generic SQL Injection Payload List
Using Burp Suite to Exploit SQL Injection Vulnerabilities
Tutorial SQLMap
SQL Injection (SQLi) Payload List
Como protegerse de SQLi

SQL desde cero: Aprende SQL en 10 minutos
Vídeo de YouTube • ‪10 minutos‬

Fundamentos de Bases de Datos - Tablas, campos y registros
https://disenowebakus.net/creando-bases-de-datos.php?authuser=1

Tipos de datos en MySQL para una base de datos SQL
https://disenowebakus.net/tipos-de-datos-mysql.php?authuser=1

Intro a SQL y MySQL - Contenido / indice
http://nachocabanes.com/sql/curso/index.php?authuser=1

Sql Injection tipos ejemplos y contramedidas - Byte Mind
https://byte-mind.net/sql-injection-tipos-ejemplos-y-contramedidas/?authuser=1

GitHub - payloadbox/sql-injection-payload-list: 🎯 SQL Injection Payload List
https://github.com/payloadbox/sql-injection-payload-list?authuser=1

Using Burp to Exploit SQL Injection Vulnerabilities: The UNION Operator - PortSwigger
https://portswigger.net/support/using-burp-to-exploit-sql-injection-vulnerabilities-the-union-operator?authuser=1

Blog elhacker.NET: Tutorial - Manual SQLmap: ataques SQLi - Inyección SQL
https://blog.elhacker.net/2014/06/sqlmap-automatizando-ataques-sqli-injection.html?authuser=1

Ataques de inyección SQL: qué son y cómo protegerse | Hostalia – Pressroom
https://pressroom.hostalia.com/white-papers/ataques-inyeccion-sql/?authuser=1

---

# Recursos V

 CROSS-SITE SCRIPTING
Elementos HTML
¿Qué es XSS? Ejemplos, tipos y como prevenirlos
Google Application Security - Cross-site Scripting
XSS Injections
Ataques XSS
XSS Payload list
Discover XSS Security Flaws by Fuzzing with Burp Suite, Wfuzz & XSStrike
Portswiger XSS
XSStrike
XSS Loader

<a>: El elemento ancla - HTML: Lenguaje de etiquetas de hipertexto | MDN
https://developer.mozilla.org/es/docs/Web/HTML/Element/a?authuser=1

Ataques XSS: Cross-Site Scripting en PHP
https://diego.com.es/ataques-xss-cross-site-scripting-en-php?authuser=1

Learn | Google Bug Hunters - Google Bug Hunters
https://www.google.com/intl/sw/about/appsecurity/learning/xss/?authuser=1

PayloadsAllTheThings/XSS Injection at master · swisskyrepo/PayloadsAllTheThings · GitHub
https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20Injection?authuser=1#xss-in-htmlapplications

Ataques XSS | H1RD.COM
http://www.h1rd.com/hacking/Ataques-xss?authuser=1

GitHub - payloadbox/xss-payload-list: 🎯 Cross Site Scripting ( XSS ) Vulnerability Payload List
https://github.com/payloadbox/xss-payload-list?authuser=1

Discover XSS Security Flaws by Fuzzing with Burp Suite, Wfuzz & XSStrike « Null Byte :: WonderHowTo
https://null-byte.wonderhowto.com/how-to/discover-xss-security-flaws-by-fuzzing-with-burp-suite-wfuzz-xsstrike-0189971/?authuser=1

Cross-Site Scripting (XSS) Cheat Sheet - 2024 Edition | Web Security Academy
https://portswigger.net/web-security/cross-site-scripting/cheat-sheet?authuser=1

GitHub - s0md3v/XSStrike: Most advanced XSS scanner.
https://github.com/s0md3v/XSStrike?authuser=1

GitHub - capture0x/XSS-LOADER: Xss Payload Generator ~ Xss Scanner ~ Xss Dork Finder
https://github.com/capture0x/XS