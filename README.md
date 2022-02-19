# 24-7Bot
Código de video para mantener el bot 24/7

Vídeo: 

Código usado en el video:
````js
const express = require('express')
const server = express();
 
server.all('/', (req, res) => {
    res.send('Bot 24/7);
});
  
server.listen(3000, () => {
    console.log('Servidor Listo.');
 });````
 
 
