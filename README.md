# copia-proyecto



<img width="430" height="975" alt="image" src="https://github.com/user-attachments/assets/53a4ed62-d304-41ae-8a34-381b9eb296ca" />




![Versión](https://img.shields.io/badge/versión-1.0.5-blue)  
![Estado](https://img.shields.io/badge/estado-en%20prototipo-yellow)  

> Breve descripción del proyecto: ¿qué hace, para quién está hecho y por qué es importante?
La solución que se propuso es la realización de una aplicación que permita el reconocimiento estructural de los puntos del cuerpo a través de la cámara del dispositivo móvil durante la realización física de la mecánica de tiro en el baloncesto, este reconocimiento permitirá que la app analice si la posición corporal de la persona es correcta a la hora de lanzar pero si no lo es la aplicación le dará tips y recomendaciones al usuario de como mejorar el movimiento mecánico del tiro en el baloncesto. Siguiendo las recomendaciones a través de la practica el usuario gradualmente mejorara su porcentaje de acierto en los tiros.
---

## 🎯 Objetivo del Proyecto

Explica brevemente el propósito general:

- La mala ejecución de la técnica al tirar puede generar malos porcentajes de acierto y posibilidad de lesión 
La mecánica de tiro en baloncesto se refiere al conjunto de movimientos y técnicas que un jugador utiliza para lanzar el balón hacia el aro de manera precisa y eficiente. Es un aspecto clave para tener un buen porcentaje de acierto.
Esto nos llevó a preguntarnos ¿De qué manera se puede corregir automáticamente la postura del brazo para que la mecánica de tiro sea más efectiva y de esa manera aumentar el porcentaje de acierto en tiros de los jugadores y evitar posibles lesiones? 

-Diseñar y desarrollar un sistema tecnológico que permita a los jugadores de baloncesto mejorar su mecánica de tiro mediante la corrección automática de la postura del brazo y la retroalimentación en tiempo real. Este sistema estará basado en sensores electromiográficos y conectividad con una aplicación móvil para monitorear y evaluar la ejecución de cada lanzamiento, ayudando a optimizar la precisión del tiro y prevenir posibles lesiones.

-Proponemos una forma economica y sencilla de usar para practicar y mejorar la mecanica de tiro de los basketbolistas , sin la necesidad de maquinas super caras o de un entrenador personal, nosotros damos la oportunidad de mejorar mostrando tips y la forma de ejecucion de la mecanica de tiro y tambien permite al usuario entender con mayor facilidad en que se esta equivocando al tirar , mostrando especificamente la fase que tiene que mejorar y como puede hacer una mejor acción 

---

## 🧪 Prototipo

Primer prototipo
Una idea inicial de donde se intentaria realizar una lectura muscular para con esa lectura generar una serie de promedios estadisticos para corregir la fuerza ejercida en el brazo durante la mecanica de tiro, una idea rechazada debido a la complejidad de los calculos del sensor y la incomodidad del dispositivo en el usuario por lo que se descarto este prototipo y se inicio la construccion del modelo de IA

<img width="439" height="500" alt="image" src="https://github.com/user-attachments/assets/ae088fb3-5a34-455a-ad15-ff029bb74f62" />


>Circuito del prototipo

Segundo prototipo
En esta etapa iniciamos la creacion de la aplicación en app inventor, un entorno de programacion diseñado para este tipo de actividades, en el avance del proyecto se tiene unas pantallas principales conectadas a partir de botones donde se puede navegar por la app, ademas de la inclusion y deteccion de la camara del celular en la pantalla “Practica” esto nos permitira conectar la aplicación con el modelo de uso Mediapipe para que se genere la captura de movimiento del cuerpo desde la camara del dispositivo y asi como paso siguiente crear los calculos de las lecturas de posicion para asi estipular las clases de cada una de las etapas de la mecanica del tiro y realizar las correcciones /n

 
<img width="459" height="359" alt="image" src="https://github.com/user-attachments/assets/cb5d5aea-2994-4fae-8fce-4aad64aaeed2" />



>Boceto de camara de analisis

<img width="459" height="359" alt="image" src="https://github.com/user-attachments/assets/c68cba5d-caa3-4816-8882-ca15f2edc67b" />



>Pantalla de carga

<img width="465" height="362" alt="image" src="https://github.com/user-attachments/assets/8dd08701-d85e-4419-aadb-63586c7dcbb9" />



>Pantalla de inicio


### 📸 Capturas



<img width="886" height="490" alt="image" src="https://github.com/user-attachments/assets/eb97c853-0642-44a1-ac5b-634ab9e28c4d" />



>Pantalla principal

<img width="886" height="476" alt="image" src="https://github.com/user-attachments/assets/36b2394d-dc09-4ea5-96e0-e4befb1746c0" />



>Muestra del codigo



---

## 🧰 Tecnologías Utilizadas


 Para el desarrollo del proyecto los recursos que necesitaremos serán pocos, pero esenciales, primeramente, necesitamos una placa de Arduino que contendrá toda la programación luego necesitaremos un sensor de señales EMC o electrodo que captan señales eléctricas a partir del movimiento muscular, un sensor bluetooth para conectar el Arduino al celular y por último el desarrollo de una aplicación en Android estudio con Java.
Fase de desarrollo:
 En esta fase vamos a implementar la creación de la aplicación en Android estudio que conectará el dispositivo móvil a una placa de Arduino que a su vez recibirá señales EMC de unos electrodos.
Fase de pruebas:
 Realización de pruebas con los electrodos y la aplicación viendo cuales son las zonas más eficientes de usar y tomar información de los músculos mientras se ejecuta la mecánica de tiro. 
Fase de entrega:
 Presentación de la manga conectada a la placa Arduino y una aplicación hecha en Android estudio 
Producto esperado
Una aplicación conectada a una manga que permitirá monitorear y corregir la mecánica de tiro en baloncesto para el usuario, está conectada por una placa Arduino, un conjunto de electrodos y un sensor bluetooth.


---

## ⚙️ Instalación

### Requisitos previos

- Tener un celular con camara  
- App instalada
- Navegador moderno
-Balon de baloncesto
  
