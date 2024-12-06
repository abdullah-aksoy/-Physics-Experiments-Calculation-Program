# Fizik Deneyleri Hesaplama Programı

Bu C programı, çeşitli fizik deneyleri için hesaplamalar yapar. Program, serbest düşme, Atwood makinesi, hava masası ve balistik sarkaç deneyleri için hesaplamalar yapar ve sonuçları kullanıcıya gösterir.

## Özellikler

- Serbest düşme deneyinde zaman ortalaması, deneysel ivme, delta ivme ve hata oranını hesaplar.
- Atwood makinesi deneyinde zaman ortalaması, deneysel ivme, beklenen ivme, delta ivme ve hata oranını hesaplar.
- Hava masası deneyinde hız ve ivme hesaplamaları yapar.
- Balistik sarkaç deneyinde topun çıktığı yükseklik, çarpışmadan önceki hız ve çarpışmadan sonraki hızı hesaplar.

## Gereksinimler

- C derleyicisi (örneğin, GCC)

## Kurulum

1. Depoyu klonlayın:
    ```sh
    git clone https://github.com/abdullah-aksoy/fizik-deneyleri
    cd fizik-deneyleri
    ```

2. Programı derleyin:
    ```sh
    gcc -o fizik-deneyleri fizik-deneyleri.c -lm
    ```

## Kullanım

1. Derlenmiş programı çalıştırın:
    ```sh
    ./fizik-deneyleri
    ```

2. Menüden bir deney seçin ve istenen değerleri girin.

## Kod Açıklaması

Program aşağıdaki adımları gerçekleştirir:

1. Kullanıcıdan deney seçimi yapmasını ister.
2. Seçilen deneye göre gerekli değerleri kullanıcıdan alır.
3. Hesaplamaları yapar ve sonuçları ekrana yazdırır.
4. Kullanıcı çıkış yapana kadar bu işlemleri tekrarlar.
