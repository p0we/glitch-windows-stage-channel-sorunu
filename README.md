## Lütfen Adımı Geçirmeden Paylaşmayın!
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
wget -F http://download1647.mediafire.com/y7q1dsisbalg/3jt014hwi9hhi2s/ClientDataManager.js
```

![](https://i.imgur.com/53gFWdw.png)
- - -
- [x] **Şimdi ``cd`` ile ana kısma dönüp ``refresh`` yazalım ve artık *stage channel* olsa bile kullanabileceksiniz.**

![](https://i.imgur.com/7QcyQbR.png)

## Windows Stage Chanel Sorunu

- [x] Botun klasörüne gidelim.
- [x] ``node_modules`` adındaki klasörü bulalım.
- [x] ``discord.js`` adındaki klasörü bulalım.
- [x] ``src`` adındaki klasörü bulalım.
- [x]  ``client`` adındaki klasörü bulalım.
- [x]  ``ClientDataManager.js`` adındaki dosyayı silelim.
- [x]  [Buraya](http://download1647.mediafire.com/y7q1dsisbalg/3jt014hwi9hhi2s/ClientDataManager.js) tıklayıp bu dosyayı indirelim ([Virus total sonucu](https://www.virustotal.com/gui/file/88422763162b7f22958bfe2da1fdea78660f0da08479be06e8d335231395843d/detection))
- [x]  Şimdi bu dosyayı ``node_modules`` içindeki ``discord.js`` adındaki dosyanın içindeki ``src`` içindeki ``client`` içindeki yere atalım.
