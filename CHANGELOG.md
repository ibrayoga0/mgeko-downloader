# Changelog

All notable changes to Mgeko Downloader CLI will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.0.0] - 2025-01-21

### Added
- **Multi-language Support**: Full support for English, Indonesian, Japanese, and Spanish
- **Advanced Download Modes**: Single chapter, chapter range, and all available chapters
- **Smart Chapter Detection**: Automatically finds all available chapters for a manga
- **Professional CLI Interface**: Enhanced user experience with emojis and clear prompts
- **Comprehensive Error Handling**: Robust retry mechanism and detailed error reporting
- **Progress Tracking**: Real-time download progress with detailed statistics
- **Resume Downloads**: Automatically skip already downloaded images
- **Professional Logging**: Detailed logs for troubleshooting and monitoring
- **Build System**: Complete build system for creating standalone executables
- **Cross-platform Support**: Works on Windows, macOS, and Linux

### Enhanced
- **Performance Optimization**: Faster downloads with optimized HTTP sessions
- **Memory Management**: Reduced memory usage during large downloads
- **Code Structure**: Professional code organization with classes and modules
- **Documentation**: Comprehensive README with usage examples and troubleshooting

### Security
- **Safe HTTP Handling**: Secure session management and timeout controls
- **Input Validation**: Proper URL validation and sanitization
- **Error Isolation**: Contained error handling to prevent crashes

### Technical
- **Python 3.8+ Support**: Modern Python features and compatibility
- **Type Hints**: Full type annotation for better code maintainability
- **Modular Design**: Separate classes for different functionality
- **Configuration System**: Flexible configuration options

## [2.0.0] - Previous Version

### Features (Legacy)
- Basic manga downloading from mgeko.cc
- Single chapter download mode
- English language support only
- Basic error handling
- Simple command-line interface

## [1.0.0] - Initial Version

### Features (Legacy)
- Initial release
- Basic scraping functionality
- Limited error handling
- Minimal user interface

---

## Upcoming Features (Roadmap)

### [3.1.0] - Next Minor Release
- [ ] **GUI Version**: Optional graphical user interface
- [ ] **Download Queue**: Queue management for multiple manga
- [ ] **Batch Processing**: Process multiple URLs at once
- [ ] **Custom Output Formats**: PDF, CBZ, CBR generation
- [ ] **Progress Persistence**: Resume interrupted downloads across sessions

### [3.2.0] - Future Release
- [ ] **Cloud Storage**: Direct upload to cloud services
- [ ] **Notification System**: Desktop notifications for completed downloads
- [ ] **Update Checker**: Automatic update detection and installation
- [ ] **Plugin System**: Support for additional manga sites
- [ ] **Advanced Filtering**: Chapter filtering by date, quality, etc.

### [4.0.0] - Major Release
- [ ] **Web Interface**: Browser-based management interface
- [ ] **API Support**: RESTful API for external integrations
- [ ] **Database Integration**: SQLite database for download history
- [ ] **User Accounts**: Multi-user support with separate libraries
- [ ] **Streaming Mode**: Read manga while downloading

---

## Migration Guide

### From v2.x to v3.0.0

**Breaking Changes:**
- Command-line arguments have changed
- Configuration file format updated
- Output directory structure modified

**Migration Steps:**
1. Backup your existing downloads
2. Update to v3.0.0
3. Re-run the application with new interface
4. Existing downloads will be detected and skipped automatically

**New Features Available:**
- Select your preferred language on startup
- Use new download modes (single, range, all)
- Enjoy enhanced error handling and progress tracking

---

## Support and Issues

- **Bug Reports**: [GitHub Issues](https://github.com/ibrayoga0/mgeko-downloader/issues)
- **Feature Requests**: [GitHub Discussions](https://github.com/ibrayoga0/mgeko-downloader/discussions)
- **Documentation**: [Project Wiki](https://github.com/ibrayoga0/mgeko-downloader/wiki)

---

**Note**: Version numbers follow Semantic Versioning (SemVer):
- **MAJOR** version for incompatible API changes
- **MINOR** version for backwards-compatible functionality additions
- **PATCH** version for backwards-compatible bug fixes
