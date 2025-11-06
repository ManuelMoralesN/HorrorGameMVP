# HorrorGameMVP

## Descripción  
Prototipo inicial de un **juego de terror en primera persona**, inspirado en *Devour*, *El Conjuro* y *Asylum*.  
El enfoque está en la **IA enemiga** y su interacción con el jugador mediante una **linterna**.

---

## Características  
- **IA con Behavior Tree:** patrulla, investiga sonidos y persigue al jugador al detectarlo.  
- **Sistema de percepción:** detección por vista y oído.  
- **Reacción al daño:** cambia de comportamiento al ser afectado por la linterna.  
- **Mapa de prueba:** entorno oscuro y claustrofóbico basado en *Asylum*.  

---

## Behavior Tree 
- **ROOT:** nodo principal con referencia al Blackboard.  
- **Selector principal:** decide entre daño, patrulla/investigación o persecución.  
- **Investigación:** se mueve a una ubicación de sonido, espera y limpia la posición.  
- **Patrulla:** recorre puntos cuando no hay estímulos.  
- **Persecución:** sigue al jugador o va a su última posición conocida.  

---
