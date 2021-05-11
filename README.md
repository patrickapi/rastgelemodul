# Rastgele 
&nbsp;

Bu Modül Sayesinde Rastgele Şeylere Erişebilirsiniz. Yakında Çok Çok Daha Fazlası!


```npm install rastgelemodul```

```js
//modülümüzü tanımlıyoruz
const rastgele = require('rastgelemodul');

//rastgele espri methodu
rastgele.espri().then(espri => {
  console.log(espri)
})

//discord.js örnek komut

client.on("message", msg => {
if(msg.content === "espriyap") {
const rastgele = require('rastgelemodul')
rastgele.espri().then(espri => {
msg.channel.send(`Buyur Esprin :`+  espri)
})}})

rastgele.atasözü() // rastgele ata sözü verir
rastgele.emoji() //rastgele emoji verir
rastgele.film() // rastgele film/dizi önerir
rastgele.renk() //rastgele renk verir
```
