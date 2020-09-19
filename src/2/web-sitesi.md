# Web Sitesi

Bu konumuza bizzat benim kendi yazdığım bir yazıdan yapacağım bir alıntıyla başlamak istiyorum:

> Linux gibi ücretsiz dağıtımlar, Python gibi modern programlama dilleri, neredeyse sınırsız kaynaklar... İnsan nasıl olur da ortaya yeni teknolojik gelişmeler koymaz, inanın anlamıyorum.
>
> [Fırsatımız Var - BorfirBora.com](https://borfirbora.com/firsatimiz-var)

Php gibi Web tabanlı programlama dilleri, HTML gibi bir işaretleme dili varken.... Neden böyle bir şeye ihtiyaç duyulsun ki? Aslında tam da bu yüzden ihtiyaç var.

Herkes PHP dilini öğrenecek kadar programlama becerisine sahip olmayabilir. Herkes HTML dilinin tamamını bilmek zorunda da değil üstelik. Belki de amacımız sadece yazı yazmak ve yazarken de istediğimiz biçimlendirmeleri yerine getirmekten ibaret.

İşte burada devreye statik site oluşturucular giriyor. Sizler sadece Markdown ile yazılarınızı yazıyor, uygun klasöre yerleştiriyorsunuz ve gerisini site oluşturucusu yapıyor. Veritabanı ile uğraşmadan, sadece yazınızı yazıyorsunuz. tasarımı değiştirmek için bile yazılarınızı kaybetme korkusu da yok.

Düşünsenize, sadece basit bir blog sitesi açmak için Wordpress gibi bir CMS kullanırken, sırf tasarımı için kaç gününüzü harcıyorsunuz?

Ben de önceleri Web sitemi Wordpress altyapısında çalıştırıyordum. İstediğim her türlü tasarımı yapıyordum evet. Anket eklentileri, yorum paneli, etiket buludu... Wordpress'e bir güncelleme geliyordu ve benim en çok kullandığım anket eklentim, istenenleri karşılayamadığı için artık sayfamda çalışmıyordu. Ne kadar can sıkıcı değil mi?

Şimdiki [BorfirBora.com](https://borfirbora.com/) alanadına  sahip sitem artık Wordpress ile çalışmıyor. Hem sadece Markdown kullanarak yazıma odaklanabiliyoorum, hem de biliyor musunuz, Hosting için kesinlikle para ödemiyorum. Bunu nasıl mı yapıyorum? Gelin beraber şöyle bir bakalım:

## JEKYLL

Jekyll, Ruby programlama dili ile geliştirilmiş bir statik site oluşturucusudur. Amacı basitçe sizin Markdown dili ile yazdığınız içeriklerinizi statik bir Web sitesine dönüştürmektir. Bilgisayarınıza [JekyllRB.com](https://jekyllrb.com) sitesinden indireceğiniz Rubi dağıtım paketiyle kurabileceğiniz Jekyll, isterseniz ücretsiz olarak sizlere bir sunucu üzerinde verilebilir.

Dünyanın en önde gelen versiyon kontrol sistemmi olan Git teknolojisinin en çok kullanıldığı bir platform var. Evet, herkesin bildiği [Github](https://github.com/)'tan bahsediyorum. Bu platformda herkes istediği gibi özgür uygulamalar geliştirebiliyor. Peki bu bizim ne işimize yarayacak diye sorabilirsiniz ama okumaya devam edin.

Herkesin istediği dilde, istediği kadar kişiyle ortak çalışabilmesini sağlayan bu güzide platformun bir de [Github Pages](https://github.io) adında, yazılım geliştiricilerin geliştirdikleri yazılımlarını tanıtması amacıyla sunduğu bir Web alanı var. İşte bu Web alanı Jekyll altyapısıyla çalışıyor. Üstelik de kendi alanadınızı da yönlendirip, istediğiniz kadar kullanabiliyorsunuz.

Bu konuyla ilgili daha fazla billgiyi, [BorfirBora.com](https://borfirbora.com/) adresinde yer alan iletişim kısmından benimle iletişime geçerek edinebilirsiniz.

Açıkçası birden çok Jekyll benzeri otomatik site oluşturucusu var fakat ben Jekyll ile çalıştığım için kitabımızın bu kısmında sadece onu örnek verdim. Ufak olarak internette yapacağınız bir araştırma sizlere daha fazla bilgi verecektir şüphesiz.

Bir sonraki konumuza geçelim ve bakalım Markdown, daha ne amaçlar için kullanılıyormuş.