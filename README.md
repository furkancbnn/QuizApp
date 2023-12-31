﻿# Quiz Oyunu

Bu depo, HTML, CSS ve JavaScript kullanılarak oluşturulmuş basit bir quiz oyununu içerir. Oyun, kullanıcılara çoktan seçmeli sorular sunar. Kullanıcılar cevaplarını seçer ve oyun doğruluk hakkında geri bildirim sağlar. Amaç, mümkün olan en çok soruyu doğru cevaplamaktır.

## Nasıl Oynanır

1. Sayfayı ziyaret ederek quiz'i başlatın.
2. Her bir soruyu sağlanan seçeneklerden birini seçerek cevaplayın.
3. Cevabınızın doğruluğu hakkında anında geri bildirim alın.
4. Bir sonraki soruya devam edin.
5. Quiz'in sonunda toplam puanınızı görün ve isterseniz tekrar oynayın.

## Proje Yapısı

- **HTML (index.html):** Oyunun kullanıcı arayüzünü tanımlar, soruları, cevap seçeneklerini ve kontrol düğmelerini içerir.

- **CSS (style.css):** Kullanıcı arayüzü için stil sağlar, renkler, düzen ve animasyonlar içerir.

- **JavaScript (script.js):** Oyunun mantığını uygular, soruları, cevapları, puanlamayı ve kullanıcı etkileşimlerini ele alır.

## Fonksiyonlar

- **startQuiz():** Quiz'i başlatır ve başlangıç durumunu ayarlar.

- **showQuestion():** Kullanıcıya mevcut soruyu ve cevap seçeneklerini gösterir.

- **resetState():** Oyun durumunu sıfırlar, cevap düğmelerini temizler ve bir sonraki soru düğmesini gizler.

- **selectAnswer(e):** Kullanıcının seçtiği cevapları ele alır, görsel geri bildirim sağlar ve cevap düğmeleriyle daha fazla etkileşimi devre dışı bırakır.

- **showScore():** Quiz'in sonunda kullanıcının toplam puanını gösterir ve tekrar oynamak için seçenek sunar.

- **handleNextButton():** Bir sonraki soruya veya quiz'in sonuna geçişi yönetir.

Quiz'in tadını çıkarın!
