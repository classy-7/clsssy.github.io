# 🌈 Web Content Extractor

A powerful, RGB-animated web content extraction tool that preserves original formatting including tables, lists, and structure.

## ✨ Features

### 🎨 **RGB Animated Interface**
- Dynamic RGB gradient backgrounds that follow mouse movement
- Floating RGB particles with smooth animations
- RGB pulse effects on buttons and interactive elements
- Animated RGB borders and glowing effects
- Enhanced RGB spinner for loading states

### 📄 **Advanced Content Extraction**
- **Extract content from any webpage** using multiple CORS proxies
- **Preserve original formatting** including tables, rows, and columns
- **Maintain content structure** (headings, lists, images, links)
- **Smart content detection** with multiple fallback mechanisms
- **Enhanced table preservation** with proper styling

### 📊 **Structure Preservation**
- **Tables**: Full table structure with headers, rows, and columns
- **Lists**: Ordered and unordered lists with proper formatting
- **Headings**: H1-H6 hierarchy with visual indicators
- **Images**: With captions and hover effects
- **Links**: External link indicators and hover states
- **Code blocks**: Syntax highlighting style
- **Blockquotes**: Elegant left border styling

### 📋 **Multiple Export Formats**
- **PDF Generation**: 
  - Standard PDF with RGB headers/footers
  - Enhanced PDF with table formatting
  - Text-only PDF for minimal size
- **Word Document**: .docx format with preserved structure
- **Markdown**: .md format with proper conversion
- **Plain Text**: Copy to clipboard functionality

### 🎯 **User Experience**
- **Keyboard Shortcuts**:
  - `Ctrl/Cmd + Enter`: Extract content
  - `Ctrl/Cmd + D`: Download PDF
  - `Ctrl/Cmd + C`: Copy content
- **Easter Egg**: Konami code (↑↑↓↓←→←→BA) for Rainbow Mode
- **Progress Bars**: RGB animated download progress
- **Responsive Design**: Works on all screen sizes
- **Toast Notifications**: User-friendly feedback

## 🚀 **Getting Started**

### **Prerequisites**
- Modern web browser with JavaScript enabled
- Internet connection for content extraction
- Local development server (optional)

### **Installation**
1. Clone or download the project files
2. Open `index.html` in your browser
3. Or run a local server:
   ```bash
   python -m http.server 8000
   ```
4. Navigate to `http://localhost:8000`

### **Usage**
1. **Enter URL**: Type any webpage URL in the input field
2. **Select Options**: Choose what to include (images, styles, links, metadata)
3. **Choose Format**: Select PDF format (Standard, Enhanced, Text-only)
4. **Extract**: Click "Extract Content" or press `Ctrl+Enter`
5. **Download**: Choose your preferred export format

## 🛠️ **Technical Details**

### **Content Extraction Methods**
1. **Direct Fetch**: Attempts direct CORS request
2. **Proxy Services**: Multiple fallback CORS proxies
3. **Text Extraction**: Jina AI proxy for text-based content
4. **Smart Parsing**: DOM-based content identification
5. **Structure Preservation**: Maintains original HTML structure

### **Supported Content Types**
- **Tables**: Full table structure with headers and data
- **Lists**: Ordered (ol) and unordered (ul) lists
- **Headings**: All heading levels (h1-h6)
- **Images**: With alt text and captions
- **Links**: Internal and external links
- **Code Blocks**: Pre and code tags
- **Blockquotes**: Quote styling
- **Div Layouts**: Content structure preservation

### **PDF Generation Features**
- **RGB Headers**: Gradient color headers on each page
- **Table Rendering**: Proper table formatting in PDF
- **Page Breaks**: Smart pagination for large content
- **RGB Footers**: Page numbers with RGB styling
- **Font Hierarchy**: Proper heading sizing
- **Content Layout**: Maintains original structure

## 🎨 **Styling & Animations**

### **RGB Color Scheme**
- **Primary Red**: `#ff006e`
- **Primary Green**: `#00ff88`
- **Primary Blue**: `#00d4ff`
- **Dark Background**: `#0a0a0a`
- **Card Background**: `#1a1a1a`

### **Animation Types**
- **RGB Gradient**: Animated background gradients
- **Floating Particles**: RGB particles floating upward
- **Pulse Effects**: RGB glow on interactive elements
- **Border Animations**: RGB color cycling on borders
- **Hover States**: Transform and color transitions
- **Loading Spinners**: RGB rotating loaders

## 📱 **Responsive Design**

### **Breakpoints**
- **Desktop**: Full functionality with all animations
- **Tablet**: Optimized spacing and touch targets
- **Mobile**: Simplified layout with vertical stacking

### **Mobile Optimizations**
- Touch-friendly button sizes
- Optimized table rendering
- Simplified animations for performance
- Vertical action button layout

## 🔧 **Customization**

### **Configuration Options**
- **Include Images**: Toggle image extraction
- **Preserve Styling**: Maintain original CSS
- **Include Links**: Preserve hyperlink formatting
- **Include Metadata**: Extract titles and timestamps
- **PDF Format**: Choose output format

### **Theme Customization**
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-red: #ff006e;
    --primary-green: #00ff88;
    --primary-blue: #00d4ff;
    --dark-bg: #0a0a0a;
    /* Add your custom colors */
}
```

## 🐛 **Troubleshooting**

### **Common Issues**
1. **CORS Errors**: Most websites block direct access
   - **Solution**: Tool uses multiple proxy services
2. **No Content Extracted**: Website may use JavaScript
   - **Solution**: Shows enhanced simulated content with explanation
3. **PDF Generation Fails**: Large content may timeout
   - **Solution**: Try text-only PDF format

### **Browser Compatibility**
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 📄 **File Structure**

```
content-extractor/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript functionality
└── README.md           # This documentation
```

## 🌟 **Advanced Features**

### **Keyboard Shortcuts**
- `Ctrl/Cmd + Enter`: Extract content from URL
- `Ctrl/Cmd + D`: Download as PDF
- `Ctrl/Cmd + C`: Copy content to clipboard
- `↑↑↓↓←→←→BA`: Activate Rainbow Mode

### **Hidden Features**
- **Double-click** extracted content to download as text file
- **Hover** over tables for cell highlighting
- **RGB particles** respond to mouse movement
- **Parallax scrolling** effects on header

### **Performance Optimizations**
- **Lazy loading** for heavy content
- **Debounced** mouse events
- **Optimized** animations with CSS transforms
- **Efficient** DOM manipulation

## 📊 **Content Types Supported**

### **Table Extraction**
- ✅ Table headers (th)
- ✅ Table data cells (td)
- ✅ Table captions
- ✅ Row/column spanning
- ✅ Nested tables

### **List Extraction**
- ✅ Unordered lists (ul)
- ✅ Ordered lists (ol)
- ✅ Nested lists
- ✅ List items (li)

### **Media Extraction**
- ✅ Images with alt text
- ✅ Image captions
- ✅ Responsive image handling
- ✅ External link indicators

## 🔒 **Security & Privacy**

### **Data Handling**
- **No server storage**: All processing in browser
- **No tracking**: No analytics or telemetry
- **Local extraction**: Content processed locally
- **Secure proxies**: Uses trusted CORS services

### **Privacy Features**
- No data sent to external servers
- No cookies or local storage used
- Content processed in browser only
- Optional metadata inclusion

## 🎯 **Use Cases**

### **For Researchers**
- Extract research data from tables
- Preserve citation formatting
- Download structured content
- Maintain reference links

### **For Content Creators**
- Extract competitor analysis
- Save formatted content
- Preserve table data
- Export to multiple formats

### **For Students**
- Extract study materials
- Preserve data tables
- Download formatted notes
- Copy content easily

## 🚀 **Future Enhancements**

### **Planned Features**
- [ ] Server-side proxy option
- [ ] Batch URL processing
- [ ] Custom CSS themes
- [ ] Export to Excel/CSV
- [ ] Image gallery view
- [ ] Content search within extractor

### **Performance Improvements**
- [ ] Web Workers for heavy processing
- [ ] Progressive content loading
- [ ] Optimized PDF generation
- [ ] Cached extraction results

## 📞 **Support**

### **Getting Help**
- Check browser console for error details
- Verify URL is accessible
- Try different proxy services
- Test with simpler webpages

### **Contributing**
- Fork the repository
- Create feature branches
- Submit pull requests
- Report issues with details

---

## 🌈 **Enjoy the RGB Experience!**

This content extractor combines powerful functionality with stunning RGB animations to make web content extraction both effective and visually appealing. The tool preserves original formatting while providing a modern, animated user experience.

**Made with ❤️ and RGB colors** 🎨
