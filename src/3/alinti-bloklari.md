# Alıntı Blokları

Yazdığımız yazılarda alıntılar yapmamız gerektiği zamanlarda bunları **alıntı bloğu** içinde gösteririz ki okurken onun bize değil, kaynak aldığımız kişiye ait olduğunu fark edebilelim. Gelin bu bölümde bunun nasıl yapıldığına bakalım.

Alıntılamak istediğimiz metnin başına bir adet **büyüktür** `>` işareti koyar ve bir boşluk bırakırız. Bundan sonra yazacağımız her şey, biz yeni satıra geçene kadar **alıntı bloğu** ile vurgulanmış olur. Eğer `Enter` tuşuyla alt satıra geçersek söz konusu blok artık biter. Tıpkı paragraflarda olduğu gibi blok ile işimiz bittiğinde iki kez `Enter` tuşuna basarak yeni paragrafa geçmeyi alışkanlık hâline getirmeliyiz.

Gelin bir örnek yapalım ve **alıntı bloğu** neymiş, bir görelim:

##### Markdown

```markdown
> "En hakiki mürşit ilimdir, fendir." M. Kemal ATATÜRK
```

##### HTML

```html
<blockquote>
<p>&quot;En hakiki mürşit ilimdir, fendir.&quot; M. Kemal ATATÜRK</p>
</blockquote>
```

##### Çıktı

-----

<blockquote>
<p>&quot;En hakiki mürşit ilimdir, fendir.&quot; M. Kemal ATATÜRK</p>
</blockquote>

-----

## Alıntı Bloklarında Birden Çok Paragraf Kullanmak

Bazen, alıntılamak istediğimiz metin bir cümleden daha fazlasıdır. Örneğin kitabın bir bölümü, birkaç paragraflık konuşma gibi; alıntıladığımız metin biraz daha geniş olabilir.

Bu genişliği karşılayabilmek için **alıntı bloğu** kullanımımızı da genişletmemiz gerekir. Bunu şu şekilde yaparız:

Önce **büyüktür** işareti ile alıntı bloğuna başlarız. Yazımızı yazar ve yeni bir paragraf için `enter` tuşuna bir defa basarız. Daha sonra bir adet **büyüktür** koyar ve ikinci `enter` tuşuna da basarız. Ardından tekrar **büyüktür** koyar ve bir boşluk bırakarak ikinci paragrafımızı da yazarız.

Bu biraz karmaşık oldu. Bu yüzden hemen örnek geliyor:

##### Markdown

```markdown
> Bu birinci paragraf.
>
> Bu da ikinci paragraf.
```

##### HTML

```html
<blockquote>
<p>Bu birinci paragraf.</p>
<p>Bu da ikinci paragraf.</p>
</blockquote>
```

##### Çıktı

-----

<blockquote>
<p>Bu birinci paragraf.</p>
<p>Bu da ikinci paragraf.</p>
</blockquote>

-----

> ###### Not
>
> Alıntı bloklarının içinde sonraki derslerde öğreneceğiniz elemanların tamamını kullanabilirsiniz.

## İç İçe Alıntı Blokları Kullanma

Hani bir önceki konumuzda bahsetmiştik ya, hem **altı çizili** hem **koyu** olmasını isteyenlerden? Burada da onlara hitap eden bir kullanım söz konusu.

Yazarın cümlesini alıntı bloğuna, yazarın ismini de daha derin alıntı bloğuna almak isteyenler için gelin bunun nasıl yapıldığına bir bakalım:

Yine **büyüktür** işaretini koyup bir boşluk bırakarak ilk bloğumuzu yazalım. Ardından bir kez `enter` tuşuna basarak bir alt satıra geçelim. Bir adet daha **büyüktür** işareti koyup `enter` tuşuna basalım. Derin alıntı bloğu için ise yan yana iki adet **büyüktür** koyup bir boşluk verelim ve derin blokta olmasını istediğimiz ibareyi yazalım.

Bunun nasıl olduğunu daha somut görebilmek için işte size bir örnek:

##### Markdown

```markdown
> En hakiki mürşit ilimdir, fendir.
>
>> M. Kemal ATATÜRK
```

##### HTML

```html
<blockquote>
<p>En hakiki mürşit ilimdir, fendir.</p>
<blockquote>
<p>M. Kemal ATATÜRK</p>
</blockquote>
</blockquote>

```

##### Çıktı

-----

<blockquote>
<p>En hakiki mürşit ilimdir, fendir.</p>
<blockquote>
<p>M. Kemal ATATÜRK</p>
</blockquote>
</blockquote>

-----
