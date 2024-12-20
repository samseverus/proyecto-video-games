﻿# proyecto-video-games

Zombie Survival Game
¡Bienvenido al Zombie Survival Game! Un juego de disparos en 2D donde el jugador lucha contra hordas de zombies, recoge recursos y lucha por sobrevivir el mayor tiempo posible. El juego cuenta con características como un menú de inicio, un sistema de pausas, y pantallas de Game Over. ¡Sobrevive cada oleada y alcanza la mayor puntuación posible!
Características
•	Menú de Inicio: Inicia el juego presionando la tecla Enter.
•	Pantalla de Game Over: Vuelve a jugar o sal del juego tras morir.
•	Menú de Pausa: Pausa el juego en cualquier momento con la tecla P y reanuda, reinicia o sale del juego.
•	Oleadas de Enemigos: Los zombies vienen en diferentes tipos (normales, rápidos, fuertes) y aumentan con cada ola.
•	Recolección de Recursos: Encuentra paquetes de salud y munición aleatorios en el mapa.
•	Sistema de Puntuación y Progreso: El jugador obtiene puntuación por matar zombies y puede ganar experiencia.
•	Efectos de Sonido: Incluye sonidos de disparos, zombies y explosiones para mejorar la inmersión.
Requisitos
Para ejecutar el juego necesitarás tener instalado Python 3 y las siguientes dependencias:
•	pygame: Para crear la interfaz gráfica del juego.
Puedes instalar las dependencias usando pip:
pip install pygame

Cómo jugar
Iniciar el juego: En la pantalla de inicio, presiona Enter para comenzar a jugar.
Control del jugador:
Mover: Usa las teclas de flecha Arriba, Abajo, Izquierda y Derecha para mover al jugador.
Disparar: Presiona la tecla Espacio para disparar.
Ataque especial: Presiona E para usar un ataque especial.
Pausar: Presiona P para pausar el juego y acceder al menú de pausa.
Reiniciar: En la pantalla de Game Over o en el menú de pausa, presiona R para reiniciar el juego.
Salir: Presiona Esc en cualquier momento para salir del juego.
Supervivencia: Intenta sobrevivir el mayor tiempo posible, eliminando zombies y recolectando paquetes de salud y munición.
Controles
Movimiento: Flechas de dirección (Arriba, Abajo, Izquierda, Derecha)
Disparar: Espacio
Pausar: P
Ataque especial: E
Reiniciar: R
Salir: Esc

Instalación y ejecución
Clona este repositorio:

bash
Copiar código
git clone https://github.com/tu_usuario/zombie-survival-game.git
Accede a la carpeta del proyecto:

bash
Copiar código
cd zombie-survival-game
Ejecuta el juego:

bash
Copiar código
python main.py
Esto abrirá una ventana de Pygame donde podrás comenzar a jugar.

Estructura del Proyecto
El proyecto está organizado de la siguiente manera:

bash
Copiar código
zombie-survival-game/
├── assets/                # Imágenes y sonidos del juego
│   ├── background.jpg
│   ├── pause_background.jpg
│   ├── zombie_hit_sound.wav
│   └── ...
├── main.py                # Archivo principal del juego
├── player.py              # Código relacionado con el jugador
├── zombie.py              # Código relacionado con los zombies
├── health_pack.py         # Código relacionado con los paquetes de salud
├── ammo_pack.py           # Código relacionado con los paquetes de munición
└── ...
Contribuciones
Si deseas contribuir al proyecto, ¡estás más que bienvenido! Puedes hacer un fork del repositorio, realizar tus cambios y enviar un pull request.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

