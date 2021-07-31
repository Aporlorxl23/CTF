## ARCFOUR
#

Soruda bize bozuk QR kod verilmişti 
!(broken_qr)[Arcfour.png]

Bize verilen QR kodu https://www.gifgit.com/image/swirl-image sitesinden düzeltiyoruz 

!(qr)[QR.png]

Düzeltilmiş QR kodu okuduğumuz zaman bize 
`UGpiMlBGR3dPSDZRU2VqNkhaaGVocVRWMUFYcmU5RnJYcWFhdHRzbldaUTZoMCthS0MvcXpxcz0KUGFzczpDQkNIYWNrSXN0YW5idWw=` böyle bir Base64 dönüyor.

Base64'ü okuduktan sonra  

`Pjb2PFGwOH6QSej6HZhehqTV1AXre9FrXqaattsnWZQ6h0+aKC/qzqs= Pass:CBCHackIstanbul`

böyle bir çıktı geliyor bunuda RC4-40 ile decode edince karşımıza flag çıkıyor.

!(RC4-40)[RC4-40-decode.jpg]
