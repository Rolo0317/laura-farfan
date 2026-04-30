# 🌺 Laura Farfán — Sitio Autobiográfico

Sitio web personal con estilo colombiano, desplegado en GitHub Pages.

## 🔗 Enlace del sitio

**https://rolo0317.github.io/laura-farfan/**

---

## 📋 Procedimiento realizado

### 1. Renombrar imágenes

Las 12 imágenes de la carpeta `imagenes/` fueron renombradas de:

| Original | Nuevo |
|----------|-------|
| WhatsApp Image 2026-04-30 at 3.17.38 PM.jpeg | foto-00-cumpleanos-familia.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (1).jpeg | foto-01-parque-acuatico.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (2).jpeg | foto-02-scooter-libertad.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (3).jpeg | foto-03-amigos-reunion.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (4).jpeg | foto-04-familia-noche.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (5).jpeg | foto-05-futbol-sala-bogota.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (6).jpeg | foto-06-graduacion.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (7).jpeg | foto-07-amigas-selfie.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (8).jpeg | foto-08-bebe-infancia.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (9).jpeg | foto-09-mascota-perro.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (10).jpeg | foto-10-sombrero-vueltiao.jpeg |
| WhatsApp Image 2026-04-30 at 3.17.38 PM (11).jpeg | foto-11-moto-tvs.jpeg |

### 2. Actualizar index.html

- Rutas de imágenes actualizadas a `imagenes/foto-XX-*.jpeg`
- Array de fotos en JavaScript con captions en español
- Estilo colombiano agregado:
  - **Barra tricolor** (amarillo, azul, rojo) en la parte superior
  - **Colores de la bandera** como variables CSS
  - **Footer con mensaje**: "🇨🇴 Hecha en Colombia · Bogotá D.C."

### 3. Git y GitHub Pages

```bash
# Inicializar repositorio
git init
git config user.name "Rolo0317"
git config user.email "rolo0317@gmail.com"

# Commit inicial
git add .
git commit -m "feat: sitio autobiografía Laura Farfán con estilo colombiano"

# Configurar remoto
git remote add origin https://github.com/Rolo0317/laura-farfan.git
git branch -M main

# Desplegar
git pull origin main --rebase
git push -u origin main
```

---

## 🎨 Características del diseño

- **Tema oscuro** con acentos de la bandera colombiana
- **Barra tricolor** animada en la parte superior
- **Galería responsiva** con tarjetas de fotos
- **Captions descriptivos** en español
- **Footer con identidad colombiana** (Bogotá D.C.)

---

## 📁 Estructura del proyecto

```
Laura_farfan/
├── index.html          # Sitio principal
├── imagenes/
│   ├── foto-00-cumpleanos-familia.jpeg
│   ├── foto-01-parque-acuatico.jpeg
│   ├── foto-02-scooter-libertad.jpeg
│   ├── foto-03-amigos-reunion.jpeg
│   ├── foto-04-familia-noche.jpeg
│   ├── foto-05-futbol-sala-bogota.jpeg
│   ├── foto-06-graduacion.jpeg
│   ├── foto-07-amigas-selfie.jpeg
│   ├── foto-08-bebe-infancia.jpeg
│   ├── foto-09-mascota-perro.jpeg
│   ├── foto-10-sombrero-vueltiao.jpeg
│   └── foto-11-moto-tvs.jpeg
└── README.md           # Este archivo
```

---

## 🛠️ Tecnologías usadas

- HTML5
- CSS3 (variables, grid, flexbox)
- JavaScript vanilla
- Git + GitHub Pages

---

*Sitio creado el 30 de abril de 2026 · Bogotá D.C., Colombia 🇨🇴*