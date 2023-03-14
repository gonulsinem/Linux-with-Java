# Linux with Java

## Ubuntu Kurulumu  :woman_technologist:

![image](https://user-images.githubusercontent.com/82284108/147258482-657657a5-9545-44c5-be74-a3e14a57d9d2.png)

>"Yeni"ye tıklayıp Ubuntu kurulumuna başlayabiliriz.

![image](https://user-images.githubusercontent.com/82284108/147258910-8e968845-b941-44da-ad2f-7bd18e92725a.png)
> Seçenekleri ile ileri basabiliriz.

![image](https://user-images.githubusercontent.com/82284108/147259208-785cc6bd-4182-4d25-be60-122b83ddfdc6.png)
>Bellek boyutunu 8192 MB, yani 8GB olarak ayarladım.

![image](https://user-images.githubusercontent.com/82284108/147259466-4a1fdfcd-8e2e-442f-9c49-cdae9a059e2f.png)
> Yeni oluşturacağım için "Şimdi sanal bir sabit disk oluştur" seçeneğiyle devam ediyorum.

![image](https://user-images.githubusercontent.com/82284108/147260018-02a6250a-fcde-4802-800c-28321aee97fa.png)
![image](https://user-images.githubusercontent.com/82284108/147260079-b85cff50-27eb-420c-983e-8ab359b62429.png)

![image](https://user-images.githubusercontent.com/82284108/147260252-2eb572af-d030-4c77-ab4c-12aeb0839564.png)
> Dosya yeri ve boyutu için 20 GB yer ayırıyorum.

![image](https://user-images.githubusercontent.com/82284108/147260433-003c9c3c-ffe2-48c7-9a5d-e346bf1c14bb.png)
> Sanal bilgisayar oluştu. Daha sonra ayarlaraını düzenliyorum.

![image](https://user-images.githubusercontent.com/82284108/147260662-e7b083cb-64e9-4819-9b39-c67271a28c8f.png)
> Sanal optik disk seçip daha önceden indirdiğmiz ubuntu dosyasını yüklüyorum.
![image](https://user-images.githubusercontent.com/82284108/147260906-74d65108-7d2d-4f6e-9582-4bc8ba947ebc.png)


![image](https://user-images.githubusercontent.com/82284108/147261214-88f102c1-e2dd-4517-b4d8-5a7cb5404d44.png)
>Ekran ayarlarını bu şekilde ayarlıyorum.



![image](https://user-images.githubusercontent.com/82284108/147261395-6da6c365-8615-41f8-82ce-242d1fe702ee.png)
> İşlemciyi 2 olarak ayarlıyorum. Anabellek'i 8 GB olarak ayarladım.
> Ayarlamalardan sonra sanal bilgisara tıklayıp "Başlat" ile bilgisayarı başlatıyoruz.

![image](https://user-images.githubusercontent.com/82284108/147262123-7866b5d3-e332-4c97-b49b-0277c1d926ee.png)
> Install Ubuntu seçeneğiyle devam ediyorum.

![image](https://user-images.githubusercontent.com/82284108/147262332-1c9a0dee-9cf8-4842-a387-250ff18406f0.png)
> Klavyeyi Türkçe olarak ayarladım.

![image](https://user-images.githubusercontent.com/82284108/147262399-c8b29e6f-cd3a-4486-97cd-250561a9094b.png)
![image](https://user-images.githubusercontent.com/82284108/147262499-df2b3647-9bf4-439c-9f40-db55db6568df.png)
![image](https://user-images.githubusercontent.com/82284108/147262570-e2a83a77-1f1d-4c75-9f59-cfb5f05719d6.png)


>Açtıktan sonra
```
apt-get update
```


![image](https://user-images.githubusercontent.com/82284108/147266267-d036332f-d1c0-426b-a860-419b0ded8c06.png)
> Daha sonra ```apt-get upgrade``` komutunu çalıştırdım. Sanal Makinenin kurulumunu yaptıktan sonra JAVA kurulumuna geçebiliriz.

> Terminalde ``` java --version ``` komutunu çalıştırarak Java'nın yüklü olup olmadığını kontrol ediyoruz.

![image](https://user-images.githubusercontent.com/82284108/147277693-8b6e1492-602c-4443-b626-43a025e8f1e2.png)
> Java'nın yüklü olmadığı görüldü.

>Oracle'dan JDK indiriyoruz.
>
![image](https://user-images.githubusercontent.com/82284108/147278005-66a58a60-a4ff-4684-a233-18f7bbc5d46d.png)

![image](https://user-images.githubusercontent.com/82284108/147278308-88b4c3da-c333-4916-a042-fc477b3edc25.png)
> Burada indirilen jdk dosyası ne ise onun ismini kullanıyoruz.

![image](https://user-images.githubusercontent.com/82284108/147278692-be9284a1-4e8e-4811-b679-fd9a1134041a.png)



```sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-17/bin/java 1```
kurulan JDK dosyasının ismini girmek önemlidir.
```sudo update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk-17/bin/javac 1```



``` java --version ``` ve ``` javac --version ``` ile kurulan Java versiyonunu öğreniyoruz.

![image](https://user-images.githubusercontent.com/82284108/147279136-d8427572-6d1c-4bca-891a-da7d2834f9d2.png)

>Kurulumlardan sonra yol ayarlarını yapıp ilk kodu yazabiliriz.

![image](https://user-images.githubusercontent.com/82284108/147279797-7439fa70-3a37-4581-81dc-76f5c3478ad1.png)

![image](https://user-images.githubusercontent.com/82284108/147279965-c9fa03a3-df3f-4384-88c6-3ad5ef8a6869.png)

![image](https://user-images.githubusercontent.com/82284108/147280210-37611bca-10c5-4f2d-b14d-0b3b5ced9ac8.png)

> Ubuntu üzerinde JAVA kodunu çalıştırdık. Kullanım kolaylığı için Eclipse IDE'sini ekleyebiliriz. Eclipse IDE'si kurulumunu yapıp kodu çalıştırabiliriz.

![image](https://user-images.githubusercontent.com/82284108/147282412-73ef5f47-8505-4e70-8525-29aff96f4acd.png)



> Eclipse IDE'sinin kurulumu için aşağıdaki videodan yararlandım.
> 
> https://www.youtube.com/watch?v=Bhgnz6aZg1Y 
