# 🎁 "Guardé algo para ti" — mini web de cumpleaños

Una página interactiva de un solo archivo: tu hermana la abre, toca la pantalla y van apareciendo mensajes.
Incluye una tarjeta secreta que se abre **manteniendo presionado el corazón**, y un final con confeti, carta y firma.

---

## 1. Cómo verla

Doble clic en `index.html`. Se abre en el navegador (funciona igual en el celular).

- Toca (o haz clic) en cualquier parte para pasar de mensaje.
- La tarjeta 5 se abre manteniendo presionado el corazón ~1,2 segundos.
- Arriba a la derecha hay un botón para activar/silenciar el sonido.

---

## 2. Cómo personalizarla (2 minutos)

Abre `index.html` con el Bloc de notas (clic derecho → Abrir con → Bloc de notas).
Busca el bloque que empieza con **`var CONFIG = {`** (está como en la mitad del archivo).
Solo cambia lo que está entre comillas:

| Campo | Qué es |
|---|---|
| `nombre` | Su nombre. Aparece en la pantalla final. Si lo dejas vacío, no aparece. |
| `mensajes` | La lista de mensajes, uno por línea, separados por coma. Agrega o quita los que quieras. |
| `sostener.texto` | Lo que se lee antes de mantener presionado. |
| `sostener.secreto` | Lo que se revela al mantener presionado. |
| `carta` | La carta del final. Usa `\n\n` para separar párrafos. |
| `firma` | La firma del final. Ej: "Con todo mi amor, tu hermano". |
| `foto` | Opcional: pon `"foto.jpg"` y guarda la foto en esta misma carpeta. |

⚠️ No borres las comillas, las comas ni las llaves. Solo cambia el texto de adentro.
Guarda el archivo y recarga la página (F5).

---

## 3. Cómo tener un enlace para enviárselo

### Opción A — Netlify Drop (la más rápida, gratis, sin instalar nada)
1. Entra a **https://app.netlify.com/drop**
2. Arrastra **esta carpeta completa** a la página.
3. En segundos te da un enlace tipo `https://algo-aleatorio.netlify.app`.
4. (Opcional) Crea cuenta gratis para conservarlo y cambiarle el nombre por algo bonito.

### Opción B — Vercel
1. **https://vercel.com/new** → arrastra la carpeta → Deploy.

### Opción C — GitHub Pages
1. Crea un repositorio público nuevo y sube `index.html`.
2. Settings → Pages → Source: `main` / root → Save.
3. Queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

---

## 4. Consejos

- **Pruébala en tu celular antes de enviarla**: el enlace se disfruta mucho más en el teléfono.
- Envíale el enlace por WhatsApp con un mensaje corto: *"No lo abras todavía… ábrelo cuando estés sola 😌"*.
- Si le pones foto, que sea una de las dos juntos: multiplica el efecto.
- Todo funciona sin internet **si abres el archivo directamente**; con enlace necesita conexión (las tipografías bonitas vienen de Google Fonts, y si no cargan, se ve igual con una letra parecida).

---

Hecho con cariño. Si quieres cambiar textos, agregar más mensajes o una canción de fondo, se puede. 💛
