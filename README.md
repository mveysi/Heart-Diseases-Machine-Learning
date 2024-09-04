# Proje Amacı 

Bu veri seti 1988'den kalmadır ve dört değişkenden oluşur: Cleveland, Macaristan, İsviçre ve Long Beach V. Tahmin edilen değişken de dahil olmak üzere 76 değişken içerir, ancak yayınlanan tüm deneyler bunların 14'ünün bir alt kümesini kullanmaya atıfta bulunur. "Hedef" alanı hastada kalp hastalığının varlığının olup olmadığını ifade eder. Bütün modeller kulanıldı ve en başarılı Logistic Regression olmuştur. CatBoost modeli de tercih edilebilirdi.

![600x400_heart_illustration_xray](https://github.com/user-attachments/assets/fd54e8dd-348e-48f4-9721-009f8118c6a7)


# VERİ SETİ

| Age | Yaş |
| Sex | Cinsiyet.(0 = kadın; 1 = erkek)|

exang: Egzersize bağlı angina (göğüs ağrısı) (1 = var; 0 = yok)

ca: Büyük damar sayısı (0 - 3)

cp: Göğüs ağrısının türü. 

      Value 1: Tipik angina.

      Value 2: Atipik angina.

      Value 3: AnginaL olmayan ağrı.
      
      Value 4:  Asemptomatik.

trestbps: Dinlenme durumundaki kan basıncı (mm Hg).

chol: Kolesterol seviyesi (mgdl), BMI sensörü aracılığıyla elde edilir.

fbs: Açlık Kan Şekeri  120 mgdl (1 = doğru; 0 = yanlış)

restecg: Dinlenme esnasındaki EKG sonuçları.

      Value 0: Normal.

      Value 1: ST-T dalga anomaliliği.

      Value 2: Estes kriterlerine göre olası veya kesin sol ventriküler hipertrofi.

thalach: Maksimum kalp atış hızı sayısı.

target(Hedef):  

      0 = Kalp krizi olasılığı düşük.

      1 = Kalp krizi olasılığı yüksek.

exang: Egzersiz kaynaklı angina (1 = evet; 0 = hayır)

oldpeak: Dinlenmeye kıyasla egzersiz kaynaklı ST depresyonu
