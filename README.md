# io.net Kurulumu ve "zsh: bad CPU type in executable" Hatasını Çözme (Apple Chip)

## Adım 1: Docker Desktop İndirme ve Kurulum

\* Docker Desktop web sitesine gidin: <a href="https://www.docker.com/products/docker-desktop/">https://www.docker.com/products/docker-desktop/</a>

* İndirme butonuna tıklayarak Docker Desktop'u bilgisayarınıza indirin.

* İndirme tamamlandıktan sonra, indirilen dosyayı açın ve Docker Desktop'u kurun.

## Adım 2: Rosetta'yı Güncelleme

* Terminal'i açın.

* Aşağıdaki komutu girerek Rosetta'yı güncelleyin:

<code>softwareupdate --install-rosetta</code>

## Adım 3: io.net Üzerinden Worker Eklemek

* io.net platformuna giriş yapın.

* worker menusune girin ve Connect New Worker butonuna tıklayın.

## Adım 4: Worker Ayarlarını Yapma

* "Select Operating System (OS)" (İşletim Sistemi Seçimi) adımında "macOS" seçeneğini belirleyin.

* "Select Supplier" (Tedarikçi Seçimi) adımında "io.net" seçeneğini belirleyin.

* "Name your device" (Cihazınızın Adını Belirtin) alanına bir cihaz adı girin.

* "Device Type" (Cihaz Türü) bölümünde "CPU" seçeneğini belirleyin.

* Gerekli olduğunda, Docker Desktop'u daha önce zaten yüklediğinizden emin olun.

## Adım 5: Binary İndirme ve Başlatma

* Son adımda gösterilen komutları sırasıyla Terminal'e girin. (Worker eklediğiniz kısımda 6. maddede belirtilen 3 komut )

* Daha sonra bağlantı sağlanana kadar en altta bulunan refresh butonuna basın .

Bu adımları takip ederek, MacOS üzerinde io.net platformuna sorunsuz katılabilirsiniz .
