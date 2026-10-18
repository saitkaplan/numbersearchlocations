# Number Search Locations

A tiny script that looks up where a phone number is from and which carrier it belongs to, using the [`phonenumbers`](https://pypi.org/project/phonenumbers/) library. One of the first programs I wrote while learning Python, between July and November 2023, kept here as it was.

## Run

Requires Python 3.

```bash
pip install -r requirements.txt
python3 main.py
```

The number to look up is in `test.py`. The script prints the region on the first line and the carrier on the second (empty for landlines).

## Notes

- The code is kept exactly as written back then; only line endings were normalized.
- The number in `test.py` was replaced with `+44 20 7946 0000`, a number Ofcom reserves for use in fiction, so no real person's number is published. It prints `London` and an empty carrier line.

## License

[MIT](LICENSE)

---

## Numara Konum Bulucu (Türkçe)

Bir telefon numarasının nereye ve hangi operatöre ait olduğunu [`phonenumbers`](https://pypi.org/project/phonenumbers/) kütüphanesiyle bulan küçük bir betik. Python öğrenirken, Temmuz ile Kasım 2023 arasında yazdığım ilk programlardan biri; hatıra olarak olduğu gibi saklanıyor.

### Çalıştırma

Python 3 gerekir.

```bash
pip install -r requirements.txt
python3 main.py
```

Sorgulanan numara `test.py` dosyasındadır. Betik ilk satırda bölgeyi, ikinci satırda operatörü basar (sabit hatlarda boş kalır).

### Notlar

- Kod o zaman yazıldığı gibi duruyor; yalnızca satır sonları düzenlendi.
- `test.py`'deki numara, gerçek bir kişinin numarası yayımlanmasın diye `+44 20 7946 0000` ile değiştirildi; bu numara İngiltere'nin iletişim düzenleyicisi Ofcom tarafından kurgu eserlerde kullanılmak üzere ayrılmıştır. Çıktı `London` ve boş bir operatör satırıdır.

### Lisans

[MIT](LICENSE)
