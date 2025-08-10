# Kataribe — Media Transcribing Tool

🚀 **Kataribe** — это инструмент с графическим интерфейсом для автоматического создания субтитров `.srt` из аудио или видео с использованием моделей **Whisper** и их модификаций.  
Поддерживает **YouTube**, **VAD** (детекция речи), автоматическую пунктуацию и работу как на **CPU**, так и на **GPU (CUDA)**.

---

## ✨ Возможности
- 🎥 **Локальные файлы и YouTube** — загружайте с диска или по ссылке.
- 🤖 **ASR-модели** — Whisper, Kotoba-Whisper, Faster-Whisper и др.
- 🎯 **VAD** — отделение сегментов речи для точной транскрибации.
- 📝 **Автопунктуация** — добавление знаков препинания и правильных регистров.
- ⚡ **Поддержка CUDA** — ускорение на GPU.
- 🖥 **Удобный GUI** — выбор модели, устройства, папки сохранения, прогресс-бар.
- 💬 **Формат вывода** — `.srt` (SubRip Subtitle).

---

## 📸 Скриншоты
| Главное окно | Сплэш-экран |
|--------------|-------------|
| ![Main GUI](docs/gui.png) | ![Splash](docs/splash.png) |

---

## 📦 Установка и запуск

### 1. Скачивание готовой сборки
- Перейдите в [Releases](https://github.com/`<your-user>`/Kataribe/releases).
- Скачайте архив `Kataribe_vX.X.zip`.
- Распакуйте и запустите `Kataribe.exe`.

### 2. Запуск из исходников
```bash
git clone https://github.com/<your-user>/Kataribe.git
cd Kataribe
pip install -r requirements.txt
python gui.py
```

---

## ⚙ Требования
- **Windows 10/11** (64-бит)
- **FFmpeg** (идёт в сборке)
- Для GPU:
  - NVIDIA GPU с CUDA 11+
  - Драйверы CUDA и cuDNN

---

## 📜 Лицензия
Проект распространяется под лицензией **MIT** — свободно используйте, изменяйте и распространяйте с сохранением авторства.  
См. [LICENSE](LICENSE).

---

## 💡 Авторы
- [@iniquitousworld](https://github.com/iniquitousworld)  
- [@shim0neta](https://github.com/shim0neta)  

---
