# COVID-19 Göğüs Röntgeni Sınıflandırma Projesi

Bu proje, göğüs röntgeni görüntülerini kullanarak COVID-19, Viral Pnömoni, Normal ve Akciğer Opaklığı durumlarını sınıflandıran bir derin öğrenme modelidir.

## 📋 Proje Açıklaması

Bu proje, COVID-19 salgını sırasında göğüs röntgeni görüntülerini analiz ederek hastalık tespiti yapmayı amaçlamaktadır. Model, dört farklı sınıfı ayırt edebilir:
- **COVID-19**: COVID-19 enfeksiyonu
- **Viral Pneumonia**: Viral pnömoni
- **Normal**: Sağlıklı akciğer
- **Lung Opacity**: Akciğer opaklığı

## 🛠️ Kullanılan Teknolojiler

- **Python 3.x**
- **PyTorch** - Derin öğrenme framework'ü
- **Torchvision** - Görüntü işleme ve veri yükleme
- **Pandas & NumPy** - Veri manipülasyonu
- **Matplotlib & Seaborn** - Görselleştirme
- **Scikit-learn** - Model değerlendirme

## 📊 Veri Seti

Proje [COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database) veri setini kullanmaktadır. Bu veri seti:
- Dengeli sınıf dağılımına sahiptir
- Göğüs röntgeni görüntülerini içerir
- Eğitim ve doğrulama için ayrılmıştır
- **Lisans:** CC BY-NC-SA 4.0 (Creative Commons Attribution-NonCommercial-ShareAlike 4.0)
- **Kaynak:** [Kaggle - COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database)

## 🚀 Kurulum ve Çalıştırma

1. **Gereksinimleri yükleyin:**
```bash
pip install torch torchvision pandas numpy matplotlib seaborn scikit-learn
```

2. **Veri setini indirin:**
   - Veri setini uygun bir kaynaktan indirin
   - `balanced_covid_dataset.zip` dosyasını çıkarın

3. **Jupyter Notebook'u çalıştırın:**
```bash
jupyter notebook medikal.ipynb
```

## 📈 Model Performansı

Model aşağıdaki metriklerle değerlendirilmiştir:
- **Doğruluk (Accuracy)**
- **Hassasiyet (Sensitivity)**
- **Özgüllük (Specificity)**
- **F1-Skoru**

## ⚠️ Önemli Notlar

- Bu proje eğitim amaçlıdır
- Tıbbi teşhis için kullanılmamalıdır
- Veri seti lisans durumunu kontrol ediniz

## 📝 Lisans

Bu proje eğitim amaçlı geliştirilmiştir. 

**Veri Seti Lisansı:** CC BY-NC-SA 4.0 (Creative Commons Attribution-NonCommercial-ShareAlike 4.0)
- Ticari kullanım yasaktır
- Atıf zorunludur
- Aynı lisansla paylaşım zorunludur

**Veri Seti Kaynağı:** [Kaggle - COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database)

## 🤝 Katkıda Bulunma

Projeye katkıda bulunmak istiyorsanız:
1. Fork yapın
2. Feature branch oluşturun
3. Değişikliklerinizi commit edin
4. Pull request gönderin

## 📞 İletişim

Sorularınız için issue açabilirsiniz. 