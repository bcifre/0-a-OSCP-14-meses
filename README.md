
# De 0 a OSCP en 14 meses?

A continuación voy a contar mi experiencia desde que decidí introducirme al mundo de la seguridad, hasta el día de hoy que me encuentro en el mes 11, recibiendo hoy el material para realizar el curso [PWK(Penetration Testing with Kali Linux)](https://www.offensive-security.com/pwk-oscp/).

Si todo sale según lo planificado en febrero del 2021 estaré dando el examen.

# Conocimientos previos (8 meses)
Cuando decidí introducirme en el mundo de la seguridad, tenía un background de 4 años como programador web (sin título universitario, 100% autodidacta), en los lenguajes de programación php y javascript principalmente.
Conocí el pentesting gracias a los videos de [Julio Ureña](https://www.youtube.com/channel/UC2o1vzpUIvgf0VMJIMKZ_rQ) por casualidad en Youtube y me dio curiosidad aprender sobre hacking.

El hecho de no entender nada de los videos que subía sobre Hack the Box, hizo que me interesara por la seguridad, particularmente el pentesting.A medida que iba investigando me daba cuenta que necesitaba reforzar esos conocimientos base sobre redes y administración de sistemas, para tener una idea en el momento que decidí aprender seguridad no sabía absolutamente nada de linux, no tenía idea que era TCP-IP, no sabía python, ni bash, ni powershell, no entendía como funcionaba el protocolo http, no entendía como funcionaban los puertos de una computadora, solo sabía que http funcionaba en el puerto 80 pero no sabía que era un puerto, ni sabía cual era la diferencia entre http y https, solo que https era más seguro que http pero no sabía porqué.

Ya tenía algunos años de experiencia como programador pero no estaba cerca de ser un programador avanzado, el conocimiento que tenía era por la experiencia que había obtenido en esos años de trabajo y lo que había aprendido de manera autodidacta.

Aclaro estas cosas para tener una idea de cuales eran mis conocimientos en mi punto de partida, ya que cuando uno comienza a aprender sobre seguridad no sabe por donde empezar y nos preguntamos cuáles son los conociminetos previos que necesitamos para subir al siguiente nivel.
Básicamente para querer aprender sobre seguridad, específicamente pentesting que es sobre lo que se trata la certificación OSCP, debemos aprender 3 grandes ramas de la computación: 
- Redes de computadoras
- Administración de sistemas (Linux y Windows) 
- Programación.

No es necesario ser experto en las 3 áreas pero sí tener conocimientos generales sobre las mismas, debemos entender  el protocolo TCP-IP, sabemos saber cuales son los principales servicios que tiene un servidor, debemos saber sobe DNS, HTTP, FTP, SMTP, SSH, etc.

Alguna vez tuvimos que tratar de entender como funciona un router, un switch, entender las diferentes capas del modelo OSI, es imposible profundizar en todo, pero aveces está bueno profundizar en algunos temas, en los que te dé mas curiosidad. Hay que tener curiosidad y ganas de aprender cuando uno quiere dedicarse a la seguridad, porque el camino es largo y algunas cosas son complicadas de entender.

Como ya lo mencioné, las bases de la seguridad informática se dividen en 3 grandes ramas, en mi caso ya tenía cubierta el área de programación, aunque en mí opinión de las 3 ramas es la menos importante.
Cada uno sabrá cuál es su background y cuales son los conocimientos que debe reforzar.

Ésta es mi experiencia, a la fecha de hoy aún no he obtenido el OSCP, pero tomando en cuenta desde que comencé en esta aventura hasta la posible fecha de que obtenga la certificación, serían 14 meses de tener 0 conocimientos en seguridad hasta conseguir mi OSCP.
En el caso de que comiences sin ningún conocimiento en ninguna de las 3 áreas anteriores, quizás te lleve un tiempo más pero bueno, todo depende de cada uno, de su velocidad de aprendizaje, de cuanto profundizamos en cada tema  y de cuánto tiempo le dediquemos a estudiar.

Cuando decidí aprender sobre seguridad, el tiempo que dedicaba a estudiar por día fue de 2 a 3 horas 6 días a la semana en promedio, aveces más aveces menos.
Principalmente éstos son los recursos que utilicé, en total fueron muchos más ya que aveces me interesaba aprender sobre un tema en particular y bueno,en esos casos Google es tu mejor amigo.

Es muy importante saber inglés ya que hay mucha más información y de mejor calidad, y las certificaciones son en ese idioma.
Mi nivel de inglés es el mínimo para poder leer, escuchar y entender, cuando comencé mi nivel era bajísimo y empezar a estudiar seguridad hizo que mejorara mi nivel, así que si tienes un nivel bajo en inglés te recomendaría dedicarle un tiempo extra a mejorar el idioma y así poder aprovechar mejor los recursos.

Todo lo que está a continuación, son los mejores cursos que encontré y los hice o leí en su totalidad.
Recomiendo mucho leer el libro de Kurose y mirar el curso de Facultad de Ingeniería, para aquellos que no tengan conocimientos en redes de computadoras.
Es imposible que en tan poco tiempo puedas estudiar a detalle todos éstos temas, lo importante es empezar con uno, profundizar en algunos puntos si es de tu interés y seguir con el siguiente.
En algunos casos tuve que volver a ver o leer algunos temas varias veces.

## Networking

* [thenewboston (Youtube)](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBpuvPW0aHa7mKdn_k9SPKO)
* [Ben Eater (Youtube)](https://www.youtube.com/watch?v=XaGXPObx2Gs&list=PLowKtXNTBypH19whXTVoG3oKSuOcw_XeW&ab_channel=BenEater)
* [Curso de redes de Facultad de Ingeniería](https://open.fing.edu.uy/courses/redes-2020/1)
* [routergods (Youtube)](https://www.youtube.com/watch?v=B_VOGH5GJhw&list=PLB81131936C01C592&index=3&ab_channel=routergods)
* [Curso CompTIA Network+ (Youtube)](https://www.youtube.com/watch?v=vrh0epPAC5w&list=PLIcYJYYAJ6bm5X6Pb3iSXbSmsrO5xf6kN&index=17&t=274s&ab_channel=PowerCertAnimatedVideos)
* [Professor Messer CompTIA Network+ (Youtube)](https://www.youtube.com/watch?v=IErQm8wsaxg&list=PLG49S3nxzAnmpdmX7RoTOyuNJQAb-r-gd&ab_channel=ProfessorMesser)
* [CompTIA Network+ Certification (Udemy)](https://www.udemy.com/comptia-network-cert-n10-007-the-total-course/)

Libros

* [Kurose - Computer Networking: A Top-Down Approach](https://www.amazon.com/-/es/James-F-Kurose/dp/0132856204)
* [Richard Stevens - TCP/IP Illustrated](https://www.amazon.com/TCP-Illustrated-Protocols-Addison-Wesley-Professional/dp/0321336313)


## Administración de sistemas

* [Eli the Computer Guy -
Windows Server (youtube)](https://www.youtube.com/watch?v=dIFKmJ4wufc&list=PLJcaPjxegjBVnEN8c6O8w1mNit4WGeAWN&ab_channel=ElitheComputerGuy)
* [ICT Solutions Trainer - Windows Server (Youtube)](https://www.youtube.com/watch?v=lrtYDS5WKR0&list=PLYogJ_kxL1wTesq-vNxEc8tjDOHvszeWf&ab_channel=ICTSolutionsTrainer)
* [tutoriaLinux-  The Linux Basics Course: Beginner to Sysadmin, Step by Step (Youtube)](https://www.youtube.com/watch?v=bju_FdCo42w&list=PLtK75qxsQaMLZSo7KL-PmiRarU7hrpnwK&ab_channel=tutoriaLinux)

## Pentesting y seguridad


* [CCNA Security (Youtube)](https://www.youtube.com/watch?v=Lb_KzcbJlfQ&list=PLNkXmZZpB7dyRsMsPQ2YIanLT5tH1gT4j&ab_channel=CCNANEW)
* [Jason Dion Comptia Pentest + (Udemy)](https://www.udemy.com/course/pentestplus/learn/lecture/10953736#overview)
* [Total Seminars Comptia Pentest + (Udemy)](https://www.udemy.com/course/ethical-hacking-and-comptia-pentest-exam-prep-pt0-001/)
* [freecodecamp - Full Ethical Hacking Course - Network Penetration Testing for Beginners (Youtube)](https://www.youtube.com/watch?v=3Kq1MIfTWCE&ab_channel=freeCodeCamp.org)

## Certificación Comptia Security +

Me llevó unos 3 meses estudiar para ésta certificación, la cual me ayudó para obtener conocimientos generales sobre seguridad informática.
Para poder aprobar la certificación es necesario aprender el temario que dejo a continuación y principalmente el material que utilicé fueron los siguientes:

 [pdf con el temario de la certificación](https://www.comptia.jp/pdf/Security%2B%20SY0-501%20Exam%20Objectives.pdf)

Materiales que usé para la preparar la certificación

Cursos:
* [Professor Messer Comptia Security + (Youtube)](https://www.youtube.com/watch?v=JU5zkddWits&list=PLG49S3nxzAnnVhoAaL4B6aMFDQ8_gdxAy&index=1&ab_channel=ProfessorMesser)
* [ItProTv CompTIA Security+](https://www.itpro.tv/courses/comptia/security-updated-2017/)

Libros:

* [Get Certified Get Ahead](https://www.amazon.com/-/es/Darril-Gibson/dp/1939136059)
* [All-in-One Exam Guide](https://www.amazon.com/-/es/Wm-Arthur-Conklin/dp/1260019322/ref=sr_1_2?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=comptia+security+%2B&qid=1604781407&s=books&sr=1-2)
* [Exam Cram](https://www.amazon.com/-/es/Diane-Barrett/dp/0789759004/ref=sr_1_3?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=comptia+security+%2B&qid=1604781407&s=books&sr=1-3)
* [Study Guide](https://www.amazon.com/-/es/Emmett-Dulaney/dp/1119416876/ref=sr_1_9?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=comptia+security+%2B&qid=1604781407&s=books&sr=1-9)

No es necesario realizar ésta certificación para  hacer el OSCP, pero en mi caso como no tenía nada de conocimientos en seguridad decidí hacerla, ya que una certificación te da un temario en el cuál podes centrarte y poder dedicarte a esos temas, y obviamente también suma para el currículum.

## Otros recursos que utilicé en éste período
Todo lo anterior fue 95% teórico, algo que me costó mucho fue dejar de leer y mirar videos y pasar a la acción, es muy difícil dar ese paso ya que hay que sentirse con confianza y tener los conocimientos para saber que es lo que hay que hacer.
Pentesterlab y el laboratorio de PortSwigger fueron los primeros recursos que me ayudaron a practicar lo aprendido y aprender cosas nuevas, aunque principalmente esos laboratorios son orientados a pentesting web, para el OSCP no recomiendo pasar mucho tiempo en éstos, pero bueno, en ese momento no me había decidido hacer el OSCP.

* [pentesterlab](https://pentesterlab.com/)
* [labs de PortSwigger](https://portswigger.net/web-security)


# Preparación OSCP (3 meses)

En éste período me dediqué a estudiar en promedio 3 horas por día de lunes a viernes y los fines de semana unas 8 a 9 horas.
Algo importante es saber reconocer cuando debemos descansar, en mi caso a medida de que me iba exigiendo cada vez más me daba cuenta que a cada 8 o 9 días debía parar y tomar un descanso porque sentía que no tenía ganas de estudiar y estaba muy estresado.
Esto depende de cada uno, es bueno reconocer cuando a uno le llega el burnout y tomarse un descanso, al otro día vas a estar con más energías. 
En éstos 3 meses me tomé unos 6 días libres aprox.

En éste punto solo tenía "resueltas" 5 máquinas de hack the box, que las hice siguiendo detenidamente videos en youtube y fue antes de hacer la certificación de Comptia Security +, por lo tanto mis conocimientos prácticos en pentesting eran muy pocos y esas maquinas no cuentan, pero al menos me dieron un pantallazo general de lo que es el hacking aunque no tenía ni idea de lo que estaba haciendo.

Para tener una idea de cuáles eran mis conocimientos en éste punto más que nada había practicado ataques web (owasp top 10), tenía una idea general sobre los principales protocolos y protocolos seguros, tenía conocimientos generales sobre hashing, criptografía, arquitectura de redes, TCP-IP, manejo básico de bash y cmd y algo de python.


## Mes 1
El primer mes me dediqué a mirar todos los videos que pude sobre las máquinas que recomiendan de Hack The Box para el oscp ([Lista de NetSecFocus de maquinas recomendadas](https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=1839402159)).
Las cosas que veía que no entendía las anotaba y luego profundizaba pero no mucho ya que el primer mes quería tener un pantallazo general de lo todo lo que necesitaba aprender, ya que la mayoría de maquinas tienen un vector de ataque diferente.

Éste mes no intenté resolver ninguna máquina, solo miré videos y profundizaba un poco en los temas que me interesaban o no tenía claro y seguía con el siguiente video.
Los videos de [Victor García](https://www.youtube.com/c/takito1812/videos) son los que me ayudaron más porque son videos cortos que van directo a la solución de la máquina, y en el caso de querer profundizar en conceptos utilizaba google, los videos de [IppSec](https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA) y [s4vitar](https://www.youtube.com/channel/UCNHWpNqiM8yOQcHXtsluD7Q)


## Mes 2

El segundo mes pagué una suscripción en [Try Hack Me](https://tryhackme.com/) e hice el path de [Offensive Pentesting](https://tryhackme.com/path/outline/pentesting).
Me sobró tiempo en ese mes y aproveché para hacer otros rooms, para tener una idea hice 4900 puntos en ese mes.
Tambíén estuve haciendo el reto [Bandit](https://overthewire.org/wargames/bandit/) de OverTheWire para practicar un poco de bash.

## Mes 3

En el último mes de mi preparación, pagué una suscripción en Hack The Box y me dediqué a resolver todas las máquinas que pude, en total pude conseguir 26 usuarios y 28 roots, un 60% de las máquinas las hice con ayuda pero hice lo mismo que con las máquinas de TryHackMe, intentaba hacerlas solo y en el caso de no poder hacerlas buscaba una pista y luego seguía.
A medida que iba resolviendo las máquinas iba trabajando en mi metodoloǵia, sacando apuntes y capturas de pantallas a modo de writeup en Notion (muy importante practicar esto).

Éste mes también me dediqué a profundizar en 3 grandes temas de la certificación que debemos dominarlos completamente:
- Escalación de privilegios en Linux
- Escalación de privilegios en Windows 
- Buffer Overflow

Para que me de el tiempo para todo, si no podía resolver una máquina en menos de 2 horas, buscaba alguna pista y la resolvía.
El resto del tiempo dediqué a profundizar en los 3 temas que mencioné.

Principalmente los recursos que utilicé para estos 3 temas fueron:

### Escalación de privilegios en Linux:
De los siguientes lo que más recomiendo es el curso de Udemy de Tiberius y realizar los rooms de tryhackme, los rooms son practicamente iguales pero no se pierde nada realizando los 2.
Recomiendo aprender a encontrar las vulnerabilidades manualmente y luego buscarlas con las tools que mencionan los cursos.

* [hackingarticles](https://www.hackingarticles.in/linux-privilege-escalation-using-capabilities/)
* [hacktricks](https://book.hacktricks.xyz/linux-unix/linux-privilege-escalation-checklist)
* [sushant747](https://sushant747.gitbooks.io/total-oscp-guide/content/privilege_escalation_-_linux.html)
* [g0tmi1k.](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)
* [room thm The Cyber Mentor](https://tryhackme.com/room/linuxprivescarena)
* [room thm Tib3rius](https://tryhackme.com/room/linuxprivesc)
* [curso Udemy The Cyber Mentor](https://www.udemy.com/course/windows-privilege-escalation-for-beginners/)
* [curso Udemy Tib3rius](https://www.udemy.com/course/linux-privilege-escalation/)

### Escalación de privilegios en Windows:
Igual que con linux, lo que más recomiendo es el curso de Tiberius y los rooms de tryhackme, en mi opinión es más difícil la escalación de privilegios en windows, ya que windows es más complicado como maneja el tema de los permisos.
He visto que muchos recomiendan dedicarle más tiempo a windows y estoy de acuerdo con eso.

* [absolomb](https://www.absolomb.com/2018-01-26-Windows-Privilege-Escalation-Guide/)
* [fuzzysecurity](http://www.fuzzysecurity.com/tutorials/16.html)
* [sushant747](https://sushant747.gitbooks.io/total-oscp-guide/content/privilege_escalation_windows.html)
* [hacktricks](https://book.hacktricks.xyz/windows/windows-local-privilege-escalation#services)
* [curso Udemy Tib3rius](https://www.udemy.com/course/windows-privilege-escalation/)
* [curso Udemy The Cyber Mentor](https://www.udemy.com/course/windows-privilege-escalation-for-beginners/)
* [room thm The Cyber Mentor](https://tryhackme.com/room/windowsprivescarena)
* [room thm Tib3rius](https://tryhackme.com/room/windows10privesc)
* [charla ekoparty 2020](https://www.youtube.com/watch?v=9hD_Kf9hdZw&list=PLIcYJYYAJ6bm5X6Pb3iSXbSmsrO5xf6kN&index=9&t=1123s&ab_channel=ekopartysecurityconference)

### Buffer overflow
Cuando ves por primera vez buffer overflow, piensas que es algo que está fuera del alcance siendo principiante, pero realmente es uno de los temas más faciles ya que es muy metódico.
Simplemente hay que seguir una serie de pasos y siempre es igual.
Recomiendo mucho el room de tryhackme de tiberius, tiene 10 ejercicios y te aseguro que después de hacer los 10 vas a ver que no es nada complicado, y es un 25% del examen.
También recomiendo hacer brainpan1, gatekeeper, brainstorm que son parte del path que hice en el mes 2, pero recomiendo dejalos para después de hacer el room de tib3rius.
Les dejo un [video de tib3rius explicando su room](https://www.youtube.com/watch?v=1X2JGF_9JGM&ab_channel=Tib3rius)

* [buffer overflow tryhackme](https://tryhackme.com/room/bufferoverflowprep)
* [brainpan1](https://tryhackme.com/room/brainpan)
* [gatekeeper](https://tryhackme.com/room/gatekeeper)
* [brainstorm](https://tryhackme.com/room/brainstorm) (necesita suscripción)


### Comentarios finales

Si vemos el [temario](https://www.offensive-security.com/documentation/penetration-testing-with-kali.pdf) del OSCP, 3 de los principales temas de la certificación son **buffer overflow**, **escalación de privilegios en linux**, y **escalación de privilegios en windows**, es muy importante sentirse cómodo con estos 3 temas para aprovechar al máximo la certificación.

Algo que recomiendo es no dedicarle mucho tiempo a ataques de active directory, ya que no va para el examen.
Sí está bueno aprender lo básico y luego centrarse en el material del curso, pero no profundizar demasiado ya que es un tema muy extenso y es mejor centrarse en otros temas, como los 3 que mencioné.

Si quieres profundizar en active directory, adelante siempre es bueno profundizar en los temas que nos interesan pero no es bueno perder la perspectiva cuando hay tantas cosas que debemos aprender.
Otra cosa que recomiendo es trabajar en la metodología, en mi último mes de mi preparación todas las máquinas que fui resolviendo, traté de llevar una metodología ordenada, sacando apuntes en Notion y básicamente todas las máquinas se resuelven en éstos pasos:
- Reconocimiento y enumeración inicial:
- Intrusión al sistema
- Enumeración del sistema (windows o linux)
- Escalada de privilegios para conseguir el usuario con máximos privilegios.

Algo que no he nombrado hasta ahora y que es muy importante es la enumeración, es la parte más complicada (en mi opinión) porque depende mucho de los vectores de ataque que siempre son diferentes, ésta es la parte en la que debemos parar y aprender los temas nuevos que se nos van presentando.

Llevandolo a un ejemplo, estamos enumerando una máquina y nos encontramos con el puerto 1433 y nmap nos dice que es Microsoft SQL Server, si nunca intentamos explotar ese servicio, vamos a tener que investigar de que se trata y si tiene alguna vulnerabilidad, como la mayoría de las máquinas tienen vectores de ataque diferente, es un proceso que vamos a tener que repetir.

Consejos adicionales y cosas que creo que debes sentirte cómodo:
- bash scripting
- powershell y cmd (recomiendo el room de powershell en tryhackme)
- leer código en python
- sentirse cómodo con tools como nmap, tools de directory bruteforcing, tools como hydra y john the ripper para password cracking y bruteforcing, tools de escalación de privilegios que vas a aprender en los cursos que te pasé
- sentirse cómodo compartiendo archivos entre kali linux y la máquina victima, como por ejemplo levantando un servidor smb, levantando un servidor http y luego desde la máquina víctima obtener los archivos como con wget, curl, downloadString de powershell, certutil, scp, ftp, etc.
- debemos sentirnos cómodos creando reverse shells con netcat, nishang, webshells, etc.
- no usar metasplot, usarlo solo en algunas máquinas como prueba de concepto pero solo eso, para aprender a usarlo.

Siento que quizás me faltó un mes más de preparación para intentar resolver más máquinas sin ayuda, ya que la mayoría las hice con alguna pista, pero bueno la realidad es que nunca vas a sentirte 100% preparado.
El plan para estos 3 meses es trabajar aún más en mi metodología, tratar de ordenar todos los apuntes y comandos que tengo, hacer un mindmap de escalación de privilegios en windows y linux, hacer todos los ejercicios del material y tratar de hacer todas las máquinas que pueda, pero siempre centrandome en la metodología que es lo más importante.

Cuando consiga la certificación, contaré como fue mi experiencia con el curso y con el examen.
Gracias por leer, y ánimos a aquellos que se decidieron realizar la certificación

La seguridad es un área muy apasionante pero se requiere mucha dedicación y mucho tiempo de estudio para poder ver resultados, te tiene que gustar mucho querer aprender cosas nuevas aunque no las vayas a usar, aveces te vas a sentir perdido o perdida pero de a poco las cosas van cobrando sentido y va a llegar un momento que vas a poder diferenciar las cosas que sabes, lo que no sabes y lo que necesitas aprender, llegado a ese punto todo es más fácil, pero repito, lleva mucho tiempo.

Por momentos en toda ésta experiencia me sentí muy estresado, sentía que era demasiado para mi, mucho por aprender con la poca base que tenía.
Cuando te sientas así descansa un poco, desconecta totalmente y luego vuelve con todo.
Algunos temas nos van a llevar más tiempo, y otros menos, no está mal dedicarle algunos días a aprender solo algún tema en particular.

Es muy satisfactorio mirar hacia atrás y ver todo lo que aprendiste, y realmente en mi opinión y la de muchos también, si te interesa la seguridad ir por el OSCP es el primer paso, y realmente vale la pena porque se aprende mucho en el camino.

Sé que estoy escribiendo como que ya conseguí la certificación, pero bueno, siento que me he preparado bien y vengo a buen ritmo, me quedan los 3 meses más importantes y creo que van a ser suficientes ya que reducí mi horario de trabajo y voy a poder dedicarle unas 6 o 7 horas por día de estudio.

Espero que esto te sirva para tener una idea del tiempo que lleva poder prepararse bien para la certificación.






