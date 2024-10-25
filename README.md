# Web3-Proje

## Genel Bakış

Bu örnek, temel bir hesap makinesi DApp'ını göstermektedir. En son hesaplamanın sonucunu temsil eden rastgele hassasiyetli bir tamsayıyı saklamak için ortogonal olarak kalıcı bir hücre değişkeni kullanır. Uygulama, aşağıdaki yöntemleri sunan bir arayüz sağlar:

- **add**: Girdiyi kabul eder ve toplama işlemini gerçekleştirir.
- **sub**: Girdiyi kabul eder ve çıkarma işlemini gerçekleştirir.
- **mul**: Girdiyi kabul eder ve çarpma işlemini gerçekleştirir.
- **div**: Girdiyi kabul eder, bölme işlemini gerçekleştirir ve sıfıra bölmeye karşı koruma sağlamak için isteğe bağlı bir tür döndürür.
- **clearall**: Değerini sıfıra ayarlayarak hücre değişkenini temizler.


## Ön Koşullar

Bu örnek için aşağıdaki kurulum adımlarını takip etmeniz gerekmektedir:

1. **IC SDK'yı yükleyin**.
2. **Örnek DApp projesini klonlayın**:

   ```bash
   git clone https://github.com/dfinity/examples

