Bir ekip AramaCubugu componentinin UI'ını hazırladı ve projeye ekledi. Biz de buna search özelliği ekleyerek aktive edeceğiz.

Bunun için App.jsx'de aramaKriter'i state'i var. AramaCubugu'na bu state'i ve yazacağımız bir change handler fonksiyonunu prop olarak iletmeli, AramaCubugu'nda da alıp kullanmalıyız.

[ ] Öncelikle, App.jsx'de input alanı için bir change handler fonksiyonu yazalım. Bu fonksiyon 3 şey yapmalı:

event'i almalı ve ilgili element'e erişip value değerini kullanabilmeli
input alanındaki metne göre aramaKriteri state'ini değiştirmeli
gönderiler state'ine ilgili verileri -aramaKriterine göre- sahteVeri'den alıp, aktarmalı. 
Çalışma dosyaları: src/App.jsx, src/components/AramaCubugu/AramaCubugu.jsx
