# Yuki — Sesli AI Companion (Lite)

Anime tarzı, **sesle konuşan** bir masaüstü AI arkadaşı. Kendi API anahtarınla (BYOK) çalışır — kurulum yok (Linux'ta tek dosya, Windows'ta zip).

> Bu depo yalnızca **indirilebilir sürümü** barındırır (kaynak kod burada değildir).
> Tanıtım & portfolyo: **[ihsandeniz.net.tr](https://ihsandeniz.net.tr/proje.html?p=alice)**

## ⬇️ İndir

**[→ Son sürümü indir (Linux AppImage · Windows zip)](https://github.com/ihsandeniz/yuki-ai/releases/latest)**

*Linux ve Windows (x64) hazır; macOS yok.*

## Ne var? (Ücretsiz Lite sürüm)

- 🎙️ **Sesli sohbet** — Yuki konuşur ve dinler (ses: Edge TTS, internet ister · konuşma tanıma: faster-whisper, cihazında)
- 🛠️ **20 sistem aracı** — web arama, hava, döviz & kripto, not, görev, hatırlatıcı, OCR, QR, pano, medya
- 🔑 **Kendi anahtarın (BYOK)** — OpenRouter dahil 15 bulut sağlayıcı ya da anahtarsız yerel Ollama; OpenRouter'ın ücretsiz modelleriyle başla
- 🖥️ **İki arayüz** — Sohbet + HALKA HUD

*Çoklu karakter · planlayıcı · gelişmiş araçlar → Pro · kalıcı (semantik) hafıza → Ultra.*

## Nasıl çalıştırılır?

1. Yukarıdan indirdiğin **Yuki-…-lite.AppImage** dosyasını al.
2. Çalıştırma izni ver: `chmod +x Yuki-*.AppImage` (veya sağ tık → Özellikler → "Çalıştırılabilir").
   *Windows'ta:* `Yuki-…-win-x64-lite.zip`'i kullanıcı klasörüne aç (`C:\Program Files` değil), `Yuki.exe`'yi çalıştır.
3. Çift tıkla aç — kurulum yok.
4. **⚙ AYAR → 🔑 ANAHTAR** → [openrouter.ai/keys](https://openrouter.ai/keys) ücretsiz anahtarını yapıştır → Kaydet.
5. Yuki'yle konuşmaya başla ✨

## Gereksinimler

- Linux (x86_64), glibc tabanlı bir dağıtım
- ya da Windows 10/11 (x64)
- İnternet bağlantısı (bulut LLM, sesli yanıt ve web araçları için)
- Bir LLM API anahtarı — ör. OpenRouter (ücretsiz alınır); yerel Ollama kullanırsan anahtar gerekmez

## Gizlilik

Anahtarın ve verilerin **yalnızca kendi bilgisayarında** saklanır (Linux `~/.config/alice-ai/` · Windows `%APPDATA%\alice-ai\`). Bizim sunucumuza hiçbir şey gitmez. Uygulamanın konuştuğu dış servisler: seçtiğin LLM sağlayıcı, sesli yanıt için Microsoft Edge TTS (Yuki'nin cevap metni), kullandığın araçlara göre DuckDuckGo / Open-Meteo (hava) / Frankfurter (döviz) / CoinGecko (kripto) ve güncelleme denetimi için GitHub.

---

© İhsan Deniz Tüfekci · [ihsandeniz.net.tr](https://ihsandeniz.net.tr)
