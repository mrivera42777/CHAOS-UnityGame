# 📘 Guía de Organización del Proyecto Unity *C.H.A.O.S.*

Este documento explica cómo vamos a nombrar **archivos, carpetas y ramas** para que todos trabajemos de manera ordenada.  
La idea es que, aunque nunca hayas usado GitHub o Unity en equipo, sepas **qué nombre ponerle a las cosas** y **cómo organizarte**.

---

## 1. Reglas básicas de nombres
- Usar **inglés** siempre.  
- No usar acentos, eñes ni símbolos raros.  
- No dejar **espacios** → usa `-` o `_`.  
- Nombres **claros y cortos**.  

---

## 2. Archivos en Unity
- **Scripts (.cs):** `PlayerController.cs`, `HealthSystem.cs`.  
- **Prefabs:** `EnemyGoblin.prefab`, `BossHospital.prefab`.  
- **Escenas (.unity):** `MenuMain.unity`, `LevelHospital01.unity`.  
- **Animaciones (.anim):** `idle.anim`, `attackHeavy.anim`.  
- **Sprites:** `enemyGoblin_idle.png`, `ui_buttonStart.png`.  

---

## 3. Carpetas principales
```
Assets/
 ├── Art/        (Sprites, animaciones, materiales)
 ├── Audio/      (Música y efectos de sonido)
 ├── Prefabs/    (Objetos listos para usar)
 ├── Scenes/     (Niveles y menús)
 ├── Scripts/    (Código C#)
 └── UI/         (Interfaz de usuario)
```

---

## 4. Ramas de trabajo en GitHub
- `main` → versión estable (no tocar).  
- `develop` → donde juntamos el trabajo de todos.  
- `feature/...` → nuevas funciones. Ej: `feature/player-movement`.  
- `bugfix/...` → arreglos de errores. Ej: `bugfix/menu-buttons`.  
- `experiment/...` → pruebas temporales.  

---

## 5. Commits (mensajes al guardar cambios)
Ejemplos buenos:  
- `add player movement`  
- `fix enemy collision`  
- `update main menu UI`  

Ejemplos malos:  
- `cosas nuevas`  
- `arreglos`  
- `final final ahora sí`  

---

## 6. Reglas rápidas de equipo
✅ Antes de empezar → haz **pull**.  
✅ Usa tu **propia rama** (no `main`).  
✅ Nombres simples y claros.  
✅ Commits pequeños.  
✅ Si dudas → pregunta antes de inventar.  
