# Başlıklar

Yazımıza başlık eklemek için **\#** karakterini kullanacağız. \# karakterinin sayısı, başlığımızın seviyesini belirleyecek. Aşağıdaki tabloda kullanabileceğimiz başlık seviyelerini bir görelim:

|Markdown|HTML|
|---|---|
|`# Seviye 1`|`<h1>Seviye 1</h1>`|
|`## Seviye 2`|`<h2>Seviye 2</h2>`|
|`### Seviye 3`|`<h3>Seviye 3</h3>`|
|`#### Seviye 4`|`<h4>Seviye 4</h4>`|
|`##### Seviye 5`|`<h5>Seviye 5</h5>`|
|`###### Seviye 6`|`<h6>Seviye 6</h6>`|

> ###### Not
>
> Oluşturduğunuz başlıktan sonra gelecek olan satır, başlık satırının altına yazılamaz. Mutlaka bir satır boş bırakılmalıdır. Bunu alışkanlık haline getirebilmek için eklenen her başlıktan sonra iki kez **Enter** tuşuna basılmalı ve boş satır oluşturulmalıdır.

Şimdi biraz örnek yapalım:

##### Markdown

```markdown
# ben birinci seviye bir başlığım

Ben de arkasından gelen metinim.
```

##### HTML

```html
<h1>ben birinci seviye bir başlığım</h1>
<p>Ben de arkasından gelen metinim.</p>
```

##### Çıktı

-----

<h1>ben birinci seviye bir başlığım</h1>
<p>Ben de arkasından gelen metinim.</p>

-----

> ###### Not 
>
> Başlık yapacağınız ibareden önce, tıpkı sonrasında olduğı gibi bir satır boş olmalı.

##### Markdown
```markdown
Ben başlıktan önceki paragrafım.

### Ben de üçüncü seviye bir başlığım

Ben de başlığın ardından gelen paragrafım.
```

##### HTML

```html
<p>Ben başlıktan önceki paragrafım.</p>
<h3>Ben de üçüncü seviye bir başlığım</h3>
<p>Ben de başlığın ardından gelen paragrafım.</p>
```

##### Çıktı

-----

<p>Ben başlıktan önceki paragrafım.</p>
<h3>Ben de üçüncü seviye bir başlığım</h3>
<p>Ben de başlığın ardından gelen paragrafım.</p>

-----

## Klasik Başlıklar

Eğer yazdığımız satırın hemen altına en az üç adet **=** koyarsak birinci seviye, **-** koyarsak ise ikinci seviye başlık olur.

Örneğimizle bunu bir anlayalım:

##### Markdown

```markdown
Bu birinci seviye başlık
===

Bu da ikinci seviye başlık
---

Bu da başlıktan sonraki paragraf
```

##### HTML

```html
<h1>Bu birinci seviye başlık</h1>
<h2>Bu da ikinci seviye başlık</h2>
<p>Bu da başlıktan sonraki paragraf</p>
```

##### Çıktı

-----

<h1>Bu birinci seviye başlık</h1>
<h2>Bu da ikinci seviye başlık</h2>
<p>Bu da başlıktan sonraki paragraf</p>

-----

Son olarak gelin, tüm bu öğrendiklerimizle güzel ve işe yarar bir örnek yapalım ve başlıklar konusunu kapatalım:

##### Markdown

```markdown
# Yeni Bir Blog Yazmak
 
 Herkes her gün yazı yazmayı bekliyor, ilhamının gelmesini. Oysa ilham gelebilmesi için yapılması gerekenler, atılması gereken adımlar var:
 
## Odaklanmak
 
Yazı yazmak için odaklanmak şart fakat bunu nasıl yapacağını bilmeli insan. Öncelikle çevremizdeki gürültülerden ve dikkati bozacak her türlü durumdan kurtulmalıyız.

## Bir Anda Yazmaya Çalışmamak

Odaklanmak konusu hallolduktan sonra kendinizden bir anda on sayfa yazı yazmayı beklemeyin. Daha gidecek çok yolunuz, yapacak çok şeyiniz var. Yazmaya başladıktan sonra ne kadar erken sıkılmış olursanız olun, yazmayı o zaman bırakın ve tekrar yazasınız gelince devam edin çünkü yazamıyorsanız, boşuna çabalamanın manası yok.
 ```
 
 ##### HTML
 
 ```html
 <h1>Yeni Bir Blog Yazmak</h1>
<p>Herkes her gün yazı yazmayı bekliyor, ilhamının gelmesini. Oysa ilham gelebilmesi için yapılması gerekenler, atılması gereken adımlar var:</p>
<h2>Odaklanmak</h2>
<p>Yazı yazmak için odaklanmak şart fakat bunu nasıl yapacağını bilmeli insan. Öncelikle çevremizdeki gürültülerden ve dikkati bozacak her türlü durumdan kurtulmalıyız.</p>
<h2>Bir Anda Yazmaya Çalışmamak</h2>
<p>Odaklanmak konusu hallolduktan sonra kendinizden bir anda on sayfa yazı yazmayı beklemeyin. Daha gidecek çok yolunuz, yapacak çok şeyiniz var. Yazmaya başladıktan sonra ne kadar erken sıkılmış olursanız olun, yazmayı o zaman bırakın ve tekrar yazasınız gelince devam edin çünkü yazamıyorsanız, boşuna çabalamanın manası yok.</p>
 ```
 
 ##### Çıktı

-----
 
 <h1>Yeni Bir Blog Yazmak</h1>
<p>Herkes her gün yazı yazmayı bekliyor, ilhamının gelmesini. Oysa ilham gelebilmesi için yapılması gerekenler, atılması gereken adımlar var:</p>
<h2>Odaklanmak</h2>
<p>Yazı yazmak için odaklanmak şart fakat bunu nasıl yapacağını bilmeli insan. Öncelikle çevremizdeki gürültülerden ve dikkati bozacak her türlü durumdan kurtulmalıyız.</p>
<h2>Bir Anda Yazmaya Çalışmamak</h2>
<p>Odaklanmak konusu hallolduktan sonra kendinizden bir anda on sayfa yazı yazmayı beklemeyin. Daha gidecek çok yolunuz, yapacak çok şeyiniz var. Yazmaya başladıktan sonra ne kadar erken sıkılmış olursanız olun, yazmayı o zaman bırakın ve tekrar yazasınız gelince devam edin çünkü yazamıyorsanız, boşuna çabalamanın manası yok.</p>

-----