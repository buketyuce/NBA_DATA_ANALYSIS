# NBA VERİ ANALİZİ
![indir](https://user-images.githubusercontent.com/101973346/182043886-f85761ec-f534-4515-a7e8-ba7318086dec.png)

# Kullanılan Kütüphaneler:

* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* warnings


# Veri Seti Hikayesi

5 veri seti mevcut:

* games: Her oyun hakkında bilgiler ve oynayan takımların istatistikleri

* games_details: Bireysel oyuncu istatistikleri hakkında daha ayrıntılı bilgi

* players: Oyuncunun adı ve takımı hakkında bilgiler

* ranking: Her takımın sezon boyunca belirli günlerdeki durumu hakkında bilgi

* teams: Sahiplik, arena, ne zaman kurulduğu vb. dahil takım hakkında bilgiler



# Yapılacak Analizler

Mevcut olan veriler birleştirilerek ve çeşitli işlemlerden geçirilerek iki farklı ana nokta üzerinden analizler gerçekleştirildi:

# 1) 2014-2021 Yılları arasında oynanmış olan tüm maçların genel analizi

* En çok kazanan 3 takım hangileri? 

<img width="591" alt="Ekran Resmi 2022-08-03 13 11 04" src="https://user-images.githubusercontent.com/101973346/182584908-cff3532a-589c-4c52-95b7-f2f61fbce9d9.png">

* Kazanmaya etki eden şeyler neler olabilir?

<img width="894" alt="Ekran Resmi 2022-08-03 13 00 15" src="https://user-images.githubusercontent.com/101973346/182584998-75638b12-6b6e-45ff-a801-454f2dd44cd8.png">


Kazanma oranı ile , saha gol başarı oranı ve üçlük başarı oranı arasında bir ilişki var gibi gözüküyor.

gol oranı ile kazanma oranı arasında ilişki olması beklenen bir durum.

üçlük başarı oranı ile ilgili daha detaylı bir inceleme yapılabilir.

<img width="856" alt="Ekran Resmi 2022-08-03 13 01 39" src="https://user-images.githubusercontent.com/101973346/182585108-ee95c80f-3f90-43f4-ba9e-dd9fd51c145b.png">

Bakıldığı zaman takımların üçlük deneme sayısının yıllar geçtikçe arttığı söylenebilir. Bu bilgi de üçlük başarısnın kazanmaya etkisi olduğu bulgusunu destekler niteliktedir.



# 2) Oyundaki detayların oyunu kazanmaya etkisi

* Takımlar kendi sahasındayken daha iyi performans gösterir mi? 
<img width="338" alt="Ekran Resmi 2022-08-03 13 03 45" src="https://user-images.githubusercontent.com/101973346/182585247-e2a8aa43-3ce5-4b4c-9205-943507e1f2ba.png">

Takımların kendi sahasında daha başarılı olduğu bilgisi çıkarılabilir.

Farklı sezonlarda ev sahibi ve deplasman takım puan istatistiklerine de bir göz atmakta fayda olacaktır.

<img width="624" alt="Ekran Resmi 2022-08-03 13 04 58" src="https://user-images.githubusercontent.com/101973346/182585317-5a0fdd6e-f1fd-4e68-8efc-23784af4b230.png">


# BONUS:

Özellikleri belirtildiğinde takımın kazanıp kazanmadığını tahmin edebilecek bir makine öğrenmesi modeli geliştirilmesi

* Veri seti bir oyunda olan her anı içerdiği için oyunları gruplayarak inceleme yapıldı.

* Özellik çıkarımları gerçekleştirildi

* Sayısal değişken analizi yapıldı

* Hedef değişken analizi yapıldı. (Hedef değişken "Kazanma durumu"; 1 kazandığını, 0 ise kazanamadığını belirtmektedir.)

* Korelasyon analizi yapıldı.

* Aykırı değer ve eksik değer analizi yapıldı.

*  Encoding işlemleri yapıldı.

* Standartlaştırma yapıldı.  

<img width="126" alt="Ekran Resmi 2022-08-03 13 25 02" src="https://user-images.githubusercontent.com/101973346/182586206-fbc623a6-cb76-4ff9-83ff-8c78285c9635.png">

<img width="585" alt="Ekran Resmi 2022-08-03 13 08 52" src="https://user-images.githubusercontent.com/101973346/182586266-b44319d1-3533-4266-bb53-0fa646f77a8a.png">






