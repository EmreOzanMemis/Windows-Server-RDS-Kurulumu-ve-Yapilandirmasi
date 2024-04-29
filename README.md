# Windows Server RDS Kurulumu ve Yapilandirmasi
<div><span style="font-size: 12pt; font-family: 'Times New Roman';">Windows Server 2012R2 kurulum ve yapılandırmalarınızı tamamlayın ve tüm Windows güncellemelerinin yüklü olduğundan emin olunuz.
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Server Manager
        </strong>açınız. <strong>Dashboard </strong>penceresinde <strong>Welcome To Server Manager
        </strong>altında bulunan <strong>Add roles and features </strong>menüsüne tıklayınız.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu1.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Add roles and features wizard
        </strong>penceresinde <strong>before you begin </strong>adımında <strong>next </strong>
        butonuna basarak devam ediniz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu2.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Add roles and features wizard
        </strong>penceresi <strong>Installation Type </strong>adımında <strong>Role-based or feature-based installation
        </strong>seçeneğini işaretliyoruz. </span><span style="font-size: 12pt; font-family: 'Times New Roman';">Not:
        <strong>Remote Desktop Service installation </strong>seçeneği kurulumu AD DS gerektirmektedir. Daha da detaylamak gerekirse RDS kurulumu için bir domain controllera login olmuş bir sunucu olması gerekiyor. Bu servis kurulumunda uzak erişim dışında uzak uygulama
        erişimi ve RDS ile gelen bir çok yeni özelliği kullanabiliyorsunuz. Biz bu kurulumumuzda eski adı ile terminal server olarak bilinen yapıya istinaden tek sunucu üzerine Remote Desktep Session Host role kurulumunu gerçekleştireceğiz. İsimlerin kısaltması çok
        yakın olduğu için karıştırılmaktadır. Bu sebeple bu detayları sizlerle paylaşmak istedim.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu3.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Server Selection
        </strong>adımında <strong>Select a server from the server pool </strong>seçili bırakıyor ve
        <strong>Remote Desktop Session </strong>kurmak istediğimiz sunucumuzu seçiyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu4.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Server Roles
        </strong>adımında <strong>Remote Desktop Service </strong>rolünü seçiyoruz. <strong>
        Next </strong>butonuna basıyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu5.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Features
        </strong>adımında bir değişiklik yapmadan <strong>Next </strong>butonuna basarak devam ediyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu6.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Remote Desktop Services
        </strong>adımında <strong>Next </strong>butonuna basıyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu7.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Role Services
        </strong>adımında sizlere not bölümünde belirttiğim ayrımı burada daha iyi gösterebiliyor olacağım. Amacımız Terminal server gibi kullanmak ise bu rol kurulumunda iki servisi seçiyoruz. Birincisi
        <strong>Remote Desktop Licensing </strong>ikincisi ise <strong>Remote Desktop Session Host
        </strong>bu iki servis kullanım amacımız için yeterlidir. <strong>Next </strong>butonuna basarak devam ediyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu8.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Son adımımız olan
        <strong>Confirmation </strong>adımında yüklemek istediğimiz role ve detaylarını kontrol ediyor. Üst bölümde bulunan
        <strong>Restart the destination server automatically if required </strong>seçeneğini işaretliyoruz. Role kurulumu sonrası sistem restart gereksinimi duyar ise bu seçenek sayesinde kurulum sonrası restart otomatik gerçekleşecektir.
        <strong>Install </strong>butonuna basarak kurulumu başlatıyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu9.png"><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Kurulum birkaç dakika sürecek ve otomatik sistem restart edecektir. Bilginiz olsun.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu10.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Kurulum tamamlanıp sisteme login olduğunuzda Windows sağ alt köşeden bir pop-up ile bir uyarı verecek.
        <strong>Remote Desktop licensing mode is not configured </strong>şeklinde bu uyarı gerekli lisans yapılandırmasının yapılmadığını ve denem süreci olan 119 günün başladığını göstermektedir. 119 gün sonra demo lisans son bulacak ve Remote Desktop Service leri
        durdurulacak. Temel olarak kurulumumuz tamamlandı. Şimdi lisans yapılandırmamızı yapacağız.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu11.png"><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Lisans yapılandırması için önce Powershell açıp aşağıdaki kodları uyguluyoruz. GUI ile bu işlemleri yapmanızı tavsiye etmem powershell ile çok kısa sürede bu işlemleri tamamlayabilirsiniz.
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';">Administrator olarak powershell çalıştırıyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu12.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Açılan Powershell penceresine ilk olarak aşağıda belirttiğim kodu yazıyor yada yapıştırıyoruz. Enter basıp kodumuzu çalıştıryoruz. Bu kod ile sunucu üzerinde ki terminal servisimizi aktif ediyoruz.
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em>$obj = gwmi -namespace "Root/CIMV2/TerminalServices" Win32_TerminalServiceSetting</em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em></em></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu13.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">İkinci olarak lisansımızın türüne göre belirleyeceğimiz kodumuzu gireceğiz ancak burada önemli bir notumuz var lisansımız cihaz bazlı ise 2 kullanıcı bazlı ise 4 yazmamız gerekiyor. Ben testlerde
        kullanıcı bazlı test yaptığım için 4 yazacağım. Sonrasında Enter basıp devam edeceğim.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em>$obj.ChangeMode(value)</em>
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Not: Value yazan yere cihaz bazlı ise 2, Kullanıcı bazlı ise 4 yazıyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu14.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Üçüncü komutum hangi server üzerinde lisans aktivasyonu yapacağımı belirliyorum
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em>$obj.SetSpecifiedLicenseServerList("LicServer")
        <br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em></em></span><span style="font-size: 12pt; font-family: 'Times New Roman';">LicServer yazan yere localhost yazıyorum.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu15.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Son olarak aşağıdaki komutu çalıştırarak sonuçladırıyoruz. Bu bölümde yaptığımzı işlemleri kontrol ediyoruz.
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em>$obj.GetSpecifiedLicenseServerList()</em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><em><br>
        </em></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu16.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';">İ</span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">İşlemlerimiz tamamdır. Şimdi lisans aktivasyonu için licmgr.exe çalıştırıyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu17.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>licmgr.exe
        </strong>çalıştırdıktan sonra <strong>RD licensing Manager </strong>penceresi açılacaktır.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu18.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>RD licensing Manager
        </strong>üzerinde serverımızı seçerek sağ tıklıyoruz ve <strong>Activete Server </strong>
        butonuna tıklıyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu19.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Activate Server Wizard
        </strong>penceresinde ilk bilgilendirme ekranı sonrası <strong>Next </strong>butonuna basarak devam ediyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu20.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Activate Server Wizard pencremizin ikinci adımında
        <strong>Connection method </strong>seçiyoruz. <strong>Automatic connection </strong>
        seçiyoruz. Önerilen seçenek otomatik bağlantıdır. <strong>Next </strong>butonuna basarak devam ediyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu21.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Company Information
        </strong>adımında bilgilerimizi doldurup <strong>next </strong>butonuna basıyoruz.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu22.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Company Information in ikinci adımı opsiyonel olduğu için direk
        <strong>Next </strong>butonuna basarak devam ediyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu23.png"><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Completing the Activate Server Wizard
        </strong>adımını göreceksiniz. <strong>Start Install Licenses Wizard now </strong>
        seçeneği işaretli olduğundan emin olun bu adım sonrası lisansımızı aktif edeceğiz.
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu24.png"></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Welcome to the Install Licenses Wizard
        </strong>penceremiz açılacaktır. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu25.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>License Program
        </strong>belirliyoruz. Lisans tipinizi hangi programa dahil ise onu seçiyoruz. Service Provider anlaşmamız olduğu için ve test amaçlı SPLA seçeneğini seçiyorum.
        <strong>Next </strong>butonuna basarak devam ediyorum. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu26.png"><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">License Program ikinci adımında SPLA Agreement number mizin girmemizi istiyor girerek
        <strong>Next </strong>butonuna basıyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu27.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>Product Version and License Type
        </strong>adımında <strong>product version </strong>ve <strong>license type </strong>
        seçip <strong>quantity </strong>sini belirliyoruz. </span><span style="font-size: 12pt; font-family: 'Times New Roman';">Kurulum yaptığım işletim sistemi Windows Server 2012 R2 olduğu için Product version olarak işletim sistemimi Windows Server 2012 olarak seçiyorum
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';">Licence type bölümünde kullanıcı bazlı lisanslama yapacağım için per user cal seçeneğini seçiyorum.
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';">Quantity bölümüne de kaç kullanıcı için lisans tanımlayacaksam onun sayısını yazıyorum test için 5 kullanıcı belirliyorum.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu28.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Completing the Install Licenses Wizard adımını gördüğünüzde lisans işleminiz başarı ile tamamlanmıştır. Finish butonuna basabilirsiniz. Lisansımız başarı ile tanımlanmıştır.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu29.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';">Kontrol etmek için
        <strong>RD Licensing Diagnoser </strong>çalıştırıyoruz. <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu30.png"><span style="font-size: 12pt; font-family: 'Times New Roman';">
        </span><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong><br>
        </strong></span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><strong>RD Licensing Diagnoser
        </strong>pencresi açıldığında lisansın ve servislerin özetini göreceksiniz. Orta bölümde bulunan information bölümünde herhangi bir uyarı olmadığını göreceksiniz. RDS lisansımız başarı ile tanımlanmıştır.
        <br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"><br>
        </span></div>
        <div><span style="font-size: 12pt; font-family: 'Times New Roman';"></span><img alt="" src="https://www.emreozanmemis.com/wp-content/uploads/2019/01/013119_1823_RDSKurulumu31.png"></div>
