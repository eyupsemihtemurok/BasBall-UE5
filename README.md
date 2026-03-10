# 🏀 BasBall-UE5

> Unreal Engine 5 ile geliştirilmiş, bir basketbol topunun parkur yaptığı aksiyon oyunu.

---

## 📖 Proje Hakkında / About

**TR:** BasBall-UE5, bir basketbol topunun ana karakter olduğu, parkur mekaniklerine dayanan bir aksiyon oyunudur. Oyuncu, topu kontrol ederek engelleri aşar, puanlar toplar ve parkur bölümlerini tamamlar. Proje Unreal Engine 5.3 kullanılarak geliştirilmektedir.

**EN:** BasBall-UE5 is an action game featuring a basketball as the main character, built around parkour mechanics. The player controls the ball, navigates through obstacles, collects points, and completes parkour sections. The project is being developed with Unreal Engine 5.3.

---

## 🎮 Oyun Mekanikleri / Gameplay Mechanics

- 🏀 **Basketbol Topu Kontrolü** – Oyuncu bir basketbol topunu yönlendirerek haritada ilerler.
- 🏃 **Parkur** – Top, çeşitli platformlar ve engellerden geçen parkur bölümlerini tamamlar.
- ⭐ **Puan Toplama** – Haritada belirli noktalara ulaşarak ve görevleri tamamlayarak puan kazanılır.
- 🗺️ **Bölüm Tasarımı** – Farklı zorluk seviyelerinde tasarlanmış parkur bölümleri.

---

## 🛠️ Teknik Gereksinimler / Technical Requirements

| Özellik / Feature         | Detay / Detail                        |
|---------------------------|---------------------------------------|
| **Oyun Motoru / Engine**  | Unreal Engine 5.3                     |
| **Grafik API**            | DirectX 12 (birincil / primary)       |
| **Platform**              | Windows (Desktop)                     |
| **Giriş Sistemi / Input** | Enhanced Input System (EIS)           |
| **Render**                | Nanite, Lumen (Dynamic GI), VSM       |
| **Ses / Audio**           | 48kHz Mekansal Ses / Spatial Audio    |

### Minimum Sistem Gereksinimleri / Minimum System Requirements

- **İşletim Sistemi / OS:** Windows 10/11 (64-bit)
- **İşlemci / CPU:** Intel Core i7-8700K / AMD Ryzen 5 3600
- **RAM:** 16 GB
- **GPU:** NVIDIA GTX 1080 / AMD RX 5700 (DirectX 12 destekli / compatible)
- **Depolama / Storage:** 10 GB boş alan / free space
- **Unreal Engine:** 5.3 veya üzeri / or newer

---

## 🚀 Kurulum ve Çalıştırma / Setup and Running

### Gereksinimler / Prerequisites

1. [Unreal Engine 5.3](https://www.unrealengine.com/) kurulu olmalıdır / must be installed.
2. [Git](https://git-scm.com/) ve [Git LFS](https://git-lfs.github.com/) kurulu olmalıdır / must be installed.

### Adımlar / Steps

```bash
# 1. Depoyu klonlayın / Clone the repository
git clone https://github.com/eyupsemihtemurok/BasBall-UE5.git

# 2. Git LFS dosyalarını indirin / Pull Git LFS files
cd BasBall-UE5
git lfs pull

# 3. Projem.uproject dosyasına sağ tıklayın ve
#    "Generate Visual Studio project files" seçin (C++ kullanıyorsanız)
# Right-click Projem.uproject and select
# "Generate Visual Studio project files" (if using C++)

# 4. Projem.uproject dosyasına çift tıklayarak Unreal Editor'ı açın
# Double-click Projem.uproject to open in Unreal Editor
```

---

## 📁 Proje Yapısı / Project Structure

```
BasBall-UE5/
├── Config/                   # Yapılandırma dosyaları / Config files
│   ├── DefaultEditor.ini
│   ├── DefaultEngine.ini     # Grafik ve render ayarları / Graphics & render settings
│   ├── DefaultGame.ini       # Oyun ayarları / Game settings
│   └── DefaultInput.ini      # Giriş bağlamaları / Input bindings
├── Content/                  # Oyun varlıkları / Game assets
│   ├── StarterContent/       # UE5 Başlangıç İçeriği / UE5 Starter Content
│   │   ├── Audio/            # Ses efektleri / Sound effects
│   │   └── Architecture/     # Mimari varlıklar / Architecture assets
│   └── Untitled.umap         # Ana oyun haritası / Main game level
├── .gitattributes            # Git LFS yapılandırması / Git LFS config
├── .gitignore                # Git yok say kuralları / Git ignore rules
└── Projem.uproject           # UE5 proje dosyası / UE5 project file
```

---

## 🔧 Kullanılan Teknolojiler / Technologies Used

- **[Unreal Engine 5.3](https://www.unrealengine.com/)** – Oyun motoru / Game engine
- **Lumen** – Dinamik global aydınlatma / Dynamic global illumination
- **Nanite** – Sanallaştırılmış geometri / Virtualized geometry
- **Virtual Shadow Maps (VSM)** – Yüksek kaliteli gölgeler / High-quality shadows
- **Enhanced Input System** – Gelişmiş giriş yönetimi / Advanced input management
- **ModelingToolsEditorMode** – Editör içi 3D modelleme / In-editor 3D modeling

---

## 👤 Geliştirici / Developer

**Eyüp Semih Temurok**

---

## 📄 Lisans / License

Bu proje şu an için özel bir lisansa sahip değildir. Tüm haklar saklıdır.

*This project does not currently have a specific license. All rights reserved.*
