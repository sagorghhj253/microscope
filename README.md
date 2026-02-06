# HemaScan Pro - Clinical Blood Analysis Application

A professional mobile-optimized web application for blood cell detection and analysis using machine learning.

## 📁 Project Structure

```
hemascan-pro/
├── common-styles.css       # Shared stylesheet for all pages
├── index.html             # Main homepage with navigation
├── camera.html            # Live camera detection with ML
├── gallery.html           # Image upload and analysis
├── analysis.html          # Historical data and reports
├── filters.html           # Image filtering tools
├── export.html            # CSV data export
├── settings.html          # App configuration
└── help.html              # User manual
```

## ✨ Features

### 🔬 Core Functionality
- **Live Camera Detection**: Real-time blood cell detection using TensorFlow.js
- **Gallery Upload**: Analyze images from device gallery
- **ML-Based Detection**: Automatic RBC and WBC counting with visual markers
- **Analysis Reports**: View last 5 readings with statistics
- **Image Filters**: 9 filter types for enhanced detection
- **CSV Export**: Export data with customizable options
- **Dark/Light Theme**: Toggle between Standard and Clinical modes
- **Local Storage**: All data stored securely on device

### 🎨 Design Features
- Neomorphic design with modern UI
- Smooth animations and transitions
- Mobile-first responsive design
- Touch-optimized controls
- Professional medical interface
- Real-time notifications

### 📊 Detection Capabilities
- Total cell count
- Red Blood Cell (RBC) count
- White Blood Cell (WBC) count
- Processing time metrics
- FPS monitoring
- Confidence scoring

## 🚀 How to Use

### Starting the Application
1. Open `index.html` in a web browser
2. Allow camera permissions when prompted
3. Navigate using the icon grid buttons

### Camera Mode (📷)
- Press "Start" to begin live detection
- Cells are automatically marked with colored circles
- Red circles = RBC, Blue circles = WBC
- Press "Capture" to save snapshots
- Press "Stop" to pause detection

### Gallery Mode (🖼️)
- Press "Upload" to select an image
- Image is automatically analyzed
- Detected cells shown with markers
- View detailed count statistics

### Analysis Reports (📊)
- View last 5 analysis results
- See average RBC/WBC counts
- Monitor success rates
- Refresh or clear data

### Filters (🔧)
- Apply 9 different image filters
- Use with live camera or uploaded images
- Adjust filter strength with slider
- Preview changes in real-time

### Export (📤)
- Export all data as CSV
- Customize export options
- Preview before download
- File saved to device downloads

### Settings (⚙️)
- Toggle dark mode (Clinical theme)
- Adjust detection sensitivity
- Set analysis interval
- Enable/disable markers
- Configure auto-save

### Clinical Mode (🩺)
- Click Clinical button on homepage
- Switches entire app to dark theme
- Professional interface for lab environments
- Reduces eye strain

## 🎯 Navigation Buttons

- **▶️ Start**: Begin analysis (goes to camera)
- **⏸️ Stop**: Stop current analysis
- **🏠 Home**: Return to homepage
- **🚪 Exit**: Close application

## 📱 Mobile Optimization

- Responsive design for all screen sizes
- Touch-optimized buttons
- Camera access on mobile devices
- Gallery integration with mobile camera
- Optimized for portrait and landscape

## 🔧 Technical Details

### Technologies Used
- HTML5 Canvas for image processing
- TensorFlow.js for ML detection
- LocalStorage for data persistence
- CSS Variables for theming
- MediaDevices API for camera access

### Browser Requirements
- Modern browser with JavaScript enabled
- Camera access permission
- LocalStorage support
- Canvas API support

### Data Storage
All data is stored locally using browser LocalStorage:
- Analysis readings
- User settings
- Theme preferences
- No server required, complete privacy

## 🎨 Theme System

### Light Theme (Standard Mode)
- Soft blue and white color scheme
- Professional medical interface
- High contrast for clarity

### Dark Theme (Clinical Mode)
- Dark blue and gray colors
- Reduced eye strain
- Professional lab environment feel

## ⚠️ Important Notes

1. This is a demonstration application for educational purposes
2. For actual medical diagnosis, consult qualified healthcare professionals
3. Detection accuracy depends on image quality and lighting
4. All processing is done locally on your device
5. No data is sent to external servers

## 📝 Data Export Format

CSV files include:
- Timestamp
- Total Cells
- RBC Count
- WBC Count
- Processing Time (ms)
- Source (live/image)

## 🔐 Privacy

- 100% local processing
- No data transmitted to servers
- No user tracking
- No external dependencies (except ML library CDN)
- Complete data control

## 💡 Tips for Best Results

1. Ensure good lighting when using camera
2. Clean camera lens before use
3. Hold device steady during detection
4. Use high-quality images for gallery mode
5. Adjust sensitivity in settings for accuracy
6. Enable markers to see detection zones

## 🆘 Troubleshooting

**Camera not working?**
- Check browser permissions
- Ensure HTTPS connection (or localhost)
- Try different browser

**No cells detected?**
- Improve lighting conditions
- Adjust detection sensitivity in settings
- Use image filters to enhance contrast

**App not saving data?**
- Check browser LocalStorage is enabled
- Clear browser cache and reload
- Ensure sufficient storage space

## 📧 Support

For questions or issues, refer to the Help page within the app.

## 🏥 Intended Use

Educational and demonstration purposes only. This application showcases ML-based image analysis techniques and should not be used for actual medical diagnosis without proper validation and professional oversight.

---

**Version**: 1.0.0  
**Last Updated**: February 2026  
**License**: Educational Use Only
