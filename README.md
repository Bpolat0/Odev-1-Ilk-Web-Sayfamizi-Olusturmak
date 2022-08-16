# Site Görüntüsü

![Img](/Images/Proje%20%C3%87%C4%B1kt%C4%B1s%C4%B1.png)

# Kullandığım Kodlar

* ! + Tab = Html İskeleti Oluşturuyor

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

* "head" = Site ziyaretçileri tarafından görülmesi gerekmeyen kodları içerir. 

```
<head> </head>
```

* "body" = Web sayfamızda görmek istediğimiz bütün içerikleri body etiketi altına yazıyoruz.

```
<body> </body>
```

* Ctrl + Ö = Yorum satırı oluşturma.

```
<!-- Buraya yorum yazılacak -->
```

* "h1" = H etiketleri başlık etiketleridir. Büyükten küçüğe sırasıyla:

```
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>
```

* "p" = Etiketi paragraf etiketidir. Sayfa içerisinde oluşturacağımız metinleri etiketi ile oluştururuz.

```
<p> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eius cumque sequi repudiandae dolorem harum cupiditate debitis distinctio saepe accusantium, error inventore, tempore doloribus, quas a recusandae? Minima consequuntur possimus velit?
</p>
```

* "ul" ve "li" = "ul" = "unordered list" sırasız liste anlamına geliyor. Listeyi oluşturduktan sonra içeriğini oluşturmak için "li" etiketini kullanıyoruz.

```
 <ul>
        <li>A</li>
        <li>B</li>
        <li>C</li>
    </ul>
    
    <ol>
        <li>A</li>
        <li>B</li>
        <li>C</li>
    </ol>
```

* "img" = Resim eklemek için "img" etiketini kullanıyoruz. "img src=”resim.jpg” alt=”açıklama yazısı” /> src="" kısmına eklemek istediğimiz görselin yolunu yani kaynağını yazmalıyız.

```
<img src="https://c.tenor.com/AATQJ1cM-IgAAAAC/cheems-doge.gif" alt="cheems-doge">
```

* "iframe" = Belge içinde belge gösterebilmemizi sağlayan etikettir. Örn: Youtube'dan bir videoyu sayfamızda göstermek istersek "iframe" kodlarını sayfamıza eklememiz yeterli. Videoya sağ tıklayın yerleştirme kodunu kopyala seçeneğini seçin.

```
<iframe width="942" height="539" src="https://www.youtube.com/embed/ZwCw-LpvZfE" title="Spinning Cheems" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

* "br" = "br" etiketi satır atlatma etiketidir ve kapatmaya ihtiyaç duymayan etiketlerden biridir. Atlatmak istediğiniz satır sayısı kadar "br" etiketi kullanabilirsiniz.

```
<br><br>
```

* "a" ve "href" = "a" etiketinin en önemli özelliği href özelliğidir. Bu etiket ile sayfaları linkleyebiliriz. Etiket içerisine yazılan içerik sayfa üzerinde gösterilecek içeriktir. href içine yazılan ise tıklandığında gideceği URL'dir.

```
<a href="https://youtu.be/ZwCw-LpvZfE"><button style="height:200px;width:200px">Cheems Button</button></a>
```

* "button" = "button" etiketini buton oluşturmak için kullanırız. Buton üzerine yazmak istediğiniz içeriği etiketin içine yazmanız yeterlidir.

```
<button>Tuş</button>
```

* "audio" = HTML ile ses çalmak için "audio" etiketi kullanılır. HTML "audio" ve "audio" etiketleri arasındaki yazı "audio" etiketini desteklemeyen tarayıcılarda görüntülenir.

```
<audio controls="controls">
    <source src="Audio Files/Noot-noot.ogg" type="audio/ogg" />
    <source src="Audio Files/Noot noot.mp3" type=".mpeg" />
    Tarayıcınız audio etiketini desteklemiyor.
  </audio>
```

* "controls" = HTML "audio" etiketi controls özelliği ses dosyası için çalma, durdurma, ses ayarlama vb. kontrolleri ekler.

* "source" = HTML "source" etiketi ses dosyası için dosya kaynağı belirler. Tarayıcı bu kaynaklardan desteklediği dosya kaynağını açar.

* "footer" =  Web sitelerinin alt kısmında yer alan hakkımızda, iletişim, alıntı yapma şartları vb. notların bulunduğu kısma footer ismi verilir.

```
<footer>Copyright © 2022</footer>
```


## Kaynakça

*[Patika.dev](https://app.patika.dev/courses/html/en-cok-kullanilan-html-etiketleri-nelerdir)

*[HTML Ses Ekleme](https://www.yusufsezer.com.tr/html-ses-ekleme/)
