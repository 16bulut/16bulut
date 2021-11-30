int sensörPin = 9 ;                  // Sensörün takılacağı pini
int buzzerPin = 8 ;                  // Buzzerın takılacağı pini
int veri;                           // Sensörden okunan verinin alınacağı

geçersiz  kurulum () {
  pinMode (sensorPin, GİRİŞ);        // Sensörün takılacağı pini INPUT olarak ayarlıyoruz.
  pinMode (buzzerPin, ÇIKIŞ);       // Buzzerın takılacağı pini ÇIKIŞ olarak ayarlıyoruz.
}
boşluk  döngüsü () {
  veri = digitalRead (sensorPin);    // Sensörden dijital okuyoruz.
  eğer (veri == true ) {             // Sensör verisi eşik değerini geçerse içerisindeki kodlar uygulanir eğer.
    digitalWrite (buzzerPin, YÜKSEK);
    gecikme ( 100 );
    digitalWrite (buzzerPin, DÜŞÜK);
    gecikme ( 100 );
  }
  else {                              // Sensör verisi eş değerinden küçükse, kodlar uygulanır.
    digitalWrite (buzzerPin, DÜŞÜK);
  }
}
