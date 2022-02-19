# 24-7Bot
Código de video para mantener el bot 24/7

# Vídeo: [Ver](https://video.com).
# Discord: [Ir](https://dsc.gg/tecnobros).

No olvides darle like y suscribirte ;)


<details><summary>Código usado en el video:</summary>
<p>

#### Código:

````js
const express = require('express')
const server = express();
 
server.all('/', (req, res) => {
    res.send('Bot 24/7);
});
  
server.listen(3000, () => {
    console.log('Servidor Listo.');
 });
