# Acceleronix Bootcamp

A training assessment platform for Acceleronix's Bootcamp. Features six customer case studies designed to test BD and sales team knowledge of Acceleronix IoT and Connectivity platforms.

## 🌟 Features

- **Training Assessment Portal**: Professional interface for customer case evaluations
- **Six Assessment Scenarios**: Real-world customer challenges across different industries
- **Interactive Case Studies**: Detailed technical requirements and business contexts
- **Hero Banners**: Visual case study presentations with product imagery
- **Acceleronix Branding**: Consistent with company training materials

## 📁 Project Structure

```
all-hands-demo/
├── index.html                 # Homepage with case study overview
├── assets/
│   ├── css/
│   │   ├── home.css          # Homepage styles
│   │   ├── styles.css        # Case study page styles
│   │   ├── greenride-theme.css  # GreenRide theme
│   │   └── solarpulse-theme.css # SolarPulse theme
│   └── images/
│       ├── Cold-Chain.jpg    # AccelTech banner
│       ├── two_wheeler.jpg   # GreenRide banner
│       ├── powerstation.png  # SolarPulse banner
│       ├── smart_lighting.jpeg  # SmartGlow banner
│       ├── heart_pump.png    # HeatFlow banner
│       └── nitrogen-generator.jpeg  # NitroGen banner
├── cases/
│   ├── acceltech.html        # Case A: Cold Chain Logistics
│   ├── mototrack.html        # Case B: Smart e-Bike IoT
│   ├── powerflow.html        # Case C: Solar Energy Storage
│   ├── smartglow.html        # Case D: Smart Lighting
│   ├── heatflow.html         # Case E: Heat Pump
│   └── nitrogen.html         # Case F: Nitrogen Generation
├── vercel.json               # Vercel deployment configuration
├── CLAUDE.md                 # AI assistant guidance
└── README.md                 # Project documentation
```

## 🎯 Assessment Cases

### Case A: AccelTech - Cold Chain Logistics
- **Location**: 🇸🇪 Sweden
- **Industry**: Cold Chain Logistics & Tracking
- **Technology**: Cat.1 Connectivity
- **Scale**: 5K EAU
- **Focus**: Temperature monitoring, trajectory playback, OTA updates
- **Assessment**: IoT platform architecture, connectivity optimization, fleet management

### Case B: GreenRide - Smart e-Bike IoT Solution
- **Location**: 🇬🇧 UK
- **Industry**: Smart Mobility & Green Transportation
- **Technology**: Cat.1 Connectivity
- **Scale**: 3K EAU
- **Focus**: Anti-theft, battery management, sustainable mobility
- **Assessment**: IoT architecture, OTA upgrades, GPS recovery, urban coverage

### Case C: SolarPulse - Mobile Solar Energy Storage
- **Location**: 🇩🇪 Germany
- **Industry**: Solar Energy & Portable Power
- **Technology**: WiFi/BLE Connectivity
- **Scale**: 6K EAU
- **Focus**: Solar optimization, grid feed-in control, app integration
- **Assessment**: Climate adaptation, subscription services, market expansion

### Case D: SmartGlow - Smart Lighting Solution
- **Location**: 🇱🇻 Latvia
- **Industry**: Smart Home - Intelligent Lighting
- **Technology**: Quectel FC41D (WiFi+BLE)
- **Scale**: 8K EAU
- **Focus**: Multi-color control, voice assistants, scene management
- **Assessment**: WiFi+BLE connectivity, smart home ecosystem integration, GDPR compliance

### Case E: HeatFlow - Smart Heat Pump Solution
- **Location**: 🇫🇷 France
- **Industry**: Smart Energy - Heat Pump Systems
- **Technology**: Quectel QCI001 4G DTU (EG810MEULA-I05-SNNSA)
- **Scale**: 10K EAU
- **Focus**: Predictive maintenance, voice control, government incentive alignment
- **Assessment**: 4G LTE connectivity, AI-powered predictive maintenance, end-to-end business model

### Case F: NitroGen - Industrial Nitrogen Generation
- **Location**: 🇮🇹 Italy
- **Industry**: Industrial Gas Production
- **Technology**: Quectel EC200U-EU (4G LTE)
- **Scale**: 12K EAU
- **Focus**: Renewable energy integration, ESG reporting, digital factory transformation
- **Assessment**: Industrial 4G LTE connectivity, sustainability tracking, remote facility management

## 🚀 Deployment

### Deploy to Vercel

1. **Via GitHub Integration** (Recommended):
   ```bash
   # Push to GitHub repository
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin your-github-repo-url
   git push -u origin main
   
   # Then connect to Vercel via dashboard
   ```

2. **Via Vercel CLI**:
   ```bash
   # Install Vercel CLI
   npm i -g vercel
   
   # Deploy
   vercel
   
   # Follow the prompts
   ```

3. **Via Drag & Drop**:
   - Visit [vercel.com](https://vercel.com)
   - Drag the project folder to the deployment area

### Local Development

```bash
# Serve locally using Python
python3 -m http.server 8000

# Or using Node.js
npx serve .

# Visit http://localhost:8000
```

## 🛠 Technical Details

### Technologies Used
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Grid/Flexbox
- **JavaScript**: Interactive navigation and smooth scrolling
- **Google Fonts**: Inter font family

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Performance Optimizations
- Optimized CSS with efficient selectors
- Minimal JavaScript footprint
- Responsive images and layouts
- CDN-hosted fonts

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (container max-width)
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: <480px

## 🎨 Design System

### Color Palette
- **Primary Gradient**: #667eea → #764ba2
- **Background**: #fafafa
- **Cards**: #ffffff
- **Text**: #333333 (primary), #666666 (secondary)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700
- **Hierarchy**: Consistent heading and body text sizes

## 🎤 Training Context

### Event Details
- **Event**: Acceleronix All Hands - EMEA
- **Location**: Belgrade, Serbia
- **Date**: October 2025
- **Duration**: 3-day training program

### Training Focus
- **Acceleronix IoT Platform**: Device management, analytics, fleet tracking
- **Connectivity Platform**: SIM management, multi-carrier support, cost optimization
- **Solution Architecture**: End-to-end design, hardware selection
- **Business Value**: ROI calculation, competitive positioning

### Assessment Purpose
- Test knowledge application from 3-day training
- Evaluate BD and sales team readiness across EMEA markets
- Practice customer scenario solutions with regional context
- Platform feature utilization assessment
- Demonstrate understanding of diverse connectivity technologies (Cat.1, 4G LTE, WiFi/BLE)

## 📄 License

This project is for demonstration purposes. All content is fictional and created for portfolio/showcase use.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test responsiveness across devices
5. Submit a pull request

## 📞 Support

For questions or issues:
- Create an issue in the GitHub repository
- Check the browser console for any errors
- Ensure all file paths are correct for deployment

---

**Live Demo**: [Deploy to see live version]
**Repository**: [GitHub repository URL]
