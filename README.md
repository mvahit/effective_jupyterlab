# Using JupyterLab Effectively (JupyterLab’ı etkin bir şekilde kullanma)

## 1. Kısayol Tuşları

Notebook verdiğimiz kısa yolları iki ayrı bileşen için ayrı ayrı algılar. Birisi hücreler için kullanacağımız kısa yol tuşları diğer hücrelerin dışında iken kullanacağımız kısayol tuşları. Örneğin hücre içinde bir şey kopyalayıp yapıştırmak istediğimizde bunu "ctrl + c", "ctrl + v" kombinasyonları ile yapabiliriz. Bu  işlemi hücre dışında hücrelere yönelik olarak yapmak istediğimizde "c" ve "v"duşlarına basmamız yeterli olacaktır. Dolayısıyla kısayol tuşlarını öğrenirken de buna göre öğrenmekte fayda var.

- Yukarı aşağı oklar ile hücreler arasında gezinilir.

- A: satırın üstüne boş satır ekler.

- B: satırın altına boş satır ekler.

- M: seçili hücreyi markdowna çevirir.

- Y: seçili hücreeyi code hücresine çevirir.

- D+D: iki defa D ye basıldığında üzerinde olunan hücre silinir.

- Z: işlemi geri alır.

- Shift + yön tuşları : birden fazla hücre seçmek için.

- Shift + m: seçili hücreleri birleştirir.


## 2. Markdown Özellikleri

Notebook'un markdown özelliklerini kullanarak yazılan yazılar aşağıdaki bazı özellikler ile biçimlendirilebilir.

* Normal bir yazı.

* Bu **kalın yazıdır**

* Bu _italik_ yazıdır.

Listeleme:

* Eleman1
* Eleman2
 * Bu da alt eleman
 * Bu da ikinci alt eleman

Numara ile Listeleme:

1. Numaralı liste
2. Numaralı liste


* Link Eklemek: [tıkla](https://www.veribilimi.co)

* Kod ifade etmek için markdown bölümünde "`sum()`" ifadesi kullanılır ve çıktısı şu şekilde olur: `sum()`

* Kod bloğu ya da girintili ifade için:

```
mean()

```

* Aynı işlemi 4 boşluk ile de ifade edebiliriz:

    foo()
