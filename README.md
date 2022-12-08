# SapCase
1 - Öncelikle Drive üzerinden bize iletilen dosyayı indirdim ve takip etmem gereken adımların olduğu siteyi açtım.
2 - SAP Machine 11'i kurduktan sonra, komut istemi üzerinden "hybris/bin/platform" dosya yolunu girdikten sonra, "setantenv.bat" komutunu
    enterladım.
3 - Daha sonra "ant clean all" komutunu girdikten sonra defalarca hata aldım. Repository içindeki antcleansonrasi.png sadece birisi.
4 - Aldığım bu hatayı çözmek için öncelikle Java version 11'i yükledim ancak aldığım hatayı çözmeye yetmedi.
5 - Ardından dili İngilizce'ye çevirmek istedim fakat Windows sürümüm Single Language olduğu için değiştiremedim bunu çözmek için Pro 
Lisans satın aldım.
6 - Windows Görüntüleme Dilini ingilizceye çevirdikten sonra "ant clean all" komutu sonrası hata almadım ve Komut İstemi üzerinde Build 
Succesfull dönütünü aldım.
7 - Bu adımdan sonra komut isteminden recips kurulumunu yapmayı denedim. Dosya yolunu komut istemine girdikten sonra,
"install.bat -r b2c_acc_plus -A local_property:initialpassword.admin=your_password" komutunu girdim. Ardından 
"install.bat -r b2c_acc_plus initialize -A local_property:initialpassword.admin=your_password" komutunu girdikten sonra bu aşamanın
tamamlanması 2 saat sürdü ve en son "install.bat -r b2c_acc_plus start" komutunu girip bir saat kadar bekledikten sonra ilerleme olmadı.
8 - https://localhost:9002/ üzerinden Hybris yönetim paneline eriştim ancak programı kuramadığım için herhangi bir geliştirme yapadım.
