# ⚙️ Hydrovia: Un Viaje Steampunk para Aprender SQL

📚 Índice
- [🧠 Descripción General](#descripcion-general)
- [🎲 Modo de Juego](#modo-juego)
- [⚙️ Tecnologías Usadas](#tecnologias-usadas)
- [🧪 Funcionalidades](#funcionalidades)
- [🚀 Instalación](#instalacion)
- [🧩 Estructura del Proyecto](#estructura-del-proyecto)
- [📄 Licencia](#licencia)
- [👩‍💻 Autores](#autores)
- [🌐 English Version](#english-version)

---

## 🧠 Descripción General <a name="descripcion-general"></a>
Juego educativo desarrollado en PHP para practicar consultas SQL a través de una historia interactiva ambientada en el universo Steampunk.
Incluye sistema de puntuación, narrativa, niveles de dificultad y gestión de sesiones.


---

**Narrativa del juego**

*Hydrovia es un reino sumido en la desigualdad: los ricos disfrutan de abundancia, 
mientras que los pobres luchan por conseguir lo más básico, como el acceso al agua 
potable. Esta disparidad se debe a un sistema de distribución de recursos 
completamente corrupto, gestionado por un complejo sistema de válvulas y datos que 
los líderes de Hydrovia controlan para mantener el poder. 
Tú como usuario serás Ezekiel, un ingeniero brillante que, cansado de la injusticia, decide tomar el 
control de la situación. Armado con tu conocimiento de sistemas de datos y 
tecnología, te adentrarás en el corazón del sistema para manipular las válvulas y 
redistribuir el agua entre las distintas áreas del reino.*

---

**Características principales:**

- Preguntas tipo test con consultas SQL reales
- Guardado de progreso por sesión
- Sistema de puntuación por vida
- 3 niveles de dificultad: Fácil, Medio, Difícil
- Estilo visual steampunk personalizado
- Imágenes y tipografías integradas
- Historia estilo steampunk ilustrada capítulo a capítulo

---

## 🎲 Modo de juego  <a name="modo-juego"></a>
**Inicio de sesión y registro:**
- Accede con tu cuenta o crea una nueva para guardar tu progreso.

**Opciones de partida:**
- Nueva Partida: Comienza desde el capítulo 0.
- Continuar: Retoma desde donde lo dejaste gracias al sistema de sesiones.

**Selección de dificultad:**
- Fácil: pierdes 10 puntos por error
- Medio: 20 puntos
- Difícil: 30 puntos

*Todos comienzan con 100 puntos de vida.*

**Mecánica:**
- Lee la narrativa del capítulo.
- Elige una de las tres consultas SQL disponibles.
- Si aciertas, avanzas. Si fallas, pierdes vida.
- 
  *Puedes consultar la base de datos de ejemplo si necesitas ayuda.*

**Final del juego:**
- Si llegas al capítulo 12 con vida, ¡salvas Hydrovia!
- Si tus puntos llegan a 0, tendrás que empezar de nuevo.

---

 ## ⚙️ Tecnologías Usadas <a name="tecnologias-usadas"></a>
<div align="center"> <img src="https://img.shields.io/badge/PHP-8.3-blue?style=for-the-badge&logo=php" /> <img src="https://img.shields.io/badge/MySQL-DB-orange?style=for-the-badge&logo=mysql" /> <img src="https://img.shields.io/badge/HTML5-CSS3-yellow?style=for-the-badge&logo=html5" /> <img src="https://img.shields.io/badge/JavaScript-ES6-green?style=for-the-badge&logo=javascript" /> </div> <br>



- **PHP** (conexión mediante PDO)
- **MySQL** como base de datos
- **HTML5**
- **CSS3**
- **JavaScript**

---


## 🧪 Funcionalidades <a name="funcionalidades"></a>

- Registro e inicio de sesión de jugadores
- Avance narrativo por capítulos
- Múltiples opciones por pregunta con feedback
- Selección de dificultad con penalización de vida
- Guardado automático de progreso
- Validación de consultas SQL correctas e incorrectas
- Diseño adaptable a dispositivos

---

## 🚀 Instalación <a name="instalacion"></a>
🧱 Clonar el repositorio

```
git clone https://github.com/tu-usuario/hydrovia.git
cd hydrov
```

### 🗃 Importar base de datos
- Abre tu gestor de bases de datos (phpMyAdmin, DBeaver, etc.)
- Importa el archivo DB_reto.sql incluido en la carpeta raíz


### ⚙️ Configurar conexión
Abre `modelo/conexionPDO.php/` y edita las variables según tu entorno:



```
$host = 'localhost';
$database = 'bd_reto';
$user = 'root';
$password = 'tu_contraseña';
```
Guarda los cambios.

### 🚨 Iniciar servidor
Si usas XAMPP o similar, coloca la carpeta en htdocs y accede desde:

### Visita el proyecto http://localhost/Hydrovia

---

## 🧩 Estructura del Proyecto <a name="estructura-del-proyecto"></a>
- `controlador/` - Lógica del juego y control de sesiones
- `database/` - Conexión a la base de datos y funciones SQL
- `public/` - Interfaz de usuario, estilos, imágenes y fuentes
- `index.php/` - Página principal y acceso al juego
- `DB_reto.sql/` - Archivo SQL con la base de datos del juego


---

## 📄 Licencia  <a name="licencia"></a>
Proyecto realizado con fines educativos dentro del módulo de Desarrollo Web en Entorno Servidor.
No cuenta con fines comerciales ni distribución oficial.

2025 

---

## 👥 Autores  <a name="autores"></a>
Proyecto desarrollado por:
Michael Alberto, William Ruiz y Carla Lozano

[GitHub](https://github.com/carlaloz24)   |   [LinkedIn](https://www.linkedin.com/in/carlalozano/)





---

## 🌐 English Version <a name="english-version"></a>
# ⚙️ Hydrovia: Un Viaje Steampunk para Aprender SQL

---

## 🧠 General Description <a name="general-description"></a>
Educational game developed in PHP to practice SQL queries through an interactive story set in a Steampunk universe.
It includes a scoring system, narrative progression, difficulty levels, and session management.

---

**Game Narrative**

*Hydrovia is a kingdom steeped in inequality: the wealthy revel in abundance, while the poor struggle to access basic necessities like clean water. This disparity stems from a thoroughly corrupt resource distribution system, managed by a complex network of valves and data controlled by Hydrovia’s leaders to maintain their power. As the user, you will embody Ezekiel, a brilliant engineer fed up with injustice, determined to take matters into your own hands. Armed with your expertise in data systems and technology, you will delve into the core of the system to manipulate the valves and redistribute water across the kingdom’s regions.*

---

**Key Features:**

- Multiple-choice questions with real SQL queries
- Progress saving via sessions
- Life-based scoring system
- 3 difficulty levels: Easy, Medium, Hard
- Custom Steampunk visual style
- Integrated images and typography
- Chapter-by-chapter illustrated Steampunk storyline

---

## 🎲 Gameplay  <a name="modo-juego"></a>
**Login and Registration:**
- Log in with your account or create a new one to save your progress.

**Game Options:**
- New Game: Start from Chapter 0.ítulo 0.
- Continue: Resume from your last saved point using the session system

**Difficulty Selection:**
- Easy: Lose 10 points per mistake
- Medium: 20 points
- Hard: 30 points

*All players begin with 100 life points.*

**Mechanics:**
- Read the chapter’s narrative.
- Choose one of three available SQL queries.
- If correct, you progress. If incorrect, you lose life points.
- 
*You can consult the sample database for assistance if needed.*

**Game Conclusion:**
- Reach Chapter 12 with life points remaining to save Hydrovia!
- If your points drop to 0, you’ll need to start over.

---

 ## ⚙️ Technologies Used <a name="tecnologias-usadas"></a>
<div align="center"> <img src="https://img.shields.io/badge/PHP-8.3-blue?style=for-the-badge&logo=php" /> <img src="https://img.shields.io/badge/MySQL-DB-orange?style=for-the-badge&logo=mysql" /> <img src="https://img.shields.io/badge/HTML5-CSS3-yellow?style=for-the-badge&logo=html5" /> <img src="https://img.shields.io/badge/JavaScript-ES6-green?style=for-the-badge&logo=javascript" /> </div> <br>



- **PHP** (connected via PDO)
- **MySQL** as the database
- **HTML5**
- **CSS3**
- **JavaScript**

---


## 🧪 Features <a name="funcionalidades"></a>

- Player registration and login
- Narrative progression through chapters
- Multiple-choice questions with feedback
- Difficulty selection with life penalties
- Automatic progress saving
- Validation of correct and incorrect SQL queries
- Responsive design for multiple devices

---

## 🚀 Installation <a name="instalacion"></a>
🧱 Clone the repository

```
git clone https://github.com/tu-usuario/hydrovia.git
cd hydrov
```

### 🗃 Import the database
- Open your database management tool (phpMyAdmin, DBeaver, etc.)
- Import the DB_reto.sql file included in the root folder


### ⚙️ Configure the connection
Open modelo/conexionPDO.php/ and edit the variables according to your environment:



```
$host = 'localhost';
$database = 'bd_reto';
$user = 'root';
$password = 'your_password'';
```
Guarda los cambios.

### 🚨 v
If using XAMPP or similar, place the folder in htdocs and access it from:

### Visit the project at http://localhost/Hydrovia

---

## 🧩 v <a name="estructura-del-proyecto"></a>
- `controlador/` - Game logic and session management
- `database/` - Database connection and SQL functions
- `public/` - User interface, styles, images, and fonts
- `index.php/` - Main page and game access
- `DB_reto.sql/` - SQL file with the game’s database


---

## 📄 License  <a name="licencia"></a>
This project was created for educational purposes as part of the Server-Side Web Development module.
It is not intended for commercial use or official distribution.

2025 

---

## 👥 Authors  <a name="autores"></a>
Project developed by:
Michael Alberto, William Ruiz and Carla Lozano

[GitHub](https://github.com/carlaloz24)   |   [LinkedIn](https://www.linkedin.com/in/carlalozano/)
</details>



