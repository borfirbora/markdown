# Markdown Nedir?

Markdown, John Gruber ve arkadaşları tarafından geliştirilmiş bir işaretleme dilidir. Tanımı biraz daha açmamız gerekirse Markdown, düz yazı içerisinde belirli karakterleri kullanarak söz konusu kısmı biçimlendirmeye ya da nitelemeye yarayan bir yazım şeklidir, diyebiliriz.

İlk önceleri e-posta yazmak amacıyla kullanılmaya başlanmış olsa da kullanım kolaylığı ve taşınabilirliği onu son derece basit fakat önemli bir araç haline getirmiştir.

## Markdown Ne Değildir?

Markdown kesinlikle bir programlama dili ya da HTML gibi bir yordam dili değildir. Markdown'un temel amacı, yazıldıktan sonra farklı araçlar kullanılarak istenilen belgeye rahatlıkla dönüşümünü sağlayabilmektir.

Markdown ile yazılan belge istenilen her formata dökülebilmektedir. Bunu ilerleyen konularda detaylıca göreceğiz.

## Markdown Nasıl Çalışır?

Siz istediğiniz gibi metninizi düzenlersiniz, kullandığınız uygulama düzenlediğiniz metni yorumlar ve size çıktı üretir. Bunu güzel bir tablo üzerinde inceleyelim ve adımları tek tek görelim:

|Adım|Yapılacak|Açıklama|
|---|---|---|
|1.|Not Defteri editöründe Markdown kullanarak yazınızı .md formatında yazarsınız.|Ben genelde Notepad++ kullanıyorum|
|2.|Yazdığınız .md uzantılı dosyayı Pandoc komut istemini kullanarak istediğiniz formata dökersiniz|Bu konuya ileriki bölümlerde detaylı olarak değineceğiz ama basit bir kod örneği isterseniz `pandoc belge.md -f markdown -t html -s -o belge.html` kodunu örnek olarak alabilirsiniz.|

Gelin bir sonraki konuya geçelim ve Markdown için kurulabilecek yazılımlara bir göz atalım.