### Pokémon Projesi

Bu projede, Pokémon kartlarını tanıtan bir web sitesi geliştirdim. Kullanıcılar, sayfa üzerindeki bir buton yardımıyla rastgele bir Pokémon kartı oluşturabiliyor. Her kartta Pokémon'un görseli, adı, türü ve bazı istatistikleri (HP, Attack, Defense, Speed) gibi temel bilgiler yer alıyor. Projede hem frontend hem de backend tarafında çeşitli teknolojiler ve diller kullandım.

#### Projede Kullanılan Teknolojiler

1. **HTML & CSS**: 
   - **HTML** ile sayfanın temel yapısını oluşturup, kartları ve butonları yerleştirdim.
   - **CSS** ile sayfanın tasarımını ve stilini oluşturdum. Özellikle, arka plan resmi, kartların stilizasyonu, buton tasarımı ve tipografi üzerinde çalıştım. Arka planda Pokémon'un ikonik logosunu kullandım ve bu resmi sayfada ortalayarak kartların arkasına yerleştirdim.
   
   **Öne Çıkan CSS Özellikleri:**
   - **background-size**, **background-position** ve **background-attachment** kullanarak arka planın tüm ekran boyunca düzgün bir şekilde görünmesini sağladım.
   - Kartların modern ve sade bir görünüme sahip olması için **box-shadow**, **border-radius** gibi özellikleri kullandım.
   - Flexbox ile kartın ve diğer elemanların sayfa üzerinde düzgün bir şekilde hizalanmasını sağladım.

2. **JavaScript**:
   - **JavaScript** kullanarak rastgele bir Pokémon kartı oluşturma işlevini yazdım. Bir API veya JSON dosyası üzerinden rastgele Pokémon verilerini çektim ve her butona tıklanışta sayfa üzerinde yeni bir kart oluşturulmasını sağladım.
   
   **Öne Çıkan JavaScript Özellikleri:**
   - **Math.random()** ve **array manipulation** kullanarak rastgele bir Pokémon seçimi yaptım.
   - DOM manipülasyonu ile oluşturulan Pokémon verilerini dinamik olarak kartlara ekledim.
   - **Event listeners** ile buton tıklamaları sonucu kart oluşturma işlemini tetikledim.
   - Kartların görsel özellikleri ve verilerini sayfa içinde uygun yerlerde göstermeyi sağladım.

#### Projenin Özellikleri

- **Responsive Tasarım**: Sayfa, tüm cihazlarda (mobil, tablet, masaüstü) düzgün görünecek şekilde tasarlandı. CSS'de kullanılan esnek yapılar sayesinde ekran boyutuna göre öğeler yeniden hizalanır ve görünüm bozulmaz.
  
- **Rastgele Pokémon Oluşturma**: Sayfadaki "Generate" butonuna her basıldığında rastgele bir Pokémon kartı görüntülenir. Bu, JavaScript ile DOM manipülasyonu yapılarak sağlanmıştır. 

- **Arka Plan Resmi**: Sayfanın arka planında Pokémon logosunu sabitledim. Logo, kartların arkasında büyükçe görünerek tematik bir hava yaratıyor. Arka plan resmi sayfanın ortasında ve kartların arkasında düzgünce hizalanmış durumda.

- **JavaScript İle Dinamik İçerik**: Butona her basıldığında sayfa üzerindeki kart dinamik olarak güncelleniyor. Yeni bir Pokémon verisi alınarak görsel ve istatistikler kart üzerinde gösteriliyor. JavaScript ile bu verilerin dinamik şekilde güncellenmesi sağlandı.

Bu proje, temel olarak Pokémon hayranları için eğlenceli ve kullanışlı bir kart oluşturma deneyimi sunuyor. Hem tasarım hem de JavaScript işlevleri sayesinde kullanıcı dostu ve interaktif bir arayüz oluşturuldu.



https://github.com/user-attachments/assets/eb440e3a-0ec4-4702-88b9-688d8a756da8


