# Paragraflar

Paragraf oluşturabilmek, Markdown'daki en basit sözdizimidir. Paragrafı oluşturan cümle topluluklarının öncesinde ve  sonrasında birer satır  boşluk varsa bu, söz konusu cümlelerin paragraf olduğu anlamına gelir.

Bir örnekle bunu hemen görelim:

##### Markdown

```markdown
Bu birinci paragraf

Bu da ikinci paragraf.

Bu da üçüncü ve son paragraf
```

##### HTML 

```html
<p>Bu birinci paragraf</p>
<p>Bu da ikinci paragraf.</p>
<p>Bu da üçüncü ve son paragraf</p>
```

##### Çıktı

-----

<p>Bu birinci paragraf</p>
<p>Bu da ikinci paragraf.</p>
<p>Bu da üçüncü ve son paragraf</p>

-----

> ###### Not
>
> * Başlık, alıntı bloğu ve ya liste gibi bir işaretle başlamıyorsa belgenin ilk satırı da paragraf başlangıcı olarak kabul edilir.
> * Paragraflarda iç içe paragraf diye bir şey söz konusu değildir.

## Yeni Satıra Geçmek

Bazen şiir gibi metinlerimizde paragraflar yerine bir alt satıra geçmek isteyebiliriz. Bu durumda yapmamız gereken, satırın bitmesini istediğimiz yerde iki ya da ikiden fazla _boşluk_ bırakmaktır. Hemen bunu bir örnekle görelim:

##### Markdown

```markdown
Birinci mısra,  
İkinci mısra,  
Üçüncü mısra,  
Dördüncü mısra.
```

##### HTML

```html
<p>Birinci mısra,<br />
İkinci mısra,<br />
Üçüncü mısra,<br />
Dördüncü mısra.</p>

```

##### Çıktı

-----

<p>Birinci mısra,<br />
İkinci mısra,<br />
Üçüncü mısra,<br />
Dördüncü mısra.</p>

-----
