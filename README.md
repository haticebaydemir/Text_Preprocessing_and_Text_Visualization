# Text_Preprocessing_and_Text_Visualization
# Metin İşleme ve Görselleştirme Projesi

## Proje Hakkında

Bu projeyi, doğal dil işleme (NLP) teknikleri ve görselleştirme yöntemlerini kullanarak metin verilerini analiz etmek amacıyla geliştirdim. Wikipedia'dan alınan metin verileri üzerinde çeşitli ön işleme adımları uyguladım ve bu süreçte kelime frekansları ile görselleştirmeleri elde ettim. Proje, dil modelleme ve metin analizi alanında bir referans olarak kullanılabilir.

## Teknolojiler ve Gereksinimler

Projede kullandığım kütüphaneler:

- **Pandas**: Veri analizi ve manipülasyonu için.
- **Matplotlib**: Görselleştirme için.
- **WordCloud**: Kelime bulutları oluşturmak için.
- **NLTK**: Doğal dil işleme için.
- **TextBlob**: Basit NLP görevleri için.

### Gereksinimlerin Kurulumu

Gerekli kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:

```bash
pip install pandas matplotlib wordcloud nltk textblob
```

# Veri Yükleme
Projem, Google Drive üzerinde depolanan bir ZIP dosyasındaki CSV dosyasını yüklemektedir. Aşağıdaki adımları izleyerek veriyi yükleyebilirsiniz:

1. Google Drive'ınızı bağlayın..
2. ZIP dosyasının yolunu güncelleyin..
# İş Akışı
1. **Veri Yükleme**
- Google Drive'dan ZIP dosyasını açarak içindeki CSV dosyasını yükledim.
- İlk 2000 satırı kullanarak verinin boyutunu optimize ettim.

2. **Veri Temizleme**
- Metinleri küçük harflere dönüştürdüm.
- Noktalama işaretlerini ve sayıları kaldırdım.
- Anlam taşımayan kelimeleri (stopwords) çıkardım.
3. **Kelime Frekansı Analizi**
- Metinde az geçen kelimeleri belirleyip çıkardım.
- Tokenizasyon işlemi gerçekleştirdim.
- Lemmatizasyon uygulayarak kelimelerin kök hallerini elde ettim.
4. **Görselleştirme**
- Kelime frekanslarını analiz edip bar grafiği oluşturdum.
- WordCloud ile kelime dağılımını görselleştirdim.

# Kullanım
Projemi Google Colab ortamında çalışacak şekilde tasarladım. Aşağıdaki adımları izleyerek projeyi çalıştırabilirsiniz:

1.Yukarıdaki tüm kodları bir hücreye yapıştırın.

2.zip_file_path değişkenini kendi ZIP dosyanızın yoluyla güncelleyin.

3.Hücreyi çalıştırarak tüm süreci gerçekleştirin.

# Çıktılar
Projenin sonunda elde ettiğim çıktılar:

- Kelime frekanslarının bar grafiği
- WordCloud görselleştirmesi

Bu görseller, metin verisinin dil yapısını ve dağılımını daha iyi anlamanızı sağlar.

# Katkı
Bu projeyi, doğal dil işleme alanında daha fazla bilgi edinmek ve uygulama geliştirmek isteyenler için bir başlangıç noktası olarak tasarladım. Geri bildirimlerinizi ve katkılarınızı her zaman beklerim.

# İletişim

Sorularınız veya önerileriniz için aşağıdaki iletişim bilgilerini kullanabilirsiniz:

E-posta: baydemirhatice@hotmail.com

Linkedln: https://www.linkedin.com/in/haticebaydemir/
