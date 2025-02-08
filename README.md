# Random Yürüme

Unreal Engine 5 kullanılarak geliştirilmiş, NPC'lerin belirli bir alan içinde rastgele hareket etmelerini sağlayan bir sistemdir. Bu proje, Blueprint kullanılarak oluşturulmuş bir örnek çalışmayı göstermektedir.

---

## 🔹 Özellikler

- NPC'lerin rastgele bir yarıçap içinde hareket etmesi.
- Blueprint ile kolayca uygulanabilir bir sistem.
- Hareket sonrası duraklamalar ve tekrarlayan döngü mantığı.

---

## 🔹 Nasıl Çalışır?

1. **Başlangıç Olayı (Event BeginPlay)**:
   - NPC'nin oyuna başladığında hareket etmesini tetikler.

2. **Rastgele Nokta Seçimi (Get Random Reachable Point in Radius)**:
   - NPC'nin pozisyonuna bağlı olarak belirlenen yarıçap içinde bir nokta seçilir.

3. **Hedefe Hareket (AI MoveTo)**:
   - Seçilen rastgele noktaya NPC'nin hareket etmesi sağlanır.

4. **Gecikme (Delay)**:
   - Hareketler arasında belirli bir süre beklenir ve döngü tekrar başlar.

---

## 🔹 Blueprint Görseli

Aşağıdaki Blueprint yapısı, rastgele yürüyen NPC sistemini göstermektedir:

![1](https://github.com/user-attachments/assets/905644b0-e673-4009-ad37-c28571c61a3b)
