# Bank Marketing Dataset ile Çok Değişkenli İstatistiksel Analizler

Bu proje, Çok Değişkenli İstatistiksel Yöntemler dersi kapsamında hazırlanmıştır. Çalışmada UCI Machine Learning Repository üzerinde yayımlanan Bank Marketing veri seti kullanılmıştır. Veri seti, Portekiz’de bir bankanın müşterilerine yönelik telefonla yürüttüğü doğrudan pazarlama kampanyalarına ait kayıtları içermektedir.

Projenin temel amacı, müşterilerin demografik özellikleri, finansal durumları ve kampanya etkileşimleri üzerinden çok değişkenli istatistiksel yöntemler kullanarak veri setinin yapısını incelemek ve anlamlı sonuçlar elde etmektir.

## Kullanılan Veri Seti

Veri seti, bankanın müşterilerine vadeli mevduat ürünü teklif ettiği pazarlama kampanyalarına aittir. Analizlerde müşteri yaşı, meslek, medeni durum, eğitim düzeyi, bakiye, görüşme süresi, kampanya sayısı, önceki kampanya bilgileri ve müşterinin ürünü kabul edip etmediği gibi değişkenler kullanılmıştır.

Analiz öncesinde veri seti SPSS üzerinden küçültülmüş ve çalışma 478 gözlem üzerinden yürütülmüştür.

## Yapılan Analizler

Projede aşağıdaki çok değişkenli istatistiksel yöntemler uygulanmıştır:

- Veri özeti ve tanımlayıcı istatistikler
- Kayıp gözlem incelemesi
- Normallik testleri
- Tek yönlü MANOVA
- Çift yönlü MANOVA
- Temel Bileşenler Analizi
- Faktör Analizi
- İki gruplu Diskriminant Analizi
- Çok gruplu Diskriminant Analizi
- Lojistik Regresyon Analizi
- Kümeleme Analizi

## Genel Bulgular

Analiz sonuçlarına göre veri setindeki değişkenlerin çoğunun normal dağılım göstermediği görülmüştür. MANOVA sonuçlarında bakiye grupları arasında özellikle yaş değişkeni bakımından anlamlı farklılıklar bulunmuştur. Çift yönlü MANOVA analizinde eğitim ve medeni durum değişkenlerinin yaş üzerinde anlamlı etkileri olduğu, ancak görüşme süresi ve kampanya sayısı üzerinde anlamlı bir etkisinin olmadığı görülmüştür.

Temel Bileşenler Analizi ve Faktör Analizi sonucunda özellikle `pdays` ve `previous` değişkenlerinin birlikte hareket ettiği ve geçmiş kampanya etkileşimlerini temsil eden önemli bir yapı oluşturduğu belirlenmiştir. Diskriminant analizinde ise grupları ayırmada özellikle bakiye ve yaş değişkenlerinin daha etkili olduğu görülmüştür.

## Kullanılan Araçlar

- SPSS
- R
- SAS
- UCI Machine Learning Repository veri seti

## Amaç

Bu proje, bankacılık sektöründe müşteri davranışlarını çok değişkenli istatistiksel yöntemlerle analiz etmeyi ve pazarlama kampanyalarına ilişkin değişkenler arasındaki ilişkileri yorumlamayı amaçlamaktadır.
