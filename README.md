# Machine-learning-ile-ger-ek-yada-sahte-yorum-tespiti
Twitterdan alınan 400’ olumlu gerçek yorum, olumlu sahte yorum, olumsuz sahte ve olumsuz gerçek yorum bilgileri her yorum 1 txt de bulunmak üzere toplam 1600 txt’lik bir datasetimiz mevcuttur. Bizden istenilen bir yorumun gerçek yada sahte olup olmadığı tahminini machine learning algoritmalarını kullanarak gerçeklememizdir. İlk olarak 400’er olarak txt’ler kendi grubuna göre cmd üzerinden birleştirildi. Elimizdeki txtler üzerinde büyük küçük harf kontrülü  gerçek olup olmadığı bilgsine dayalı veri manipülasyonu ve preprocecing adımları gerçekleştirildi. Txt’deki yorumlar üzerinde öncelikle büyük küçük harf kontrolü ,sembollerin çıkarılması ,dil bilgisine dayalı en çok kullanılan sözcüklerin çıkarılması (ı , you ,will ,we,my) Adımları gerçekleştirilerek elimizdeki txt sütunu sadeleştirilmiş ve gerekli olanlar kalmıştır. Ardından gerçek olup olmadıklarına dair bilgisine dayalı veri manipülasyonu gerçekleştirilip dataset machine learning algoritmalarına hazırlanmıştır.Machine learning algoritması olarak Support vektör machine , multinomal naive bayes , Decision Tree kullanılmıştır. En yüksek n fold cross validation skoruna Multinomal nb 86.21 ile sahiptir.gerekli hata metrikleri ve skorlar arasındaki farklar grafiksek olarak gösterilmiştir
