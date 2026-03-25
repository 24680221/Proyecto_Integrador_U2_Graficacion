# Proyecto_Integrador_U2_Graficacion

# Introduccion
En esta práctica se realizó una animación tradicional en 2D utilizando la herramienta Grease Pencil en Blender.
El objetivo fue crear un walk cycle de un personaje tipo caricatura (una criatura pequeña cargando una roca), aplicando principios básicos de animación como peso, ritmo y continuidad.

link de video de referencia: https://youtu.be/0myBDB1vuq0?si=5genaRDW11b-HM0b
# Preparación del entorno

Primero se cambió el espacio de trabajo a 2D Animation, donde se trabaja directamente con Grease Pencil.

Posteriormente:

- Se eliminó el objeto inicial (stroke por defecto)
- Se agregó un nuevo objeto:
- Grease Pencil en blanco
- Se renombró como: “Personaje”

<img width="412" height="71" alt="image" src="https://github.com/user-attachments/assets/6b8826e4-4277-4de6-94a7-5eaafa58ec92" />

# Creación de materiales

Se configuraron materiales para representar al personaje:

- Material 01 (Trazo):
Color oscuro (negro) para contornos
- Material 02 (Cuerpo):
Negro (criatura)
- Material 03 (Roca):
Café oscuro
- Material 04 (Ojos):
Blanco
- Material 05 (Detalles):
Cafe claro (sombras o acentos)

<img width="312" height="159" alt="image" src="https://github.com/user-attachments/assets/dd59de14-4aa7-4366-a5c1-12b0935770c7" />

Se separaron en capas:

- Trazo (líneas)
- Relleno (colores)

<img width="315" height="211" alt="image" src="https://github.com/user-attachments/assets/46062bad-3525-41fd-a96a-223cc88c1354" />

# Imagen de referencia

Se importó una imagen guía con las poses del personaje:

6 poses de caminata
4 poses de aplastamiento (extra)

Se ajustó:

- Escala
- Posición
- Opacidad (~0.5)

Esto permitió dibujar encima sin perder visibilidad.

<img width="1536" height="1024" alt="El esfuerzo de un pequeño ser" src="https://github.com/user-attachments/assets/77d4ed49-e937-4ff2-a0d9-ddb2ffeb6bd0" />

# Organización de la animación

Se configuró la línea de tiempo:

Inicio: Frame 1
Fin: Frame 26
Total: 26 frames

<img width="921" height="211" alt="image" src="https://github.com/user-attachments/assets/6d6f97db-5233-40bf-8ba1-9aaa38edcecd" />

Cada pose se colocó cada 3 frames:

Pose	Frame
1	      1
2	      4
3	      7
4	      10
5	      13
6	      16
7	      19
8	      22

# Creación de las poses (Walk Cycle)

Se dibujaron manualmente las poses usando:

- Arcos
- Curvas
- Líneas poligonales

como se dibujo el personaje:

Primero, se colocó una imagen de referencia con las diferentes poses del personaje, a la cual se le redujo la opacidad para poder dibujar encima sin que estorbara la visibilidad. Después, se organizaron dos capas principales: una para el trazo (líneas) y otra para el relleno (colores).

El dibujo comenzó trazando el contorno del personaje utilizando herramientas como líneas, curvas y arcos, cuidando seguir la forma de la referencia. Posteriormente, se procedió a rellenar cada parte del personaje, aplicando los colores correspondientes: negro para el cuerpo, café para la roca, blanco para los ojos y detalles en cafe claro.

Este proceso se repitió para cada una de las poses del ciclo de animación, asegurando que todas mantuvieran proporciones similares para lograr una animación fluida.

Pose 1 – Contacto: El personaje pisa el suelo con una pata al frente.

Pose 2 – Bajada: El cuerpo baja por el peso de la roca.

Pose 3 – Paso: Las patas se cruzan en el centro.

Pose 4 – Empuje: La pata trasera impulsa el movimiento.

Pose 5 – Contacto invertido: Se repite el ciclo con la otra pata.

Pose 6 – Empuje final: Se completa el ciclo.

- Secuencia adicional: Aplastamiento

Después del ciclo de caminata, se agregó una animación secundaria donde:

- El personaje comienza a hundirse
- La roca baja progresivamente
- El cuerpo se comprime
- Solo quedan visibles los ojos

<img width="1536" height="1024" alt="El esfuerzo de un pequeño ser" src="https://github.com/user-attachments/assets/7644ded2-5c29-4d08-b9b2-c1def4402059" />

# Principios de animación aplicados

Durante la práctica se aplicaron:

- Peso: la roca afecta el movimiento
- Anticipación: antes de cada paso
- Exageración: en la compresión del cuerpo
- Timing: uso de 3 frames por pose
- Overlap: ligero retraso entre cuerpo y roca

# Organización final

Se alinearon todas las poses:

- Usando modo edición (A para seleccionar)
- Moviendo con G en el eje X
- Centrando respecto a la cámara

Se utilizó:

- Onion Skin (piel de cebolla)
Para visualizar frames anteriores y siguientes.

<img width="593" height="508" alt="Captura de pantalla 2026-03-24 210735" src="https://github.com/user-attachments/assets/ccbfbd58-626b-4cde-a68b-094767cc4a4b" />

<img width="481" height="537" alt="Captura de pantalla 2026-03-24 210730" src="https://github.com/user-attachments/assets/da9bcff0-c37d-4b6a-a992-22ed22003f23" />

# Resultados

Se obtuvo una animación fluida donde:

- El personaje camina con dificultad
- Se percibe el peso de la roca
- La secuencia final añade un efecto cómico
<img width="494" height="521" alt="Captura de pantalla 2026-03-24 210824" src="https://github.com/user-attachments/assets/3534ded5-7a13-4eb3-8701-a67bc9bd3822" />
<img width="487" height="507" alt="Captura de pantalla 2026-03-24 210829" src="https://github.com/user-attachments/assets/c8262a66-7c96-4b34-89a3-7a9e31725e2b" />
<img width="586" height="527" alt="Captura de pantalla 2026-03-24 210835" src="https://github.com/user-attachments/assets/beb84178-14e3-4e11-a2f6-11abbb1cb3b9" />
<img width="589" height="502" alt="Captura de pantalla 2026-03-24 210840" src="https://github.com/user-attachments/assets/90e1894f-dc57-4a1f-a3de-2dd6f48c5152" />
<img width="675" height="495" alt="Captura de pantalla 2026-03-24 210846" src="https://github.com/user-attachments/assets/926f7b84-3768-4983-b18e-672df82b5884" />
<img width="552" height="513" alt="Captura de pantalla 2026-03-24 210850" src="https://github.com/user-attachments/assets/c0b28f65-bf48-4551-95b2-a3c9ae70f1a7" />
<img width="653" height="539" alt="Captura de pantalla 2026-03-24 210855" src="https://github.com/user-attachments/assets/be06aca8-517a-490e-89b5-18268e095cbc" />
<img width="659" height="504" alt="Captura de pantalla 2026-03-24 210901" src="https://github.com/user-attachments/assets/4e4ef295-2289-4213-aa4d-ef4096c7a054" />
<img width="534" height="369" alt="Captura de pantalla 2026-03-24 210905" src="https://github.com/user-attachments/assets/0a818cef-445c-493f-8b11-83dfa4840f70" />
<img width="418" height="307" alt="Captura de pantalla 2026-03-24 214539" src="https://github.com/user-attachments/assets/5b8f3922-492e-43b6-aeb6-037791fc1bf0" />
<img width="393" height="261" alt="Captura de pantalla 2026-03-24 214545" src="https://github.com/user-attachments/assets/45a8018c-b437-4c56-818f-4afea567ef09" />

# Conclusión

El uso de Grease Pencil en Blender permite crear animaciones 2D de forma eficiente, combinando herramientas de dibujo y animación en un mismo entorno.
Esta práctica permitió comprender: Cómo construir un ciclo de caminata, La importancia del timing,Cómo agregar personalidad mediante la animación
