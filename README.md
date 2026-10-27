# voices

"Namaz Öğrenme ve Takibi" uygulamasının sesli anlatım dosyaları.
Uygulama, kullanıcının dilindeki dosyaları ilk kullanımda buradan (jsDelivr
üzerinden) bir kez indirir. Türkçe sesler uygulamanın içindedir.

Yapı: `<dil>/prayer/<dosya>.mp3` (13 dosya) ve `<dil>/wudu/<dosya>.mp3` (10 dosya).
Diller: en, de, fr, id, ar, ur, hi.

Dosyaları değiştirirken yeni bir etiket (v2, v3…) oluşturun ve uygulamadaki
`src/config/narration.ts` içinde adresi ve `NARRATION_VERSION` değerini güncelleyin.
