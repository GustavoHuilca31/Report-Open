# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.
Para la realizar el To-be Scenario Mapping el equipo determinó como se vería el flujo de trabajo luego de que nuestra solución haya sido implementada para cada segmento objetivo. El objetivo del presente artefacto es comparar y
mejorar los aspectos negativos identificados en el As-is Scenario.

**Segmento escritor:**

<img src="https://github.com/Open-Source-SW54-Group-3-ArtCollab/Report/blob/develop/assets/images/to-be-scenario-mapping/To-Be%20Scenario%20Mapping-escritor.jpg?raw=true" alt="Segmento escritor">

**Segmento ilstrador:**

<img src="https://github.com/Open-Source-SW54-Group-3-ArtCollab/Report/blob/develop/assets/images/to-be-scenario-mapping/To-Be%20Scenario%20Mapping-ilustrador.jpg?raw=true" alt="Segmento ilstrador">

**Segmento lector:**

<img src="https://github.com/Open-Source-SW54-Group-3-ArtCollab/Report/blob/develop/assets/images/to-be-scenario-mapping/To-Be%20Scenario%20Mapping-lector.jpg?raw=true" alt="Segmento lector">

Enlace de Miro: https://miro.com/app/board/uXjVKXvjT-4=/?share_link_id=428179149390

## 3.2. User Stories
<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 21%" />
<col style="width: 39%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>
<tr class="even">
<td>E1-US01</td>
<td>Barra de navegación en la Landing Page</td>
<td><p><strong>Como</strong> Usuario</p>
<p><strong>quiero</strong> visualizar una pagina</p>
<p><strong>para</strong> saber acerca de los servicios de la
aplicación</p></td>
<td><p>Escenario 1: Header</p>
<p>Dado que el usuario se encuentre en la landing page</p>
<p>Cuando se encuentra con la barra de navegación</p>
<p>Entonces podrá visualizar diversas secciones y botones.</p>
<p>Escenario 2: Navegación</p>
<p>Dado que el usuario esta en la landing page</p>
<p>Cuando aprete cualquier sección o Botón</p>
<p>Entonces va a ser redirigido a esta</p></td>
<td>1</td>
</tr>
<tr class="odd">
<td>E1-US02</td>
<td>Visualización de las redes sociales mediante footer</td>
<td><p><strong>Como</strong> Usuario</p>
<p><strong>quiero</strong> visualizar la sección de footer de la
pagina</p>
<p><strong>para</strong> encontrar los links de las redes
sociales</p></td>
<td><p>Escenario 1: Footer</p>
<p>Dado que el usuario se encuentre en la landing page</p>
<p>Cuando se encuentre con el footer</p>
<p>Entonces podrá visualizar diversas redes sociales del startup</p>
<p>Escenario 2: Redes</p>
<p>Dado que el usuario se encuentre en la landing page</p>
<p>Cuando aprete cualquier red social del footer</p>
<p>Entonces se le redirigirá a la red social escogida mostrando el
perfil de la startup</p></td>
<td>1</td>
</tr>
<tr class="even">
<td>E1-US03</td>
<td>Sección de Conócenos</td>
<td><p><strong>Como</strong> Usuario</p>
<p><strong>quiero</strong> conocer los servicios que ofrece la
aplicación</p>
<p><strong>para</strong> saber las características que ofrece</p></td>
<td><p>Escenario 1: Conocenos</p>
<p>Dado que el usuario se encuentra en la landing page</p>
<p>Cuando se encuentre en la sección Conócenos</p>
<p>Entonces podrá visualizar los diversos libros en trending y los
mejores ilustradores</p></td>
<td>1</td>
</tr>
<tr class="odd">
<td>E1-US04</td>
<td>Sección Colabora</td>
<td><p><strong>Como</strong> Usuario</p>
<p><strong>quiero</strong> conocer las formas de colaborar con otros
usuarios que me ofrece la aplicación</p>
<p><strong>para</strong> facilitarme el contacto con otros
artistas</p></td>
<td><p>Escenario 1: Colabora</p>
<p>Dado que el usuario se encuentra en la landing page</p>
<p>Cuando se encuentre en la sección Colabora</p>
<p>Entonces podrá visualizar como un escritor y ilustrador colaboran</p>
<p>Escenario 2: Descubre</p>
<p>Dado que el usuario se encuentre en la landing page</p>
<p>Cuando se encuentre en la sección</p>
<p>Colabora y le de clic a “descubrir como”</p>
<p>Entonces se le redirigirá a una pagina con toda la
informacion</p></td>
<td>1</td>
</tr>
<tr class="even">
<td>E1-US05</td>
<td>Sección Hero</td>
<td><p><strong>Como</strong> Usuario</p>
<p><strong>quiero</strong> visualizar una sección hero donde describa
brevemente la misión de la startup</p>
<p><strong>para</strong> tener una idea de lo que ofrece la
aplicación</p></td>
<td><p>Escenario 1: Hero</p>
<p>Dado que el usuario se encuentra en la landing page</p>
<p>Cuando se encuentre en la sección hero</p>
<p>Entonces podrá visualizar la página principal donde se le invita a
pertenecer a la comunidad</p>
<p>Escenario 2: Comunidad</p>
<p>Dado que el usuario se encuentra en la landing page</p>
<p>Cuando se encuentre en la sección hero y le dé clic a “Únete”</p>
<p>Entonces se le redirigirá a la sección de registro</p></td>
<td>1</td>
</tr>
<tr class="odd">
<td>E2-US06</td>
<td>Asignación de Rol</td>
<td><p><strong>Como</strong> lector</p>
<p><strong>quiero</strong> poder asignarle un rol</p>
<p><strong>para</strong> poder visualizar la página</p></td>
<td><p>Escenario 1: Ingreso a la página luego del inicio de sesión</p>
<p>Dado que el usuario se encuentra logeado en la página </p>
<p>Cuando se desplace le aparecerá una ventana para que elija un rol
(Escritor, Ilustrador, Lector).</p>
<p>Entonces el usuario elije el rol</p>
<p>Escenario 2: Actualización de Datos</p>
<p>Dado que el usuario escogió el rol</p>
<p>Cuando se le asigne el rol le pedirá una actualización de Datos </p>
<p>Entonces el usuario llenará los datos que le piden Dependiendo el Rol
que haya escogido</p>
<p>Escenario 3: Actualización de página y herramientas</p>
<p>Dado que el usuario terminó la actualización de datos</p>
<p>Cuando se desplace se le dirigiera a la página principal</p>
<p>Entonces se le mostrará la página principal actualizada dependiendo
al rol que haya escogido con nuevas herramientas.</p></td>
<td>2</td>
</tr>
<tr class="even">
<td>E2-US07</td>
<td>Configuración de Perfil del Usuario</td>
<td><p><strong>Como</strong> lector, artista o escritor</p>
<p><strong>quiero</strong> configurar mi perfil</p>
<p><strong>para</strong> satisfacer mis gustos</p></td>
<td><p>Escenario 1: Ingresar al perfil</p>
<p>Dado que el usuario se encuentra en la página principal</p>
<p>Cuando le de click en su perfil</p>
<p>Entonces se le abrirá su perfil</p>
<p>Escenario 2: Configuración de perfil</p>
<p>Dado que se encuentra en su perfil</p>
<p>Cuando le de click en Configuración</p>
<p>Entonces podrá configurar su perfil en aspectos estética, finanzas y
portafolio</p></td>
<td>2</td>
</tr>
<tr class="odd">
<td>E3-US08</td>
<td>Sube tus libros</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> una plataforma</p>
<p><strong>para</strong> subir mis libros</p></td>
<td><p>Escenario 1: Hoja de texto</p>
<p>Dado que el escritor se encuentra en la página principal</p>
<p>Cuando le dé clic en “crear”</p>
<p>Entonces se le abrirá una página donde podrá subir su obra </p>
<p>Escenario 2:</p>
<p>Dado que el escritor terminó la obra</p>
<p>Cuando le dé clic en publicar</p>
<p>Entonces la obra será publicada y se verá en su portafolio</p></td>
<td>3</td>
</tr>
<tr class="even">
<td>E3-US09</td>
<td>Colaboración con Ilustradores</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> que mis obras sean ilustradas</p>
<p><strong>para</strong> mejorarlas</p></td>
<td><p>Escenario 1: Ilustra</p>
<p>Dado que me encuentro en la pestaña de mis obras</p>
<p>Cuando le dé clic en alguna de mis obras e Ilustrar</p>
<p>Entonces se me abrirá una pestaña nueva donde habrá una sección de
ilustradores</p>
<p>Escenario 2: Escoger</p>
<p>Dado que me encuentre algún ilustrador que me guste</p>
<p>Cuando entre a su perfil y le clic en colaborar</p>
<p>Entonces se me abrirá un chat con el ilustrador</p>
<p>Escenario 3: Acuerdos</p>
<p>Dado que ambos llegaron a un acuerdo </p>
<p>Cuando le den clic al botón acuerdo en el chat</p>
<p>Entonces elegirás que obra poder darle acceso</p></td>
<td>3</td>
</tr>
<tr class="odd">
<td>E4-US10</td>
<td>Destaca tus libros</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> destacar mis libros</p>
<p><strong>para</strong> tener más vistas</p></td>
<td><p>Escenario 1: Sistema monetario</p>
<p>Dado que el escritor se encuentra en su perfil</p>
<p>Cuando le dé clic en monedas</p>
<p>Entonces se le abrirá un recuadro de cuantas monedas desea
comprar</p>
<p>Escenario 2: Ingreso Bancario</p>
<p>Dado que se encuentra en la parte de compra</p>
<p>Cuando ingrese sus datos bancarios y lo confirme</p>
<p>Entonces le llegara un correo de recibo y se depositaran las
monedas</p>
<p>Escenario 3: Destaca tus obras</p>
<p>Dado que el usuario se encuentra en la pestaña de sus obras</p>
<p>Cuando le clic en una obra específica y en destacar </p>
<p>Entonces se le mostrará un monto y por cuánto tiempo se destacó la
obra</p></td>
<td>4</td>
</tr>
<tr class="even">
<td>E4-US11</td>
<td>Reparto por Ingresos publicitarios</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> generar ingresos</p>
<p><strong>para</strong> mejorar mis libros</p></td>
<td><p>Escenario 1:  Ingreso al programa de recompensas</p>
<p>Dado que el escritor se encuentra en su perfil</p>
<p>Cuando le dé clic al programa de ingresos</p>
<p>Entonces se le descargara una forma a llenar</p>
<p>Escenario 2: Recopilación de Datos</p>
<p>Dado que el escritor lleno los datos que le piden</p>
<p>Cuando le dé clic en enviar formulario</p>
<p>Entonces se le mostrará una recopilación de requisitos previos
(+1.000 seguidores y +50.000 vistas)</p>
<p>Escenario 3: Aceptación de Solicitud</p>
<p>Dado que el escritor recibió un correo de aceptación</p>
<p>Cuando le dé clic en aceptar</p>
<p>Entonces se le mostrará un mensaje de bienvenida donde recibirá un
50% de ingreso neto por los anuncios mostrados cuando leen la
obra</p></td>
<td>4</td>
</tr>
<tr class="odd">
<td>E5-US12</td>
<td>Diversos géneros literarios</td>
<td><p><strong>Como</strong> lector</p>
<p><strong>quiero</strong> tener una gran cantidad de géneros literarios
a mi disposición</p>
<p><strong>para</strong> tener una gran variedad de opciones a elegir
para mis lecturas</p></td>
<td><p>Escenario 1: Opción géneros</p>
<p>Dado que me encuentro en la página principal</p>
<p>Cuando le dé clic a ver catalogo</p>
<p>Entonces me redirigirá al catálogo literario de la página</p>
<p>Escenario 2: Filtración</p>
<p>Dado que me encuentro en el catálogo literario de la página</p>
<p>Cuando le dé clic a filtrar</p>
<p>Entonces lo podré filtrar por género, número de páginas, popularidad,
etc.</p></td>
<td>5</td>
</tr>
<tr class="even">
<td>E5-US13</td>
<td>Desbloqueo de Capítulos</td>
<td><p><strong>Como</strong> lector</p>
<p><strong>quiero</strong> tener acceso al contenido exclusivo de la
plataforma</p>
<p><strong>para</strong> contar con más capítulos a mi
disposición</p></td>
<td><p>Escenario 1: Finanzas</p>
<p>Dado que el usuario se encuentra en la página principal </p>
<p>Cuando le de clic al apartado de monedas</p>
<p>Entonces se le mostrará el valor de las monedas</p>
<p>Escenario 2: Monedas</p>
<p> Dado que el usuario se encuentra en el apartado de monedas</p>
<p>Cuando elija cuántas quiere y elija el modo de pago</p>
<p>Entonces se le redirige a una pestaña de pago de su elección</p>
<p>Escenario 3: Pago</p>
<p>Dado que el usuario pago y se le depositó las monedas </p>
<p>Cuando vaya al libro a desbloquear los nuevos capítulos cuando le dé
clic en desbloquear</p>
<p>Entonces se le desbloqueara el capítulo</p></td>
<td>5</td>
</tr>
<tr class="odd">
<td>E5-US14</td>
<td>Dejar Comentarios</td>
<td><p><strong>Como</strong> lector, escritor e ilustrador</p>
<p><strong>quiero</strong> poder comentar las obras</p>
<p><strong>para</strong> ayudar a otros usuarios brindándoles un
feedback</p></td>
<td><p>Escenario 1: Escoge el libro</p>
<p>Dado que el usuario se encuentra en la página principal</p>
<p>Cuando le de click en su perfil</p>
<p>Entonces podrá visualizar sus libros recién leídos</p>
<p>Escenario 2: Reseña</p>
<p>Dado que el usuario se encuentra en el libro seleccionado</p>
<p>Cuando le dé clic en el apartado de “dejar comentarios”</p>
<p>Entonces podrá escribir su comentario y publicarlo</p></td>
<td>5</td>
</tr>
<tr class="even">
<td>E6-US15</td>
<td>Ingreso por las ilustraciones</td>
<td><p><strong>Como</strong> ilustrador</p>
<p><strong>quiero</strong> contar con una monetización por mis
ilustraciones</p>
<p><strong>para</strong> poder percibir ingresos dentro de la
aplicación</p></td>
<td><p>Escenario 1: Acuerdo Mutuo</p>
<p>Dado que el ilustrador fue contactado por el escritor</p>
<p>Cuando ambas partes lleguen a un acuerdo se dará a una
colaboración</p>
<p>Entonces cuando se termine el trabajo acordaron un pago de manera
externa</p>
<p>Escenario 2: Fecha de Pago</p>
<p>Dado que el ilustrador terminó sus ilustraciones pendientes</p>
<p>Cuando le comenté a su colaborador (Escritor)</p>
<p>Entonces se le pagará por un medio externo</p></td>
<td>6</td>
</tr>
<tr class="odd">
<td>E6-US16</td>
<td>Flexibilidad al ilustrar</td>
<td><p><strong>Como</strong> ilustrador</p>
<p><strong>quiero</strong> tener flexibilidad creativa a la hora de
dibujar</p>
<p><strong>para</strong> tener un mejor rendimiento</p></td>
<td><p>Escenario 1: Añade Flexibilidad</p>
<p>Dado que el ilustrador se encuentra en la página principal</p>
<p>Cuando le dé clic a perfil</p>
<p>Entonces podrá visualizar su perfil</p>
<p>Escenario 2: perfil flexible</p>
<p>Dado que el ilustrador configuración de perfil</p>
<p>Cuando le dé clic en editar su perfil</p>
<p>Entonces podrá elegir editar sus preferencias por la flexibilidad
creativa </p>
<p>Escenario 3: Creatividad</p>
<p>Dado que los escritores revisen tu perfil</p>
<p>Cuando les den clic a preferencias</p>
<p>Entonces podrán visualizar tu preferencia por la flexibilidad
creativa</p></td>
<td>6</td>
</tr>
</tbody>
</table>
<hr>

## 3.3. Impact Mapping.
<img src="https://github.com/Open-Source-SW54-Group-3-ArtCollab/Report/blob/develop/assets/images/Impactmap1O.png?raw=true" alt="Impact Map 1" style="margin-bottom: 5px;" width="1000"/>
<img src="https://github.com/Open-Source-SW54-Group-3-ArtCollab/Report/blob/develop/assets/images/Impactmap2O.png?raw=true" alt="Impact Map 2" style="margin-bottom: 5px;" width="1000"/>
<img src="https://github.com/Open-Source-SW54-Group-3-ArtCollab/Report/blob/develop/assets/images/Impactmap3O.png?raw=true" alt="Impact Map 3" style="margin-bottom: 5px;" width="1000"/>
<hr>

## 3.4. Product Backlog.
https://trello.com/invite/b/XGFz58Qm/ATTId8b089f48c027b128a0df36e9f15df3c662ADF56/mi-tablero-de-trello
<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 18%" />
<col style="width: 28%" />
<col style="width: 14%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th>#Orden</th>
<th>User Story ID</th>
<th>Titulo</th>
<th>Descripcion</th>
<th>Prioridad</th>
<th>Story Points</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>US01</td>
<td>Barra de navegación en la Landing Page</td>
<td><p><strong>Como</strong> escritor o lector</p>
<p><strong>quiero</strong> visualizar una pagina</p>
<p><strong>para</strong> saber acerca de los servicios de la
aplicación</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>2</td>
<td>US02</td>
<td>Visualización de las redes sociales mediante footer</td>
<td><p><strong>Como</strong> lector, escritor o ilustrador</p>
<p><strong>quiero</strong> visualizar la sección de footer de la
pagina</p>
<p><strong>para</strong> encontrar los links de las redes
sociales</p></td>
<td>Baja</td>
<td>1</td>
</tr>
<tr class="odd">
<td>3</td>
<td>US03</td>
<td>Sección de Conócenos</td>
<td><p><strong>Como</strong> lector, escritor o ilustrador</p>
<p><strong>quiero</strong> conocer los servicios que ofrece la
aplicación</p>
<p><strong>para</strong> saber las características que ofrece</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>4</td>
<td>US04</td>
<td>Sección Colabora</td>
<td><p><strong>Como</strong> escritor o ilustrador</p>
<p><strong>quiero</strong> conocer las formas de colaborar con otros
usuarios que me ofrece la aplicación</p>
<p><strong>para</strong> facilitarme el contacto con otros
artistas</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>5</td>
<td>US05</td>
<td>Sección Hero</td>
<td><p><strong>Como</strong> lector, escritor o ilustrador</p>
<p><strong>quiero</strong> visualizar una sección hero donde describa
brevemente la misión del startup</p>
<p><strong>para</strong> tener una idea de lo que ofrece la
aplicación</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>6</td>
<td>US06</td>
<td>Asignación de Rol</td>
<td><p><strong>Como</strong> lector</p>
<p><strong>quiero</strong> poder asignarle un rol</p>
<p><strong>para</strong> poder visualizar la página</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>7</td>
<td>US07</td>
<td>Configuración de Perfil de Usuario</td>
<td><p><strong>Como</strong> lector, artista o escritor</p>
<p><strong>quiero</strong> configurar mi perfil</p>
<p><strong>para</strong> satisfacer mis gustos</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>8</td>
<td>US08</td>
<td>Sube tus libros</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> una plataforma</p>
<p><strong>para</strong> subir mis libros</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>9</td>
<td>US09</td>
<td>Colaboración con Ilustradores</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> que mis obras sean ilustradas</p>
<p><strong>para</strong> mejorarlas</p></td>
<td>Media</td>
<td>2</td>
</tr>
<tr class="even">
<td>10</td>
<td>US10</td>
<td>Destaca tus libros</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> destacar mis libros</p>
<p><strong>para</strong> tener más vistas</p></td>
<td>Media</td>
<td>2</td>
</tr>
<tr class="odd">
<td>11</td>
<td>US11</td>
<td>Reparto por Ingresos publicitarios</td>
<td><p><strong>Como</strong> escritor</p>
<p><strong>quiero</strong> generar ingresos</p>
<p><strong>para</strong> mejorar mis libros</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>12</td>
<td>US12</td>
<td>Diversos géneros literarios</td>
<td><p><strong>Como</strong> lector</p>
<p><strong>quiero</strong> tener una gran cantidad de géneros literarios
a mi disposición</p>
<p><strong>para</strong> tener una gran variedad de opciones a elegir
para mis lecturas</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>13</td>
<td>US13</td>
<td>Desbloqueo de Capítulos</td>
<td><p><strong>Como</strong> lector</p>
<p><strong>quiero</strong> tener acceso al contenido exclusivo de la
plataforma</p>
<p><strong>para</strong> contar con más capítulos a mi
disposición</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>14</td>
<td>US14</td>
<td>Dejar Comentarios</td>
<td><p><strong>Como</strong> lector, escritor e ilustrador</p>
<p><strong>quiero</strong> poder comentar las obras</p>
<p><strong>para</strong> ayudar a otros usuarios brindándoles un
feedback</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>15</td>
<td>US15</td>
<td>Ingreso por las ilustraciones</td>
<td><p><strong>Como</strong> ilustrador</p>
<p><strong>quiero</strong> contar con una monetización por mis
ilustraciones</p>
<p><strong>para</strong> poder percibir ingresos dentro de la
aplicación</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>16</td>
<td>US16</td>
<td>Flexibilidad al ilustrar</td>
<td><p><strong>Como</strong> ilustrador</p>
<p><strong>quiero</strong> tener flexibilidad creativa a la hora de
dibujar</p>
<p><strong>para</strong> tener un mejor rendimiento</p></td>
<td>Alta</td>
<td>3</td>
</tr>
</tbody>
</table>
