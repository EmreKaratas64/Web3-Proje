# Web3-Proje

anahtar kelimeler: [basic, motoko, hesap makinesi, calc]

Genel Bakış
Bu örnek temel bir hesap makinesi dapp'ını göstermektedir. En son hesaplamanın sonucunu temsil eden rastgele hassasiyetli bir tamsayıyı saklamak için ortogonal olarak kalıcı bir hücre değişkeni kullanır.
Uygulama, aşağıdaki yöntemleri ortaya çıkaran bir arayüz sağlar:

add: girdiyi kabul eder ve toplama işlemini gerçekleştirir.
sub: girdiyi kabul eder ve çıkarma işlemini gerçekleştirir.
mul: girdiyi kabul eder ve çarpma işlemini gerçekleştirir.
div: girdiyi kabul eder, bölme işlemini gerçekleştirir ve sıfıra bölmeye karşı koruma sağlamak için isteğe bağlı bir tür döndürür.
clearall: değerini sıfıra ayarlayarak hücre değişkenini temizler.


Ön Koşullar
Bu örnek bir kurulum gerektirir:
[x] IC SDK'yı yükleyin .
[x] Örnek dapp projesini klonlayın: git clone https://github.com/dfinity/examples
Bir terminal penceresi açarak başlayın.

Adım 1: Projenin dosyalarını içeren klasöre gidin ve komutla çoğaltmanın yerel bir örneğini başlatın:
cd examples/motoko/calc
dfx start --arka plan

Adım 2: Kanisteri şu komutla dağıtın:
dfx deploy

Adım 3: Bir hesap makinesi işlevi çalıştırın. Örneğin, 2 ile 3'ü çarpmak için:
dfx canister call calc add '(2)'
dfx kutu çağrı calc mul '(3)'

Çıktı:
(2 : int)
(6 : int)
