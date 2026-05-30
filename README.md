# Discord - OnlyGhost Studio Bot & Server Setup

Bu klasör tüm Discord ile ilgili dosyaları içerir.

## 📁 Dosyalar

### Bot Dosyaları
- `bot.py` - AI-powered Discord bot (Gemini)
- `discord_setup.py` - Sunucu kurulum scripti
- `requirements.txt` - Python bağımlılıkları

### Konfigürasyon
- `.env` - Gizli ayarlar (TOKEN, API KEY, vb) - **GİTHUB'A YÜKLENMEZ**
- `.env.example` - Template dosyası

### Dokümantasyon
- `BOT_SETUP.md` - Detaylı bot kurulum rehberi
- `BOT_QUICK_START.md` - Hızlı başlangıç (5 dakika)
- `BOT_ENV_SETUP.md` - Environment variables ayarları

## 🚀 Hızlı Başlangıç

### 1. Bot Kurulumu

```bash
# Bağımlılıkları yükle
pip install -r requirements.txt

# .env dosyasını doldur
# (BOT_ENV_SETUP.md'yi oku)

# Botu çalıştır
python bot.py
```

### 2. Sunucu Kurulumu

```bash
# Sunucuyu kur (ilk kez)
python discord_setup.py

# Token seç (1 = Bot Token, 2 = User Token)
# Token'ı gir
# Bitti!
```

## 📝 Komutlar

Sadece sen (581877396584529921) kullanabilirsin:

| Komut | Açıklama |
|-------|----------|
| `!devlog <info>` | Devlog oluştur |
| `!ask <soru>` | AI'ya sor |
| `!announce <mesaj>` | Duyuru gönder |
| `!update <info>` | Güncelleme paylaş |
| `!notify <rol> <mesaj>` | Rol bilgilendir |
| `!status` | Sunucu durumu |
| `!help` | Komutları göster |

## 🔐 Güvenlik

- `.env` dosyası **GİTHUB'A YÜKLENMEZ** (.gitignore'da)
- Token'ları asla paylaşma
- API key'leri gizli tut

## 📚 Detaylı Rehberler

- **Hızlı Başlangıç:** `BOT_QUICK_START.md`
- **Bot Kurulumu:** `BOT_SETUP.md`
- **Environment Setup:** `BOT_ENV_SETUP.md`

## 🎯 Özellikler

### Bot
- 🤖 AI Devlog Generator (Gemini)
- 💬 Smart AI Assistant
- 📢 Announcements
- 🔄 Studio Updates
- 🔔 Role Notifications
- 👤 Auto Member Role
- 🔐 Owner-Only Commands

### Sunucu
- 📢 ANNOUNCEMENTS (3 kanal)
- 💬 COMMUNITY (4 kanal)
- 🎮 GAMES (2 kanal)
- 📊 LOGS (2 kanal)
- 👥 ABOUT (3 kanal)
- 9 Özel Rol
- Rol-based Permissions

## 💡 İpuçları

- Bot'u arka planda çalıştırmak için `nohup python bot.py &` kullan
- Sunucu kurulumunu tekrar çalıştırabilirsin (eski kanallar silinir)
- Gemini API tamamen bedava
- Token'ı regenerate etmek istersen Discord'da yap

## 🆘 Sorun Giderme

**Bot çalışmıyor:**
- `.env` dosyası dolduruldu mu?
- Token'lar doğru mu?
- Bağımlılıklar yüklü mü?

**Sunucu kurulumu başarısız:**
- Bot token'ı doğru mu?
- Bot sunucuya davet edildi mi?
- Bot yeterli izinlere sahip mi?

Detaylı sorun giderme için ilgili `.md` dosyasını oku.

---

**Hazır!** Discord bot ve sunucu kurulumu tamamlandı. 🚀
