Projeyi görüntülemek için [bu bağlantıya](https://abdulkadir-erdeger.github.io/create-xapi-url/) tıklayın.

# URL Üretici Arayüz

Bu proje, kullanıcıların çeşitli bilgileri girerek URL'ler oluşturmasını sağlayan bir web arayüzü sunar. HTML, CSS (Bootstrap) ve JavaScript kullanılarak hazırlanmıştır.

## Özellikler

- **Temel URL**: Kullanıcının girmesi gereken ana URL.
- **Endpoint**: API veya başka bir endpoint için URL parçası.
- **Key**: Yetkilendirme için gerekli anahtar.
- **Secret**: Yetkilendirme için gerekli şifre.
- **Actor**: JSON formatında isim ve e-posta adresi içeren bir aktör objesi.

Kullanıcı, bu bilgileri girdikten sonra, uygulama tarafından oluşturulan URL, sayfada bir input alanında görüntülenir.

## Kurulum ve Kullanım

### 1. Gereksinimler

- Modern bir web tarayıcısı (Chrome, Firefox, vb.)
- İnternet bağlantısı (Bootstrap ve diğer kütüphaneler için)

### 2. HTML Dosyasını Açma

Projenizi kullanmaya başlamak için aşağıdaki adımları izleyin:

1. **Dosyayı Tarayıcıda Açın**: `index.html` dosyasını bir web tarayıcısında açarak arayüzü görüntüleyebilir ve kullanabilirsiniz.

### Kullanım Talimatları

1. **Gerekli Bilgileri Girin**: Form alanlarına aşağıdaki bilgileri girin:

   - **Base URL**: Temel URL (örneğin, yerel dosya yolu veya ana URL).
   - **Endpoint**: API veya hizmet URL’sinin son kısmı.
   - **Key**: Yetkilendirme için gerekli anahtar.
   - **Secret**: Yetkilendirme için gerekli şifre.
   - **Actor Name**: Aktörün adı.
   - **Actor Mbox**: Aktörün e-posta adresi (eğer `mailto:` ile başlamıyorsa otomatik olarak eklenecektir).

2. **URL'yi Üretin**: "Generate URL" butonuna tıklayarak belirtilen bilgilerle oluşturulan URL'yi görüntüleyin. URL, formun altında bulunan `Generated URL` alanında gösterilecektir.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakabilirsiniz.
