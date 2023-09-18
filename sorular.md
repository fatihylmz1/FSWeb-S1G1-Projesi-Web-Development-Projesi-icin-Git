# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Versiyon kontrol sistemini sağlayan bir kontrol mekanizmasıdır.

2. Git ile GitHub arasında ne fark var?

Git bir kontrol mekanizmasıdır , GitHub ise bu kontrol mekanizmasını kullanan kar amacı güden bir şirkettir.

3. Neden bir branch oluşturuyoruz?

Master kodumuzda yapmak istediğimiz değişiklikleri ya da varolan hataları düzeltmek amacıyla ve master kodun yapısını bozmadan bu işlemleri yapabilmek için master kodumuzun bir kopyası olarak üzerinde oynama yapabileceğimiz ama merge işlemi yapmadığımız takdirde master kodu etkilemeyecek bir branch oluştururuz.

4. Pull Request'in amacı nedir?

Bir projede değişiklik yapmak isteyen kullanıcının, bu değişiklikleri yapabilmeyi proje sahibinden talep etmesidir. Aynı zamanda yapılan değişikliğin herkes tarafından görülmesini sağlar. Bu sayede aynı kod blokları üzerinde değişiklik yapan yazılımcıların diğer değişikliklerden haberi olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout main kodu ile main branch'ine geçiş yapabilirim.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch ve git pull komutları uzak sunucudan veri çekmemizi sağlar, ama aralarındaki fark git fetch komutu getirilen veriler ile local bilgisayarımızdaki veriler aynı olduğunda elimizdeki verilerin üzerine yazmaz, get pull komutu ise uzaktan çektiğimiz komutlar ile localdeki komutları eşleştirerek aynı olmasını sağlar. git merge kodu ise başka bir branch'deki kodu kendi branch'imize almamızı sağlar.

7. Merge conflict nedir?

Aynı kod üzerinde çalışan iki kişi aynı dosyayı ve aynı satırı değiştirirse merge conflict yani çakışma olur.

8. Merge conflict'i nasıl çözeriz?

Git bu conflict'leri otomatik olarak çözmeye çalışır, ama çözemezse bu kodu yazan kişiye bildirilir ve bu çakışmanın manuel olarak çözülmesi gerekir.

