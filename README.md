# Coach de Feedback (página externa gratis con Gemini)

public/index.html (interfaz) + api/chat.js (servidor que llama a Gemini) + vercel.json.

1. Key gratis en https://aistudio.google.com/apikey (sin tarjeta).
2. Sube la carpeta a GitHub e impórtala en https://vercel.com/new
3. Antes de Deploy agrega la variable GEMINI_API_KEY con tu key.
4. Opcional: GEMINI_MODEL para cambiar de modelo (por defecto gemini-flash-latest).
