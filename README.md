# VoiceLearn

A dynamic multi-language text-to-speech learning application that helps you learn vocabulary across multiple languages simultaneously. Upload a CSV file with words in different languages and let VoiceLearn speak them in sequence for immersive language learning.

## Features

- **Dynamic Language Support**: Supports any number of languages (2, 3, 4, 5+) - just add more columns to your CSV
- **Visual Learning Interface**: Clean, intuitive web interface with real-time visual feedback
- **Sequential Playback**: Plays all languages in order with customizable pauses between words
- **Language Detection**: Automatically uses appropriate voices for each language
- **Interactive Controls**: Play, pause, stop, next/previous navigation with repeat mode
- **Progress Tracking**: Visual progress bar and statistics
- **Drag & Drop**: Easy CSV file upload with drag-and-drop support
- **Responsive Design**: Works on desktop and mobile browsers

## Quick Start

1. **Download the files**:
   ```bash
   git clone https://github.com/moemoe89/voice-learn.git
   cd voicelearn
   ```

2. **Open `index.html`** in your web browser (double-click or open with browser)

3. **Prepare your CSV file**:
   ```csv
   こんにちは,Hello,Halo
   ありがとう,Thank you,Terima kasih
   さようなら,Goodbye,Selamat tinggal
   ```

4. **Upload, configure languages, and start learning!**

## Files

- `index.html` - The complete VoiceLearn application (no server required!)
- `README.md` - This documentation
- `LICENSE` - MIT license

## CSV Format

VoiceLearn accepts simple CSV files with any number of columns:

```csv
word_lang1,word_lang2,word_lang3,word_lang4
目線,sudut pandang,gaze,視線
後悔,menyesal,regret,후회
無視,menghiraukan,ignore,무시
```

- Each column represents a different language
- No headers required - just pure data
- Supports any number of columns (minimum 2)
- Handles different CSV encodings and line endings

## Supported Languages

VoiceLearn supports 40+ languages through the Web Speech API:

- **Asian**: Japanese, Korean, Chinese (Mandarin/Taiwan), Indonesian, Thai, Vietnamese, Hindi
- **European**: English (US/UK), Spanish, French, German, Italian, Portuguese, Russian, Dutch, Swedish, Norwegian, Danish, Finnish, Polish, Czech, Hungarian, and more
- **Others**: Arabic, Hebrew, Turkish, and additional regional variants

*Note: Available voices depend on your browser and operating system.*

## How It Works

1. **Upload**: Drag and drop or select your CSV file
2. **Configure**: Assign languages to each column using dropdown menus
3. **Learn**: Click "Start Learning" and VoiceLearn will:
    - Display all words visually with language labels
    - Play each language in sequence with proper pronunciation
    - Highlight the currently spoken word
    - Automatically progress through your vocabulary list

## Browser Compatibility

- **Chrome**: Full support with excellent voice quality ⭐ **Recommended**
- **Safari**: Good support on macOS and iOS
- **Firefox**: Basic support with limited voice options
- **Edge**: Good support on Windows

*For the best experience, use Chrome or Safari.*

## Installation & Usage

### Option 1: Direct Download
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start learning immediately!

### Option 2: Local Web Server (Optional)
If you encounter file loading issues:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with npx)
npx serve .

# Then open http://localhost:8000
```

## Configuration Options

### Speech Settings
- **Speech Rate**: Adjust from 0.5x to 2x speed
- **Pause Duration**: Customize pauses between word sets (500ms - 10s)

### Learning Controls
- **Repeat Mode**: Loop current word set indefinitely
- **Manual Navigation**: Jump to specific words using next/previous
- **Progress Tracking**: Visual progress bar and statistics

## Use Cases

- **Language Learning**: Practice pronunciation and vocabulary across multiple languages
- **Translation Practice**: Compare words across languages simultaneously
- **Vocabulary Building**: Build multilingual vocabulary systematically
- **Pronunciation Training**: Hear native-like pronunciation for each language
- **Educational Tools**: Teachers can create multilingual learning materials

## Example Learning Scenarios

### Japanese-Indonesian-English Learning
```csv
食べ物,makanan,food
飲み物,minuman,drink
学校,sekolah,school
```

### European Language Comparison
```csv
hello,hola,bonjour,hallo,ciao
thank you,gracias,merci,danke,grazie
goodbye,adiós,au revoir,auf wiedersehen,ciao
```

### Academic Vocabulary Building
```csv
研究,penelitian,research,연구
분석,analisis,analysis,분석
結論,kesimpulan,conclusion,결론
```

## Technical Details

- **Frontend-Only**: Pure HTML, CSS, and JavaScript - no server required
- **Web Speech API**: Uses browser's built-in text-to-speech capabilities
- **No Dependencies**: Self-contained single HTML file
- **Responsive**: CSS Grid and Flexbox for mobile compatibility
- **Real-time**: Dynamic DOM updates with visual feedback

## Troubleshooting

### No Speech Output
- Ensure your browser supports Web Speech API (Chrome/Safari recommended)
- Check browser permissions for speech synthesis
- Try refreshing the page

### CSV Not Loading
- Ensure your CSV uses comma separators
- Check file encoding (UTF-8 recommended)
- Try opening in a local web server if direct file access fails

### Voice Quality Issues
- Some languages may have limited voice options depending on your OS
- Install additional language packs in your operating system
- Try different browsers for different voice selections

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make changes to `index.html`
4. Test in multiple browsers
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with vanilla JavaScript and Web Speech API
- Uses browser's built-in text-to-speech functionality
- Inspired by the need for flexible multilingual learning tools
- No external dependencies or server required

---

**VoiceLearn** - Learn languages through voice, one CSV at a time.

*Simply open `index.html` in your browser and start learning!*

## CSV Format

VoiceLearn accepts simple CSV files with any number of columns:

```csv
word_lang1,word_lang2,word_lang3,word_lang4
目線,sudut pandang,gaze,視線
後悔,menyesal,regret,後悔
無視,menghiraukan,ignore,無視
```

- Each column represents a different language
- No headers required - just pure data
- Supports any number of columns (minimum 2)
- Handles different CSV encodings and line endings

## Supported Languages

VoiceLearn supports 40+ languages through the Web Speech API:

- **Asian**: Japanese, Korean, Chinese (Mandarin/Taiwan), Indonesian, Thai, Vietnamese, Hindi
- **European**: English (US/UK), Spanish, French, German, Italian, Portuguese, Russian, Dutch, Swedish, Norwegian, Danish, Finnish, Polish, Czech, Hungarian, and more
- **Others**: Arabic, Hebrew, Turkish, and additional regional variants

*Note: Available voices depend on your browser and operating system.*

## How It Works

1. **Upload**: Drag and drop or select your CSV file
2. **Configure**: Assign languages to each column using dropdown menus
3. **Learn**: Click "Start Learning" and VoiceLearn will:
    - Display all words visually with language labels
    - Play each language in sequence with proper pronunciation
    - Highlight the currently spoken word
    - Automatically progress through your vocabulary list

## Browser Compatibility

- **Chrome**: Full support with excellent voice quality
- **Safari**: Good support on macOS and iOS
- **Firefox**: Basic support with limited voice options
- **Edge**: Good support on Windows

*For the best experience, use Chrome or Safari.*

## Installation & Development

### Prerequisites
- Go 1.16 or later
- Modern web browser with Web Speech API support

### Running Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/voicelearn.git
cd voicelearn

# Run the application
go run main.go

# Open browser to http://localhost:8080
```

### Building for Production
```bash
# Build binary
go build -o voicelearn main.go

# Run binary
./voicelearn
```

## Configuration Options

### Speech Settings
- **Speech Rate**: Adjust from 0.5x to 2x speed
- **Pause Duration**: Customize pauses between word sets (500ms - 10s)

### Learning Controls
- **Repeat Mode**: Loop current word set indefinitely
- **Manual Navigation**: Jump to specific words using next/previous
- **Progress Tracking**: Visual progress bar and statistics

## Use Cases

- **Language Learning**: Practice pronunciation and vocabulary across multiple languages
- **Translation Practice**: Compare words across languages simultaneously
- **Vocabulary Building**: Build multilingual vocabulary systematically
- **Pronunciation Training**: Hear native-like pronunciation for each language
- **Educational Tools**: Teachers can create multilingual learning materials

## Example Learning Scenarios

### Japanese-Indonesian-English Learning
```csv
食べ物,makanan,food
飲み物,minuman,drink
学校,sekolah,school
```

### European Language Comparison
```csv
hello,hola,bonjour,hallo,ciao
thank you,gracias,merci,danke,grazie
goodbye,adiós,au revoir,auf wiedersehen,ciao
```

### Academic Vocabulary Building
```csv
研究,penelitian,research,연구
分析,analisis,analysis,분석
結論,kesimpulan,conclusion,결론
```

## Technical Architecture

- **Backend**: Go with net/http standard library
- **Frontend**: Vanilla JavaScript with Web Speech API
- **No Dependencies**: Self-contained single binary
- **Responsive**: CSS Grid and Flexbox for mobile compatibility
- **Real-time**: Dynamic DOM updates with visual feedback

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with Go's standard library
- Uses the Web Speech API for text-to-speech functionality
- Inspired by the need for flexible multilingual learning tools

---

**VoiceLearn** - Learn languages through voice, one CSV at a time.