# 🚀 Mgeko Manga Downloader V3

[![Version](https://img.shields.io/badge/version-3.0.0-blue.svg)](https://github.com/ibrayoga0/mgeko-downloader)
[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](https://github.com/ibrayoga0/mgeko-downloader)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

**Professional Windows manga downloader with multi-language support** - Download manga from Mgeko easily with a beautiful CLI interface.

## ✨ Features

- 🌍 **Multi-Language Support**: English, Indonesian, Japanese, Spanish
- 🚀 **Windows Executable**: No Python installation required
- 📱 **Professional CLI**: Beautiful, user-friendly interface
- 🔄 **Smart Resume**: Continue interrupted downloads
- 📝 **Detailed Logging**: Track all download activities
- ⚡ **Fast & Reliable**: Optimized download performance
- 🛡️ **Error Recovery**: Robust error handling and retry mechanism

##  Interface Preview

```
🚀 Mgeko Manga Downloader V3.0.0
=====================================

🌍 Select Language / Pilih Bahasa:
[1] English
[2] Indonesian  
[3] Japanese
[4] Spanish

Choice: _
```

## 🚀 Quick Start

### Download & Install

1. Go to [Releases](https://github.com/ibrayoga0/mgeko-downloader/releases)
2. Download: `mgeko-downloader-v3.0.0-windows.exe` 
3. Run the executable directly - no installation required!

## � System Requirements

- **OS**: Windows 10/11 (64-bit)
- **RAM**: 512MB minimum
- **Storage**: 50MB + space for manga downloads
- **Internet**: Stable connection required

## 💡 Usage

### How to Use

Simply run the executable:

```bash
# Double-click the file OR run from command line:
mgeko-downloader-v3.0.0-windows.exe
```

The application will guide you through:

1. **Language Selection**: Choose your preferred language
2. **URL Input**: Enter the mgeko.cc chapter URL
3. **Download Mode**: Select single, range, or all chapters
4. **Automatic Download**: Sit back and watch the magic happen!

### Example URLs

```
https://www.mgeko.cc/reader/en/solo-leveling-chapter-1-eng-li/
https://www.mgeko.cc/reader/en/tower-of-god-chapter-580-eng-li/
https://www.mgeko.cc/reader/en/one-piece-chapter-1100-eng-li/
```

## 🎯 Download Modes

### 1. Single Chapter
Downloads only the specified chapter.

### 2. Chapter Range
Downloads multiple chapters within a specified range.
- Enter start chapter number
- Enter end chapter number
- All chapters in between will be downloaded

### 3. All Available Chapters
Automatically detects and downloads all available chapters for the manga.
- Smart chapter detection
- Handles missing chapters gracefully
- Perfect for complete manga downloads

## 📁 Output Structure

```
downloads/
├── manga-name_ch_001/
│   ├── 001.jpg
│   ├── 002.jpg
│   └── ...
├── manga-name_ch_002/
│   ├── 001.jpg
│   ├── 002.jpg
│   └── ...
└── ...
```

## 🌍 Supported Languages

- **English** - Full support
- **Bahasa Indonesia** - Full support
- **日本語 (Japanese)** - Full support
- **Español (Spanish)** - Full support

## 📊 Performance

- **Download Speed**: Up to 50+ images per minute
- **Memory Usage**: < 100MB typical  
- **Success Rate**: 99%+ with retry mechanism
- **File Size**: ~7MB executable
- **Supported Formats**: JPG, PNG, WebP

## 🔧 Troubleshooting

### Common Issues

**1. "Invalid URL format" Error**
- Ensure URL is from mgeko.cc
- URL should follow format: `https://www.mgeko.cc/reader/en/manga-name-chapter-X-eng-li/`

**2. "Chapter not available" Error**
- Chapter might not exist or be temporarily unavailable
- Try a different chapter number

**3. Download Failures**
- Check internet connection
- Retry mechanism will automatically attempt failed downloads
- Check logs in `mgeko_downloader.log`

**4. Permission Errors**
- Ensure write permissions to download directory
- Run as administrator if necessary

### Getting Help

1. Check the [Issues](https://github.com/ibrayoga0/mgeko-downloader/issues) page
2. Review the log file: `mgeko_downloader.log`
3. Create a new issue with:
   - Error message
   - Windows version
   - URL you're trying to download
   - Log file contents

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Bug Reports**: Submit detailed bug reports with reproduction steps
2. **Feature Requests**: Suggest new features or improvements  
3. **Translations**: Help add support for more languages
4. **Documentation**: Improve documentation and examples

> **Note**: This is a Windows-only release. For other platforms, please create a feature request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is for educational and personal use only. Please respect copyright laws and the terms of service of the websites you download from. The developers are not responsible for any misuse of this software.

## 🙏 Acknowledgments

- Thanks to all contributors and users
- Special thanks to the manga community
- Built with love for manga enthusiasts worldwide

## 📞 Support

- **GitHub Issues**: [Report bugs or request features](https://github.com/ibrayoga0/mgeko-downloader/issues)
- **Email**: [Contact the developer](mailto:ibrayoga890@gmail.com)
- **Documentation**: [Full documentation](https://github.com/ibrayoga0/mgeko-downloader/wiki)

---

**Made with ❤️ for Windows manga enthusiasts**

⭐ **Star this repository if you find it useful!** ⭐
