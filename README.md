# 🐺 TulparOS

> **Debian tabanlı, hafif, performans odaklı ve özelleştirilebilir Linux dağıtımı.**

TulparOS; kararlılığını Debian'ın sağlam altyapısından alan, modern masaüstü deneyimi ve düşük kaynak tüketimini bir arada sunmayı hedefleyen bağımsız bir Linux dağıtımıdır.

---

## 🚀 Öne Çıkan Özellikler

* **Debian Tabanlı Kararlılık:** Gücünü Debian paket yönetiminden ve geniş yazılım deposundan alır.
* **Hafif ve Hızlı:** Düşük donanımlarda bile akıcı çalışacak şekilde optimize edilmiştir.
* **APT & Nala Desteği:** Paket yönetimi için standart `apt` yanında daha hızlı ve görsel `nala` desteği sunar.
* **Sürücü Desteği:** Geniş donanım uyumluluğu için varsayılan olarak non-free/proprietary sürücü sürücü seçenekleri barındırır.
* **Minimal Taban:** Sistemde gereksiz arka plan servisleri ve gereksiz paketler (bloatware) yer almaz.

---

## 🛠️ Kurulum

TulparOS ISO imajını sisteminize yüklemek için aşağıdaki adımları izleyebilirsiniz:

### 1. ISO İmajını İndirin
En son sürüme ait ISO dosyasını indirin.

### 2. Kurulum Medyası Oluşturun
İndirdiğiniz ISO dosyasını bir USB belleğe yazdırmak için **Ventoy**, **BalenaEtcher** veya terminal üzerinden `dd` komutunu kullanabilirsiniz:

```bash
sudo dd if=tulparos-latest-amd64.iso of=/dev/sdX bs=4M status=progress conv=fsync
