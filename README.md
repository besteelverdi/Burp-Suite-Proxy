# Burp Suite

Burp veya Burp Suite, web uygulamalarının sızma testi için kullanılan bir dizi araçtır. İnternet tarayıcıları GET ve POST isteklerini ve daha bir çok şeyi görsel hale getirir. HTML ve Javascripti çalıştırır. Arka planda olan şeyleri görmek istiyorsak Burp Suite aracını kullanabiliriz. Linkten Burp Suite'i indirebilirsiniz.
https://portswigger.net/burp/releases/professional-community-2020-11-1?requestededition=community

Burp Suite'i kurduktan sonra, Proxy olarak kullanmak için çalışır olduğunu denetlemek gerekmektedir. Proxy > Options sekmesine giderek interface tanımlandığından ve running kutucuğunun işaretli olduğundan emin olun
![image](https://user-images.githubusercontent.com/70814577/112728769-e43c5880-8f39-11eb-83fe-e3b26b3ce1d2.png)

Burp Suite'i tarayıcınızda vekil olarak kullanmak için firefox tarayıcınızdan Seçenekler > Ağ ayarları'nı açınız. Vekil sunucuyu elle ayarla seçeneğini seçerek daha önce bulduğumuz interface adresini resimdeki gibi yazınız. Böylece istekleriniz ilk olarak Burp Suite proxy'e gider ve atadığınız vekil ile sayesinde gerçekleştirilir.
![image](https://user-images.githubusercontent.com/70814577/112728920-9ffd8800-8f3a-11eb-975f-20b1674701bf.png)

Bağlanmak istediğiniz siteler SSL sertifikasına sahip ise Burp Suite ile bu sitelere erişemeyebilirsiniz. Bunun için geçerli sertifika indirerek ayar yapmanız gerekmektedir.
http://burp adresine giderek  CA Certificate yazısına tıklayınız ve dosyayı kaydediniz.
![image](https://user-images.githubusercontent.com/70814577/112729169-dee00d80-8f3b-11eb-8122-5195122032c7.png)

İndirdiğiniz sertifikayı tarayıcınıza aktarmanız gerekmektedir. Seçenekler > Gizlilik ve Güvenlik > Sertifikalar > Sertifikaları Görüntüle'ye giderek içe aktara tıklayınız ve indirdiğiniz sertifikayı seçiniz. Çıkan pencerede sertifikaya güvendiğinize dair seçenekleri işaretleyiniz.
![image](https://user-images.githubusercontent.com/70814577/112729284-72194300-8f3c-11eb-802c-9debcddab0d4.png)



![image](https://user-images.githubusercontent.com/70814577/112729403-f7045c80-8f3c-11eb-8bf3-49f5d8d81fbe.png)
![image](https://user-images.githubusercontent.com/70814577/112729415-05527880-8f3d-11eb-980c-b3d92fc41707.png)


