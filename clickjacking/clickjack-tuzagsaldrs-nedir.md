# Clickjack Tuzagı Saldırısı Nedir

Bu tür bir saldırı kötü niyetli site bir kullanıcıyı gizli bir çerçeveye \( frame \)
veya **iframe**'e yükledikleri başka bir sitenin gizli bir öğesine tıklamaya
zorladığında oluşur.

## Clickjack Tuzağına Bir Örnek

Bir online mağazanın \( Örneğin yemek sepeti \), oturum açmış bir kullanıcının bir öğeyi
satın almak için **Şimdi Satın Al** düğmesini tıklayabileceği bir sayfa olduğunu
varsayalım. Bir kullanıcı kolaylık sağlamak için her zaman mağazada giriş yapılmış bir
şekilde kalmayı tercih eder. Saldırgan bir site, kendi sayfalarından birinde bir **Araba
kazandınız lütfen tıklayın** veya anlamsız gibi görünen bir düğme oluşturabilir ve
mağazanın sayfasını, "Şimdi Satın Al" düğmesinin görünmeden üst üste **Araba kazandınız
lütfen tıklayın** düğmesine basacak şekilde şeffaf bir iframe içine yerleştirebilir.
Kullanıcı saldırganın sitesini ziyaret ederse, **Araba kazandınız** gibi bir seçeneğine
tıklamak, **Şimdi Satın Al** düğmesini yanlışlıkla tıklatmaya ve öğeyi bilmediğiniz bir
satın almaya neden olabilir
