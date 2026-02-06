# HemaScan Pro - Blood Cell Analysis System

## 📁 File Structure

This system consists of 10 HTML files and 1 common CSS file:

### Main Files:
1. **index.html** - Main dashboard/home page
2. **camera.html** - Live camera with real-time cell detection
3. **gallery.html** - Image upload and analysis
4. **analysis.html** - View last 5 analysis reports
5. **filters.html** - Live and gallery image filters
6. **export.html** - Export data to CSV format
7. **settings.html** - App configuration
8. **help.html** - User manual and instructions
9. **clinical.html** - Clinical mode switcher (dark theme)
10. **common-styles.css** - Shared CSS for all pages

## 🚀 How to Use

### Installation:
1. Download all files to your mobile device
2. Open **index.html** in your mobile browser
3. For best experience, add to home screen (works as PWA)

### Features:

#### 📷 Camera (camera.html)
- Real-time blood cell detection
- Green circles mark Red Blood Cells (RBC)
- Red circles mark White Blood Cells (WBC)
- Live statistics: total cells, RBC, WBC, FPS
- Capture and save snapshots with annotations
- Works with device rear camera

#### 🖼️ Gallery (gallery.html)
- Open device gallery to select images
- Automatic cell detection on uploaded images
- Colored circles mark detected cells
- Statistics: total cells, RBC/WBC ratio, confidence
- Results saved for later review

#### 📊 Analysis (analysis.html)
- View last 5 analysis sessions
- Statistics: total readings, averages, success rate
- Trend analysis with visual indicators
- Detailed breakdown of each reading
- Date, time, and source tracking

#### 🔧 Filters (filters.html)
- **Live Filter Mode**: Apply filters to camera feed
- **Gallery Filter Mode**: Process uploaded images
- Available filters:
  - None, Grayscale, Contrast, Brightness
  - Blur, Sharpen, Edge, Invert, Threshold
- Real-time filter preview
- Adjustable filter strength

#### 📤 Export (export.html)
- Export all analysis data as CSV
- Customizable export options:
  - Include/exclude timestamps
  - Include/exclude cell counts
  - Include/exclude source info
  - Include/exclude confidence levels
- Preview before export
- Share via messaging/email apps
- Compatible with Excel and Google Sheets

#### ⚙️ Settings (settings.html)
- **Display Settings**: Dark mode, cell markers, statistics
- **Detection Settings**: 
  - Sensitivity adjustment (0-100%)
  - Processing interval (1-30 FPS)
  - Auto-save toggle
- **Camera Settings**: 
  - Quality selection (480p, 720p, 1080p)
  - Flash mode (off, on, auto)
- **Data Management**: View storage usage, total readings

#### ❓ Help (help.html)
- Complete user manual
- Step-by-step instructions for each feature
- Best practices for accurate detection
- Important medical disclaimer
- Technical support information

#### 🩺 Clinical Mode (clinical.html)
- Switch between Standard (light) and Clinical (dark) themes
- Standard Mode: Bright interface for well-lit environments
- Clinical Mode: Dark theme for reduced eye strain
- Theme applies across entire application
- Preview before applying

## 🎨 Design Features

### Neumorphic Design:
- Soft, modern UI with depth effects
- Smooth shadows and highlights
- Touch-responsive buttons
- Professional medical aesthetic

### Responsive Layout:
- Optimized for mobile devices (420px width)
- Works on phones and tablets
- Touch-friendly interface
- Smooth animations

### Dark Mode Support:
- Clinical mode available throughout app
- Reduces eye strain during extended use
- Better for low-light environments
- OLED-friendly for battery saving

## 💾 Data Storage

- All data stored in browser localStorage
- Automatically saves analysis readings
- Keeps last 100 readings
- Export to CSV for backup
- Clear data option in Analysis page

## 🔒 Privacy & Security

- All processing done locally on device
- No data sent to external servers
- Camera access only when explicitly granted
- Data stored only on your device

## 📱 Browser Compatibility

- Chrome for Android (recommended)
- Firefox for Android
- Samsung Internet
- Safari for iOS
- Any modern mobile browser with camera API support

## ⚠️ Important Notes

### Medical Disclaimer:
HemaScan Pro is a screening tool and NOT a substitute for professional medical diagnosis. All results should be verified by qualified medical personnel using standard laboratory procedures.

### Best Practices:
1. Use proper microscope lighting
2. Ensure blood smear is properly stained
3. Focus camera/microscope before detection
4. Keep device stable during live analysis
5. Process multiple samples for accuracy
6. Regularly backup data using Export
7. Clean camera lens for optimal quality

## 🔧 Technical Requirements

- Mobile device with camera
- Modern web browser (Chrome, Firefox, Safari)
- Camera permission granted
- Minimum 100MB free storage
- Good lighting conditions

## 📞 Support

For questions or issues:
- Email: support@hemascanpro.com
- Version: 1.0.0
- Last Updated: February 2026

## 🎯 Navigation

All pages include Home and Close buttons:
- **🏠 Home** - Return to main dashboard
- **❌ Close** - Exit current page

Pages are interconnected - tap any icon on the dashboard to navigate to that feature.

---

**Developed for clinical blood cell analysis and educational purposes.**
