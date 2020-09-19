# Vurgulamalar

Yazılarımızda önemli yerleri vurgulamak isteriz. Altını çizmek, koyu ve italik yapmak genelde bizim ihtiyaçlarımızı karşılar. Gelin bunun nasıl yapılacağını adım adım öğrenelim.

## Altı Çizili Yapmak

Bir metinde altını çizmek istediğimiz ibarenin başına bir adet **alt çizgi** `_` ya da bir adet **yıldız** `*` koyarız. Daha sonra altı çizili kısmın bittiği yerin sonuna da bir adet **alt çizgi** ya da **yıldız** koyarak işlemi tamamlarız. Aşağıdaki örneği inceleyelim:

##### Markdown

```markdown
Aşağıdaki cümlelerin hangisinde deyim, anlamıyla _yanlış_ eşleştirilmiştir?
```

##### HTML

```html
<p>Aşağıdaki cümlelerin hangisinde deyim, anlamıyla <em>yanlış</em> eşleştirilmiştir?</p>
```

##### Çıktı

-----

<p>Aşağıdaki cümlelerin hangisinde deyim, anlamıyla <em>yanlış</em> eşleştirilmiştir?</p>

-----

## Koyu Yapmak

Aynı şekilde, metni koyu yapabilmek için de **yıldız** `*` ya da **alt çizgi** `_` karakterini kullanırız. Fakat burada dikkat etmemiz gereken nokta, bu sefer birer tane değil ikişer tane kullanmalıyız. Örnek geliyor:

##### Markdown

```markdown
Yazar, yukarıdaki cümleyle neyi anlatmak __istiyor__ olabilir?
```

##### HTML

```html
<p>Yazar, yukarıdaki cümleyle neyi anlatmak <strong>istiyor</strong> olabilir?</p>
```

##### Çıktı

-----

<p>Yazar, yukarıdaki cümleyle neyi anlatmak <strong>istiyor</strong> olabilir?</p>

-----

> ###### Not
>
> Eğer işleme alt çizgi ile başlamışsanız, bitirirken de alt çizgiyi kullanmalısınız. Örneğin `Benim adım __Ela**` şeklinde bir kullanım uygularsanız, sonucunuz hatalı olacaktır. Doğrusu `Benim adım __Ela__` şeklinde olmalı.

## Hem Koyu Hem Altı Çizili Yapmak

Bazen düzeni o kadar abartırız ki, metinlerimizdeki bazı ibarelerin hem koyu hem altının çizili olması gibi biraz tuhaf isteklerimiz olabilir. **Markdown**, bu konuda da isteklerimizi karşılıyor ve bizi bir kez daha kendisine hayran bırakıyor. Gelin bunun nasıl yapıldığına bir bakalım:

Bunu yapabilmek için metnin hem koyu hem de altı çizili olmasını istediğimiz yerin başına üç adet **yıldız** ya da üç adet **alt çizgi** koyarız. İşlemi bitirmek için ise aynı işlemi tekrarlarız. Yani ya üç adet **yıldız**, ya da üç adet **alt çizgi**.

> ###### Not
>
> Eğer üç adet **yıldız** ile başlamışsak mutlaka **yıldız ile bitirmeliyiz. Bu kural **alt çizgi** ile kullanım için de geçerli tabii ki. Eğer üç adet **alt çizgi** kullanmışsak, bitirirken de aynısını yapmalıyız.

Gelin artık örneğimize geçelim:

##### Markdown

```markdown
Kullanım kolaylığı bakımından en rahat olan akıllı cihazları ***Apple*** üretmektedir.
```

##### HTML

```html
<p>Kullanım kolaylığı bakımından en rahat olan akıllı cihazları <strong><em>Apple</em></strong> üretmektedir.</p>
```

##### Çıktı

-----

<p>Kullanım kolaylığı bakımından en rahat olan akıllı cihazları <strong><em>Apple</em></strong> üretmektedir.</p>

-----
