# Pizarra Táctica ⚽

App web para anotar y visualizar eventos de un partido de fútbol en tiempo real sobre un campo dividido en cuadrantes.

## 🚀 Demo en GitHub Pages

Esta app es 100% **standalone** (un único archivo HTML) — no necesita servidor, base de datos ni backend. Todos los datos se guardan en el navegador (localStorage).

## ✨ Funcionalidades

- ✅ **Gestión multi-partido** con persistencia local
- ✅ **Campo de fútbol táctico** con cuadrícula configurable (2×2 a 12×12)
- ✅ **15 tipos de evento**: Pérdida, Recuperación, Remate, Tiro a puerta, Gol, Falta, Pase ok/fallado, Intercepción, Centro, Tarjetas, Cambio...
- ✅ **2 equipos** con colores personalizables
- ✅ **Jugadores con dorsales** (1-99) y posición (POR/DEF/MED/DEL)
- ✅ **Cronómetro con mitades 1H/2H** y tiempo añadido (45+2', 90+3'...)
- ✅ **Heat-map** con filtro por equipo
- ✅ **Timeline cronológica** con badges 1H/2H y divisores entre mitades
- ✅ **Estadísticas** con totales, desglose por tipo y top jugadores
- ✅ **Deshacer** el último evento
- ✅ **Exportar CSV** (Excel) y **JSON** (compartir entre dispositivos)
- ✅ **Importar JSON** para recrear un partido en otro dispositivo
- ✅ **Mobile-first** — optimizada para uso táctil en el campo

## 📦 Cómo desplegar en GitHub Pages

### Opción A: Subir el archivo por la web (más fácil)

1. Ve a tu repo: https://github.com/tpinilla81-sudo/ANOTAOLSEN
2. Click en **"Add file" → "Upload files"**
3. Arrastra el archivo `index.html` de esta carpeta
4. Escribe un mensaje de commit (ej: "Deploy Pizarra Táctica")
5. Click en **"Commit changes"**
6. Ve a **Settings → Pages**
7. En **"Source"** selecciona **"Deploy from a branch"**
8. En **"Branch"** selecciona **`main`** y carpeta **`/ (root)`**
9. Click en **"Save"**
10. Espera 1-2 minutos y entra en: `https://tpinilla81-sudo.github.io/ANOTAOLSEN/`

### Opción B: Por línea de comandos

```bash
# Clona tu repo
git clone https://github.com/tpinilla81-sudo/ANOTAOLSEN.git
cd ANOTAOLSEN

# Copia el archivo index.html aquí
cp /ruta/descarga/index.html .

# Sube los cambios
git add index.html
git commit -m "Deploy Pizarra Táctica"
git push origin main

# Activa GitHub Pages: Settings → Pages → Branch: main / root → Save
```

URL pública resultante: **https://tpinilla81-sudo.github.io/ANOTAOLSEN/**

## 🎯 Cómo usar la app

1. **Crea un partido**: botón "+ Nuevo" → equipos, colores, cuadrícula
2. **(Opcional) Añade jugadores**: botón 👥 → dorsal + nombre + posición
3. **Inicia el cronómetro**: botón ▶️
4. **Selecciona equipo + tipo de evento + jugador**
5. **Toca una zona del campo** para registrar el evento
6. **Cambia de mitad** con el botón "2ª →"
7. **Cambia a vista Heat-map** con el botón 🔥
8. **Exporta CSV/JSON** con el botón ↗

## 📱 Capturas

En la carpeta `download/` tienes capturas reales de la app en móvil.

## 🛠️ Tecnología

- HTML5 + CSS3 + JavaScript vanilla (sin frameworks)
- Tailwind-inspired CSS variables
- localStorage para persistencia
- 100% client-side — sin dependencias externas

## 📄 Licencia

MIT — libre uso, modificación y distribución.
