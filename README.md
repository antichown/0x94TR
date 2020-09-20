
# 0x94TR

- Burp version<br>
- Windows version (does not require burp - Burp gerektirmiyor)<br>
- Linux version (does not require burp - Burp gerektirmiyor)<br><br>

# 0x94TR Burp version<br>
Command Injection<br>
Blind Command Injection<br>
Template Injection<br>
Code Injection<br>
Local Fıle Inclusion<br>
SSI Injection<br>
Open Redirect<br>
SSRF<br>
Arbitrary File Download<br>
-----------

<img src="https://raw.githubusercontent.com/antichown/0x94TR/master/watch.gif">
-----------
<img src="https://raw.githubusercontent.com/antichown/0x94TR/master/watch2.gif">

-------------
#Install
-----------------------------
<img src="https://raw.githubusercontent.com/antichown/0x94TR/master/94_1.png">

---------------------------------

<img src="https://raw.githubusercontent.com/antichown/0x94TR/master/94_2.png">
---------------------------------

<img src="https://raw.githubusercontent.com/antichown/0x94TR/master/94_3.png">

# 0x94TR - Python version (does not require burp - Burp gerektirmiyor)
Taramak istemediginiz ozelligi config.cfg dosyasında True yazan yerleri False yaparak devre dışı bırakabilirsiniz<br>

Programdaki başlıca özellikler :<br>

Sunucu IP adresi ve kullanılan protocol bilgisini alir<br>
Sunucunun Allow Header listesini alır<br>
Seo yada 302 yonlendirmeli linklerin location URL lerini alır<br>
Sitedeki tüm linkleri 3 farklı crawl yöntemiyle tamamen alır (Örümcek misali sitedeki tüm linkleri gezer)<br>
Tüm sitede Expression Language Injection dener.<br>
Tüm sitede HTTP Response Splitting<br>
Tüm sitede SSI(Server-Side Includes) açıklarını dener<br>
Tüm GET ve POST verilerinde Blind LDAP injection dener<br>
Tüm GET ve POST verilerinde Blind XPATH injection dener<br>
Tüm GET ve POST verilerinde Remote Command Execution dener<br>
Tüm GET ve POST verilerinde Blind Command injection dener<br>
Tüm GET ve POST verilerinde SQL injection dener<br>
Tüm GET ve POST verilerinde Blind SQL injection dener<br><br>
Tüm GET ve POST verilerinde Time Based SQL injection dener<br>
Tüm GET ve POST verilerinde Header injection dener<br>
Tüm GET ve POST verilerinde Cross-Site Scripting(XSS) dener(noscript olup olmadiğini belirtir)<br>
Tüm GET ve POST verilerinde Command injection dener<br><br><br>
Tüm GET ve POST verilerinde Frame injection dener<br><br>
Tüm Sitede Local File Inclusion denemesi yapar.<br>
Http Trace Cross-Site Scripting açığını test eder<br>
Tüm linklerde Header Crlf injection dener<br>
Bulduğu site içi tüm linklerde login sayfalarini otomatik bulup basit capli brute force gerçekleştirir.<br>
Wordpress yada Joomla siteleri tespit eder.<br>
Tomcat kullanan siteyi tespit edip, default password denemesi yapar.<br>
Joomla token açığını otomatik dener<br>
Gezdiği tüm linklerde ajax ile veri gönderimi yapan URL leri tespit eder<br>
Gezdiği tüm linklerde geçen emailleri otomatik alır<br>
Çalışmayan(Kodları gözüken) PHP ve ASP kodlarının olduğu sayfaları tespit eder.<br>
Gezdiği tüm linklerde OPEN Redirect açığı olup olmadığını kontrol eder<br>
Gezdiği tüm linklerde bir alt dizine inip index Of olup olmadığını kontrol eder<br>
Gezdiği tüm linklerde FRAME,Javascript,CSS kontrolü yapar.<br>
Aspx siteler için Custom Error dosyası analizi yapar<br>
Aspx siteler için Elmah Error Log dosyası analizi yapar<br>
Aspx siteler için Aspx Trace Information analizi yapar<br>
Cold Fusion siteler için dizin taraması ve panel taraması yapar<br>
Gezdiği tüm sitelerde bulunan dizinlerde aynı zamanda CSS ve Javascript dizinlerinde Shell taraması yapar<br>
Gezdiği tüm linklerin yedek dosyası kontrolünü yapar<br>
Site içerisindeki tüm dizinlerde yedeklenmiş dosya yada bilgi dosyaları (rar,zip,tar,tar.gz,txt,sql) kontrolü yapar<br>
Site içerisinde dosya upload izni olan sayfaları bulur<br>
ShellShock açığını test eder<br>
Apache Struts açığını test eder<br>
SEF url sistemi olan sitelerde SEF url adreslerine göre çoklu Cross-Site Scripting(XSS) denemesi yapar.<br>
SEF url sistemi olan sitelerde SEF url adreslerine göre çoklu SQL injection denemesi yapar.<br>
Wordpress sitelerin belli başlı açıklarını otomatik dener<br>
Akıllı sistem mevcuttur(Form Sayfa içinde user,username,pass,password vb id yada name olarak tanıtılmışsa otomatik olarak basit çaplı brute force gerçekleştirir)<br>
Tüm dizinlerde belli başlı dosyalar olan phpinfo,install,db vb dosyalarını arar<br>
WS-FTP log dosyasını kontrol eder<br>
Nodejs proje dosyalarını kontrol eder<br>
Git proje dosyalarını kontrol eder<br>
Her dizinde Okumaya açık olan htaccess dosyalarını bulur<br>
ve daha bir çok özellik<br>
AYARLAR<br>

Javascript destekler.<br>
Asp.net ve Java siteler için ignoreparametre(taramaya dahil etme) özelliği ignoreparametre.txt den ayarlanabilir.<br>


Config.cfg dosyasından :<br>
Thread sayısı,<br>
Cookie ayarı (Login olupta işlem yapabilir),<br>
Proxy ayarı,<br>
ve birden fazla Request engelleyen siteler için Request bekleme limiti ayarlanabilir<br>

// Her yazılımda olduğu gibi, bu yazılımda da yanılma payı olabilir.Fakat elimden geldiğince exploit ederek açıkları tespit etmeye çalıştım. Yazılıma kendi bulma ve çalışma mantıklarımı sistematik şekilde entegre ettim.Aynı zamanda kolaylaştırmak için 10 küsür aracın da çalışma mantığını entegre ettim.Program çok iyidir diyemem çünkü programda eklemediğimiz halen bir çok şey mevcuttur. Onlarıda vakit buldukça geliştiriyoruz //<br>

SADECE Güvenlik testleri için kullanın<br>
Yazılımın oluşturacağı sorunlardan yazılımcı sorumlu değildir.<br>
Yazılımın oluşturacağı sorunlardan yazılımcı sorumlu değildir.<br>
Yazılımın oluşturacağı sorunlardan yazılımcı sorumlu değildir.<br>
All responsibility belongs to the user<br>
Tüm sorumluluk kullanıcıya aittir.<br>
TÜRK sitelerinde tarama yapmaz<br>

<img src="https://raw.githubusercontent.com/antichown/0x94TR/master/config.png">
<br>
<img src="https://raw.githubusercontent.com/antichown/0x94TR/master/ddd.png">


<a href="https://twitter.com/0x94">Twitter 0x94</a>
