## Glitch/Linux Stage Channel Sorunu
- [x] **Terminali açın.**

![](https://i.imgur.com/ArKO9Eq.png)
- - -
- [x] **Modülün dosyasına vereceğim kod ile gidelim.**
```console
cd node_modules/discord.js/src/client
```

![](https://i.imgur.com/x9KMhlg.png)
- - -
- [x] **Şimdi ise vereceğim kod ile ClientDataManager.js dosyasını silelim. (``ls`` ile silinip silinmediğini kontrol edebilirsiniz.)**
```console
rm -rf ClientDataManager.js
```

![](https://i.imgur.com/4bxhDIY.png)
- - -
- [x] **Şimdiyse sorunsuz ClientDataManager.js kodumuzu indirelim. (``-F`` kodun htmlye dönüşmesini önler)**
```console
wget -F https://download1647.mediafire.com/q18h3z0mjlpg/3jt014hwi9hhi2s/ClientDataManager.js
```

![](https://i.imgur.com/53gFWdw.png)
- - -
- [x] **Şimdi ``cd`` ile ana kısma dönüp ``refresh`` yazalım ve artık *stage channel* olsa bile kullanabileceksiniz.**

![](https://i.imgur.com/7QcyQbR.png)

## Windows Stage Chanel Sorunu
