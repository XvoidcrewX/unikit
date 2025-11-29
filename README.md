# Unicode Tools Suite

A comprehensive web-based tool suite for character analysis, text cleaning, and file extraction. This client-side application helps developers, content creators, and data analysts identify problematic invisible characters, clean text, and extract content from multiple files - all while maintaining complete privacy.

[![License](https://img.shields.io/badge/License-MIT-001CFF.svg)](LICENSE)
[![Download ZIP](https://img.shields.io/badge/Download-ZIP-blue)](https://github.com/XvoidcrewX/unikit/archive/refs/heads/main.zip)

## Features

### Character Viewer
- **Visualize Hidden Characters**: See invisible Unicode characters highlighted with their hex codes
- **Interactive Analysis**: Click on any character to view detailed Unicode information
- **File Support**: Upload and analyze various text files (TXT, LOG, CSV, JSON, XML, HTML, and more)
- **Character Counting**: Display total characters and byte size with real-time statistics
- **Tooltip Details**: Hover over characters to see decimal and hexadecimal values
- **Smart Rendering**: Special display for control characters (CR, LF, TAB, spaces)

### Text Cleaner
- **Remove Problematic Characters**: Automatically strip invisible Unicode characters
- **Copy & Download**: Easily copy cleaned text or download as file
- **Batch Processing**: Clean multiple files efficiently
- **Preserve Formatting**: Maintain visible text structure while removing hidden characters
- **File Upload Support**: Process entire text files with one click

### Text Extractor
- **Multi-File Processing**: Extract text from multiple files simultaneously
- **Wide Format Support**: Supports text files, code files, documents, scripts, and configuration files
- **Custom Extension Management**: Add or remove allowed file extensions with persistent storage
- **Progress Tracking**: Real-time progress bar for batch processing
- **Smart Filtering**: Automatic rejection of unsupported file types with detailed feedback
- **Combined Output**: All extracted text compiled into a single, organized output
- **Drag & Drop Interface**: Intuitive file upload with visual feedback
- **Raw Text Extraction**: Extract text content without formatting from supported files

### Additional Features
- **Dark Mode Support**: Toggle between light and dark themes with persistent preference
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Local Storage**: Remembers your custom file extensions and theme preference
- **No Dependencies**: Pure vanilla JavaScript - no external libraries required

## Quick Start

### Local Installation
1. Download [index.html](index.html)
2. Open it in any modern web browser
3. Start analyzing, cleaning, and extracting text

### Online Access
Simply open the HTML file in your browser - no server required!

## How to Use

### Analyzing Text (Character Viewer)
1. Paste your text into the "Input Text" area
2. Click "View Characters" to see hidden characters highlighted
3. Click on any character to view detailed Unicode information
4. Upload text files for analysis using the file upload option

### Cleaning Text (Text Cleaner)
1. Switch to the "Text Cleaner" tab
2. Paste or upload your text
3. Click "Clean Text" to remove invisible characters
4. Copy or download the cleaned result

### Extracting Text (Text Extractor)
**Important Usage Order:**
1. **First - Add Custom Extensions** (if needed):
   - If you want to process files with custom extensions, **add the extension first** in the "Manage Allowed File Extensions" section
   - Enter the extension (e.g., `rtf`, `custom`) and click "Add"
   - The extension will be saved and available for future sessions

2. **Then - Upload Files**:
   - Switch to the "Text Extractor" tab
   - Drag & drop files or click "Select Files" to browse
   - **Write the full file name** including extension when selecting files
   - Multiple files can be selected at once

3. **Process Files**:
   - Click "Extract Text from All Files" to process
   - View progress in the real-time progress bar
   - See rejected files with reasons in the "Unsupported Files" section

4. **Access Results**:
   - Copy combined text or download as a single file
   - Each file's content is clearly marked with headers

## File Upload Instructions

### For Standard File Types:
1. Go to the Text Extractor tab
2. Drag & drop files or click "Select Files"
3. Select your files (e.g., `document.txt`, `script.js`, `data.json`)
4. Click "Extract Text from All Files"

### For Custom File Types:
1. **First, add the extension** in the "Manage Allowed File Extensions" section
   - Example: Type `rtf` and click "Add"
2. **Then upload your file** with that extension
   - Example: Select `myfile.rtf` after adding the extension
3. Process as normal

### Supported File Types

The tool supports a wide range of text-based file formats:

#### Text & Documents
- **Text Files**: `.txt`, `.text`, `.log`, `.md`, `.markdown`
- **Documents**: `.ini`, `.conf`, `.cfg`, `.properties`

#### Code Files
- **Web**: `.html`, `.htm`, `.css`, `.scss`, `.sass`, `.less`, `.xml`
- **JavaScript/TypeScript**: `.js`, `.jsx`, `.ts`, `.tsx`
- **Backend**: `.py`, `.java`, `.c`, `.cpp`, `.cs`, `.php`, `.rb`, `.go`, `.rs`, `.swift`, `.kt`, `.scala`
- **Scripts**: `.bat`, `.sh`, `.ps1`

#### Data Files
- **Structured Data**: `.json`, `.csv`, `.yaml`, `.yml`, `.sql`

#### Custom Extensions
You can add your own file extensions through the extension manager. **Remember to add the extension first before uploading files** with that extension.

## Supported Characters

The tool detects and can remove various invisible Unicode characters including:

- **Zero-width characters**: `U+200B`, `U+FEFF`, `U+200C`, `U+200D`, `U+2060`
- **Directional markers**: `U+200E`, `U+200F`, `U+202A`-`U+202E`
- **Formatting controls**: `U+2061`-`U+2064`
- **Special format characters**: `U+FFF0`-`U+FFFD`
- **Line controls**: CR (Carriage Return), LF (Line Feed), TAB
- **Control characters**: Various other invisible and formatting characters

## Technology

- **Pure Client-Side**: HTML, CSS, JavaScript - no server required
- **No Dependencies**: Works without external libraries or frameworks
- **Cross-Platform**: Compatible with all modern browsers (Chrome, Firefox, Safari, Edge)
- **Privacy-Focused**: All processing happens locally - no data sent to servers
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Dark Mode**: Complete dark theme with smooth transitions
- **Local Storage**: Saves user preferences for extensions and theme

## Privacy & Security

- **No Data Collection**: All processing happens in your browser
- **No Cookies**: No tracking or user identification
- **No Server Uploads**: Your files and text never leave your computer
- **Local Storage**: Only stores your custom file extension preferences and theme locally
- **Open Source**: Transparent code for security verification
- **File Size Limits**: 10MB maximum per file to prevent browser crashes

## Important Notes

### File Processing:
- **Text Extraction**: Files are processed to extract raw text content without formatting
- **Large Files**: Maximum 10MB per file for optimal performance
- **Unsupported Files**: Clearly marked with rejection reasons
- **Batch Processing**: Multiple files processed sequentially with progress tracking

### Custom Extensions:
- **Add First**: Always add custom extensions before uploading files
- **Persistence**: Custom extensions are saved in your browser's local storage
- **Validation**: Only alphanumeric extensions (1-10 characters) are accepted
- **System Extensions**: Default extensions cannot be removed (gray tags)

## Helpful Resources

- [Unicode Converter](https://www.branah.com/unicode-converter)
- [FileFormat.Info Unicode Search](http://www.fileformat.info/info/unicode/char/search.htm)
- [UTF-8 Character Table](http://utf8-chartable.de/unicode-utf8-table.pl)
- [CloudConvert](https://cloudconvert.com/) - For file format conversion

## Repository & Updates

This tool is regularly updated with new features and improvements. Check the repository for the latest releases:

**Repository**: [https://github.com/XvoidcrewX/unikit](https://github.com/XvoidcrewX/unikit)

## Support Future Development

Unicode Tools Suite is built to grow stronger each year, with continuous upgrades in text processing, security, and analysis capabilities — without sponsors or corporate backing.

Your support ensures that future releases stay open-source, independent, and technically advanced.

### Bitcoin
```

bc1qk7hp6vxa5sd00sw3ma7la0cj7fdpkflvjrwq9g

```

### Monero
```

42uEgsLYHHgXwDdcs991anU12CZpS9m2dCAgtqw1MR9T4Hjs3CReQnJar8x1D1LjUAaWP5hAH77j9bXX3nJUxbXaE6GGvqD

```

☕ Buy me a coffee... or a cold beer 🍺 — every sip funds the next evolution.

---

**Note**: This tool is particularly useful for:
```
- Debugging text encoding issues
- Cleaning datasets  
- Content managers ensuring text compatibility across platforms
- Technical writers preparing documentation
- Anyone working with multi-language or special character text
- Quality assurance testing text inputs and outputs
```

## License

This project is open source and available under the [MIT License](LICENSE)
