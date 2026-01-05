# Nepal Letter & Form Helper - नेपाल पत्र र फारम सहायक

A comprehensive, mobile-first digital platform for Nepali citizens to write official letters and create government form resources. This unofficial tool helps prepare documents following Nepal government formats while maintaining complete privacy through client-side processing.

## ⚠️ IMPORTANT DISCLAIMER

**This is an independent digital assistance platform. We are NOT affiliated with the Government of Nepal. This tool helps prepare letters and resources only. Final verification and submission must be done on official government websites.**

## 🎯 Project Overview

A unified website that combines:
- **Nepal Letter Writing System** - All types of official letters in proper government format
- **Government Form Resource Builder** - Tools to create required photos, documents, and files

## 📝 Nepal Letter Writing System

### Standard Nepal Letter Format (Mandatory)
All letters follow the commonly accepted Nepal government administrative format:

1. **Date** (B.S. preferred, A.D. optional)
2. **Sender Details** (Name, Address, Phone)
3. **Receiver Office Details**
4. **Subject line** — "विषय:"
5. **Salutation** — "महोदय,"
6. **Body** (formal administrative Nepali language)
7. **Closing** — "भवदीय,"
8. **Signature block** (name, signature, date)
9. **Printable A4 layout** with official margins

### Letter Categories

#### 1️⃣ Government & Administrative Letters
- **निवेदन पत्र** (Application)
- **सिफारिस पत्र** (Recommendation)
- **अनुरोध पत्र** (Request)
- **गुनासो / उजुरी पत्र** (Complaint)
- **स्पष्टीकरण पत्र** (Clarification)
- **प्रमाणिकरण अनुरोध पत्र** (Verification Request)

#### 2️⃣ Education Letters
- **विद्यालय / कलेज निवेदन** (School/College Application)
- **छात्रवृत्ति आवेदन** (Scholarship Application)
- **चरित्र प्रमाणपत्र निवेदन** (Character Certificate Request)
- **स्थानान्तरण पत्र** (Transfer Letter)

#### 3️⃣ Job & Professional Letters
- **Job Application**
- **Cover Letter**
- **Leave Application**
- **Resignation Letter**
- **Experience Letter Request**

#### 4️⃣ Personal & Legal (Templates Only)
- **शपथपत्र** (Affidavit) ⚠️ *Legal verification required*
- **घोषणा पत्र** (Declaration) ⚠️ *Legal verification required*
- **मन्जुरीनामा** (Approval Letter) ⚠️ *Legal verification required*
- **करारनामा** (Agreement) ⚠️ *Legal verification required*

### Letter System Features
- ✅ **Nepali + English toggle**
- ✅ **BS date auto-generator**
- ✅ **Formal wording suggestions**
- ✅ **Preview before download**
- ✅ **Export as PDF & Word**
- ✅ **Optional signature attachment**

## 🧰 Government Form Resource Builder Tools

### 📸 1️⃣ Passport Size Photo Maker (Nepal Standard)
- **Size**: 35mm × 45mm
- **Resolution**: 300 DPI
- **Background**: White / Light blue
- **Features**: Auto face centering, crop guide overlay, background removal
- **Output**: JPG / PNG (Print-ready & upload-ready)

### 🗜️ 2️⃣ Photo Compression Tool
- **Compress under**: 50 KB, 100 KB, Custom size
- **Quality**: No visible quality loss
- **Privacy**: Client-side only processing
- **Batch**: Multiple photos at once

### ✍️ 3️⃣ Signature Maker
- **Input**: Draw signature (touch/mouse)
- **Output**: Transparent PNG
- **Features**: Resize / rotate, attach to PDF or image

### 🎭 4️⃣ Background Removal Tool
- **Function**: One-click background removal
- **Replace with**: White / light blue
- **Features**: Edge smoothing, mobile optimized

### 📄 5️⃣ PDF Maker & Converter
- **Convert**: Text → PDF, Image → PDF, Multiple images → single PDF
- **Layout**: A4 layout with Nepal-standard margins

### 📐 6️⃣ Image Validator
- **Shows**: Image size, file size, DPI
- **Warns**: If not government-acceptable
- **Suggests**: Auto-fix recommendations

### 📋 7️⃣ Government Form Resource Checklist
Choose form type and get:
- **Required photos** with specifications
- **Required documents** list
- **File size limits** and formats
- **Downloadable checklist** as PDF

**Supported Forms**: Passport, Citizenship, PAN, Driving License, Loksewa Exam, Voter ID

## 🇳🇵 Nepal-Specific Features

- **Nepali Unicode** (Devanagari script) support
- **Formal government wording** templates
- **Simple explanations** for non-technical users
- **Low-bandwidth optimization** for rural areas
- **Android phone compatibility**
- **Dark mode support**
- **Bikram Sambat (B.S.) date system**

## 🖥️ Technical Stack

### Frontend
- **HTML5** - Semantic structure
- **Tailwind CSS** - Responsive styling
- **Vanilla JavaScript** - No framework dependencies

### Libraries
- **jsPDF** - PDF generation
- **pdf-lib** - Advanced PDF manipulation
- **docx.js** - Word document export
- **Canvas API** - Image processing
- **Fabric.js** - Advanced canvas operations

### Hosting
- **Static hosting compatible** (GitHub Pages / Netlify)
- **No server required** - runs entirely client-side

## 📁 File Structure

```
nepal-letter-helper/
├── index.html              # Main homepage
├── styles.css              # Custom CSS with Nepal-specific styling
├── script.js               # Complete JavaScript functionality
├── README.md               # This documentation
└── assets/                 # (Optional) Images and icons
```

## 🚀 Getting Started

### Installation
1. **Clone or download** this repository
2. **Open `index.html`** in any modern web browser
3. **No server setup required** - works offline after initial load

### Usage
1. **Select Category**: Choose from Letters or Tools
2. **Fill Forms**: Enter details in provided fields
3. **Preview**: Review your document before generating
4. **Generate**: Create PDF/Word documents
5. **Download**: Save files to your device

## 🌟 Key Features

### Privacy & Security
- **No Data Storage** - All processing in browser
- **Client-Side Only** - No data sent to servers
- **No Registration** - Use immediately
- **Offline Capable** - Works without internet after load

### Accessibility
- **Screen Reader Friendly** - ARIA labels and semantic HTML
- **Keyboard Navigation** - Full keyboard support
- **High Contrast** - Supports high contrast mode
- **Mobile First** - Optimized for smartphones
- **Low Bandwidth** - Fast loading on slow connections

### Language Support
- **Bilingual Interface** - English ↔ Nepali toggle
- **Unicode Safe** - Proper Devanagari handling
- **Cultural Context** - Nepal-style examples and formats

## 🔗 Official Government Portals

The website includes quick links to:
- [Nagarik App Portal](https://nagarikapp.gov.np)
- [Citizen Portal](https://citizenportal.donidcr.gov.np)

**Remember**: Always verify document formats with official portals before submission.

## ⌨️ Keyboard Shortcuts

- **Esc** - Close modal/dialog
- **Ctrl + D** - Toggle dark mode
- **Ctrl + L** - Toggle language (English ↔ Nepali)

## 🛠️ Development

### Adding New Letter Types
1. Add letter form generator function in `script.js`
2. Add letter type to `openLetterForm()` function
3. Update translation data for bilingual support
4. Add button in appropriate category section

### Adding New Tools
1. Create tool generator function
2. Add tool initialization function
3. Add tool to `openTool()` function
4. Update UI with new tool button

## 📱 Browser Compatibility

- **Chrome** 60+ ✅
- **Firefox** 55+ ✅
- **Safari** 12+ ✅
- **Edge** 79+ ✅
- **Mobile browsers** ✅

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## ⚖️ Legal Notice

This tool is provided "as is" without warranty. Users are responsible for:
- Verifying accuracy of generated documents
- Ensuring legal compliance
- Consulting legal professionals for important documents
- Following official government procedures

## 📄 License

This project is open source and available under the MIT License.

## 🆘 Support

For issues or questions:
1. Check the FAQ section
2. Review the documentation
3. Submit an issue on GitHub
4. Contact through official channels

---

**Built with ❤️ for the people of Nepal**

*Empowering citizens with digital tools while respecting traditional administrative formats*