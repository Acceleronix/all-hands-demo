# Acceleronix All Hands - APAC Training Assessment

A training assessment platform for Acceleronix's Bangkok All Hands meeting (August 2025). Features three customer case studies designed to test BD and sales team knowledge of Acceleronix IoT and Connectivity platforms.

## 🌟 Features

- **Training Assessment Portal**: Professional interface for customer case evaluations
- **Three Assessment Scenarios**: Real-world customer challenges across different industries
- **Interactive Case Studies**: Detailed technical requirements and business contexts
- **Acceleronix Branding**: Consistent with company training materials

## 📁 Project Structure

```
tracker_website/
├── index.html                 # Homepage with case study overview
├── assets/
│   ├── css/
│   │   ├── home.css          # Homepage styles
│   │   └── styles.css        # Case study page styles
│   └── js/                   # (Future JavaScript files)
├── cases/
│   ├── acceltech.html        # AccelTech case study (complete)
│   ├── smartlogistics.html   # SmartLogistics case study (coming soon)
│   └── industrialtech.html   # IndustrialTech case study (coming soon)
├── vercel.json               # Vercel deployment configuration
├── CLAUDE.md                 # AI assistant guidance
└── README.md                 # Project documentation
```

## 🎯 Assessment Cases

### Case A: AccelTech - Cold Chain Logistics
- **Location**: Malaysia
- **Industry**: Cold Chain Logistics
- **Focus**: NB-IoT connectivity, sensor integration, platform scalability
- **Scale**: 5K EAU
- **Assessment**: OTA management, connectivity optimization

### Case B: MotoTrack - Two Wheeler Fleet Management
- **Location**: Vietnam
- **Industry**: Ride-sharing & Delivery
- **Focus**: Battery optimization, connectivity costs, anti-theft solutions
- **Scale**: 25K+ fleet
- **Assessment**: 2G/4G strategy, power management

### Case C: PowerFlow - Mobile Energy Storage
- **Location**: India
- **Industry**: Portable Power Solutions
- **Focus**: Predictive maintenance, remote monitoring, business optimization
- **Scale**: 2K+ units
- **Assessment**: LTE-M connectivity, AI analytics

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
- **Event**: Acceleronix All Hands - APAC
- **Location**: Bangkok, Thailand
- **Date**: August 2025
- **Duration**: 4-day training program

### Training Focus
- **Acceleronix IoT Platform**: Device management, analytics, fleet tracking
- **Connectivity Platform**: SIM management, multi-carrier support, cost optimization
- **Solution Architecture**: End-to-end design, hardware selection
- **Business Value**: ROI calculation, competitive positioning

### Assessment Purpose
- Test knowledge application from 4-day training
- Evaluate BD and sales team readiness
- Practice customer scenario solutions
- Platform feature utilization assessment

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