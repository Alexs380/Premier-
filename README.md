
// server.js
const express = require('express');
const app = express();
const port = 3000;

// Ruta principal que muestra "Hello World"
app.get('/', (req, res) => {
  res.send('Hello World');
});

// Iniciar el servidor
app.listen(port, () => {
  console.log(`Servidor corriendo en http://localhost:${port}`);
});
