# doviz-borsa-kripto-api
Bulunan Tüm Döviz Kurları, Borsa ve Kripto Fiyatları Toplu API Servisleri

## Paragaranti Foreks API
- BIST Endeks Listesi: https://web-paragaranti-pubsub.foreks.com/web-services/securities/exchanges/BIST/groups/E
- BIST Endes Alfabetik Detaylı Liste: https://web-paragaranti-pubsub.foreks.com/web-services/securities?key=A&index=&exchangeGroupFilter=BIST.E&extendedResult=true ( * key=**HARF** )
- BIST Endeks Detayı: https://web-paragaranti-pubsub.foreks.com/web-services/securities/definition?name=**ENDEKS_ISMI**&group=E&exchange=BIST (**ENDEKS_ISMI** yazan bölüme bir üst satırlardaki Endeks isimleri gelecektir.)
- BIST Yatırım Kuruluşları Listesi: https://web-paragaranti-pubsub.foreks.com/web-services/securities/exchanges/BIST/groups/I

## canlidoviz.com Api
- Döviz: https://api.canlidoviz.com/web/items?marketId=1&type=0
- Altın: https://api.canlidoviz.com/web/items?marketId=1&type=1
- Kripto: https://api.canlidoviz.com/web/items?marketId=1&type=2

## Hürriyet Bigpara Api
- Hisse Listesi: http://bigpara.hurriyet.com.tr/api/v1/hisse/list
- Hisse Detay: http://bigpara.hurriyet.com.tr/api/v1/borsa/hisseyuzeysel/AEFES (*AEFES temsili değerdir, bir üst satırdaki **kod** verisi kullanılacaktır.)
