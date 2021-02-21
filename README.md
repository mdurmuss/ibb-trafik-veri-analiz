# ibb-trafik-veri-analiz
Bu projede İBB'nin paylaştığı 2019 yılı trafik veri seti üzerinde aşağıda tanımlanan hipotezlerin analizleri yapılacaktır.

**NOT:** Veri setinin ham halinde yalnızca tarih ve trafik indeksi yer almaktadır. Verinin son hali [buradan](https://github.com/skurmus/2019istanbultrafikverisi) alınmıştır.

## Hipotezler

- Ekim ayının pazartesi günleri Haziran ayının Pazartesi günlerinden daha fazla trafik olur.
* Haftasonu sabahları haftaiçinden daha az trafik olur.
- Mesai saatlerinin bitişinde mesai saati başlangıcından daha çok trafik olur.
* Dün mesai çıkışı yaşanan trafik ortalaması 40'dan fazlaysa bir sonraki gün trafik azalır.

- Sesli harfle başlayan aylarda diğer aylara göre fazla tatil günü vardır.



## Kaynaklar

- https://data.ibb.gov.tr/dataset/trafik-indeks-raporu
- https://pandas.pydata.org/pandas-docs/stable/index.html
- https://github.com/skurmus/2019istanbultrafikverisi
* https://realpython.com/ggplot-python/
- https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.html#pandas.DataFrame.plot