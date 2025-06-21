# Quick Start Guide - Mgeko Downloader CLI v3.0

## 🚀 Fast Setup

### Option 1: Use Pre-built Executable (Recommended)
1. Download `mgeko-downloader-v3.0.0-windows.exe`
2. Double-click to run
3. Follow the prompts!

### Option 2: Run from Source
```bash
# Install Python 3.8+
pip install -r requirements.txt
python mgeko_downloader_cli.py
```

## 📖 How to Use

### Step 1: Choose Language
Select your preferred language (1-4):
- 1 = English
- 2 = Bahasa Indonesia  
- 3 = 日本語 (Japanese)
- 4 = Español (Spanish)

### Step 2: Enter URL
Paste any mgeko.cc chapter URL, for example:
```
https://www.mgeko.cc/reader/en/solo-leveling-chapter-1-eng-li/
```

### Step 3: Choose Download Mode
- **1 = Single Chapter**: Downloads just that chapter
- **2 = Chapter Range**: Downloads chapters X to Y
- **3 = All Chapters**: Downloads all available chapters

### Step 4: Wait for Download
The app will:
- ✅ Check chapter availability
- ✅ Extract image URLs  
- ✅ Download high-quality images
- ✅ Show real-time progress
- ✅ Handle errors automatically

## 📁 Output Structure
```
downloads/
├── manga-name_ch_001/
│   ├── 001.jpg
│   ├── 002.jpg
│   └── ...
├── manga-name_ch_002/
│   └── ...
```

## 🔧 Troubleshooting

**Problem**: "Invalid URL format"
**Solution**: Make sure URL is from mgeko.cc and contains chapter number

**Problem**: "Chapter not available"  
**Solution**: Try a different chapter or check if manga exists

**Problem**: Download fails
**Solution**: Check internet connection, try again (auto-retry included)

## 🌟 Pro Tips

- Use **All Chapters** mode for complete manga downloads
- App automatically skips already downloaded images
- Check the activity log for detailed information
- Download directory is created automatically

## 📞 Need Help?

- GitHub Issues: Report bugs or ask questions
- Documentation: Full README for advanced features
- Logs: Check `mgeko_downloader.log` for technical details

---

**Happy downloading! 📚✨**
