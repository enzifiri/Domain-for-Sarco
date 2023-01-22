# Hosting.com.tr sitesinde DNS ayarı nasıl yapılır?

## Alttaki linke tıklayın ve sağdaki yönet tusuna basın.

[Buraya Tıkla](https://www.hosting.com.tr/musteri-paneli/domainlerim)

![image](https://user-images.githubusercontent.com/76253089/213944894-318c0025-5b4e-4824-9962-83700cacf02e.png)

## Solda Domain Parking Menüsünün altında DNS Zone yönetimine tıklayın ve Domain Parkingi etkinleştirin

![image](https://user-images.githubusercontent.com/76253089/213945027-c993fd84-8ebf-4c6d-8231-a7b2fac13d6e.png)

## İşaretlediğim yerleri fotoğraftaki gibi doldurun ve kaydedin.

![image](https://user-images.githubusercontent.com/76253089/213945236-1e6c084a-b89e-45f5-b265-bc23e06669e4.png)

## Şimdi Terminale gidip çıktıyı kontrol edelim. Alttaki komutu girin <br>
``docker logs quickstart-archaeologist-acme-companion-1``

## Eğer çıktı Aşağıdaki şekildeyse hata var bu komutları uygulayıp tekrar kontrol edin.

``cd quickstart-archaeologist`` <br>
``COMPOSE_PROFILES=service docker compose stop``  <br>
``COMPOSE_PROFILES=service docker compose pull`` <br>
``COMPOSE_PROFILES=service docker compose up -d`` <br>

Hatalı çıktı örneği;
![image](https://user-images.githubusercontent.com/76253089/213945576-7f26ac67-ad45-44d0-b9e1-74303ecd15d9.png)

Başarılı çıktı örneği;
![image](https://user-images.githubusercontent.com/76253089/213945770-d9f931c5-0854-42c0-9722-7735abc8cf71.png)

