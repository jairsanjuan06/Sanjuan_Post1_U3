# Perfil Personal con CSS3 — Post-Contenido 1 · Unidad 3

**Nombre del estudiante:** Jair Sanjuan 
**Programa:** Ingeniería de Sistemas  
**Asignatura:** Programación Web — UDES 2026  

---

## Descripción del proyecto

Página web de perfil personal construida como laboratorio de la **Unidad 3: CSS3 Básico**. El proyecto integra los siguientes conceptos de CSS3:

- **Selectores avanzados:** selectores de clase, combinadores de hijo directo (`>`), pseudo-clases (`:hover`, `:focus`, `:active`) y pseudo-elementos (`::placeholder`).
- **Box Model con `box-sizing: border-box`:** aplicado globalmente mediante reset CSS para garantizar que padding y border no desborden el ancho declarado.
- **Posicionamiento CSS:** `position: fixed` en el header de navegación y `position: absolute` para el badge superpuesto sobre el avatar.
- **Custom Properties (Variables CSS):** paleta de colores, tipografía, sombras y radios definidos en `:root` y reutilizados en toda la hoja de estilos.
- **Formulario accesible:** reset de estilos de inputs, focus ring visible, y estados interactivos en el botón de envío.
- **Nomenclatura BEM:** usada en los modificadores de las tarjetas de habilidades (`skill-item--html`, `skill-item--css`, etc.).

### Estructura de archivos

```
apellido-post1-u3/
├── index.html          ← Estructura HTML5 semántica
├── css/
│   └── estilos.css     ← Estilos CSS3 organizados por secciones
├── img/
│   └── perfil.jpg      ← Foto de perfil (o imagen placeholder)
└── README.md           ← Este archivo
```

---

## Cómo abrir el proyecto localmente

### Requisitos previos
- [VS Code](https://code.visualstudio.com/) con la extensión **Live Server** instalada.
- [Git](https://git-scm.com/) para clonar el repositorio.
- Navegador **Google Chrome** (recomendado para usar DevTools con F12).

### Pasos

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/jairsanjuan06/Sanjuan-Post1-u3.git
   ```

2. **Abrir la carpeta en VS Code:**
   ```bash
   cd apellido-post1-u3
   code .
   ```

3. **Iniciar Live Server:**  
   Hacer clic derecho sobre `index.html` en el explorador de archivos de VS Code y seleccionar **"Open with Live Server"**.  
   El navegador abrirá automáticamente `http://127.0.0.1:5500/index.html`.

4. **Inspeccionar el Box Model (opcional):**  
   Presionar `F12` en Chrome → pestaña **Elements** → seleccionar cualquier elemento → pestaña **Computed** para ver el Box Model con `box-sizing: border-box` activo.

---

## Funcionalidades implementadas

| Funcionalidad | Descripción |
|---|---|
| Header fijo | Permanece visible durante el scroll con `position: fixed` y `z-index: 100` |
| Badge sobre avatar | Posicionado con `position: absolute` dentro de `.avatar-wrapper` (`position: relative`) |
| Tarjetas de habilidades | Colores diferenciados con modificadores BEM y efecto `translateY` en hover |
| Formulario accesible | Focus ring azul translúcido en campos de texto y email |
| Botón con estados | Cambia de color en `:hover` y se comprime levemente en `:active` |
| Variables CSS | Paleta de colores centralizada en `:root` para fácil mantenimiento |

---

## Captura de pantalla

![alt text](../Sanjuan_Post1_U3/src/img/Captura.png)
---


© 2026 — Jair Sanjuan · Universidad de Santander (UDES)
