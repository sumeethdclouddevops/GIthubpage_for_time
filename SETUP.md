# GitHub Pages Operations Dashboard

A complete 24/7 shift management and operations monitoring system hosted on GitHub Pages.

## 🚀 Features

### 1. **Shift Handover Generator** (`handover-generator.html`)
   - Document shift handovers with comprehensive task tracking
   - Agent selection (Agent 1-10, easily expandable)
   - Three shift configurations:
     - Shift 1: 5:30 AM - 3:00 PM IST
     - Shift 2: 2:30 PM - 11:00 PM IST
     - Shift 3: 9:00 PM - 5:50 AM PST
   - Track: Tasks received, completed, pending, ticket details, special notes
   - One-click copy to clipboard
   - Professional formatted output

### 2. **Global DC Timings** (`index.html`)
   - Real-time monitoring of 8 data centers across 2 rings
   - Live analog clock displays
   - Business hours vs Non-Business hours tracking
   - Deployment window planner
   - Countdown timers to shift changes
   - Multi-ring filtering

### 3. **Landing Page** (`landing.html`)
   - Central hub for all operations tools
   - Quick access to all features
   - Shift configuration reference
   - Usage guides and pro tips
   - Feature highlights

## 📁 File Structure

```
GIthubpage_for_time/
├── index.html                    # Global DC Timings Dashboard
├── handover-generator.html       # Shift Handover Generator
├── landing.html                  # Operations Dashboard Hub
├── README.md                     # Detailed documentation
├── SETUP.md                      # Setup instructions
└── .git/                         # Git repository
```

## 🌐 Live URLs (After GitHub Pages Enabled)

Once you enable GitHub Pages in your repository settings:

- **Home/Dashboard**: `https://yourusername.github.io/GIthubpage_for_time/landing.html`
- **DC Timings**: `https://yourusername.github.io/GIthubpage_for_time/index.html`
- **Handover Generator**: `https://yourusername.github.io/GIthubpage_for_time/handover-generator.html`

## ⚙️ Setup Instructions

### 1. **Initialize Git (if not already done)**
```bash
cd GIthubpage_for_time
git init
git add .
git commit -m "Initial commit: Add operations tools"
```

### 2. **Create GitHub Repository**
- Go to https://github.com/new
- Repository name: `GIthubpage_for_time`
- Add description: "24/7 Operations Shift Management & Monitoring"
- Make it **Public** for GitHub Pages
- Create repository

### 3. **Push to GitHub**
```bash
git remote add origin https://github.com/yourusername/GIthubpage_for_time.git
git branch -M main
git push -u origin main
```

### 4. **Enable GitHub Pages**
- Go to repository Settings
- Scroll to "GitHub Pages" section
- Source: Select `main` branch
- Select root folder `/ (root)`
- Click Save

### 5. **Access Your Pages**
Pages will be available at:
- `https://yourusername.github.io/GIthubpage_for_time/landing.html` (recommended entry point)
- `https://yourusername.github.io/GIthubpage_for_time/index.html` (DC timings)
- `https://yourusername.github.io/GIthubpage_for_time/handover-generator.html` (handover tool)

## 🎯 Shift Handover Generator - User Guide

### Features:
- ✅ Select agent (Agent 1-10)
- ✅ Select shift time
- ✅ Enter shift date
- ✅ Choose next agent
- ✅ Document tasks received
- ✅ Document tasks completed
- ✅ List pending tasks
- ✅ Add ticket details
- ✅ Add special notes
- ✅ Generate professional document
- ✅ Copy to clipboard instantly

### How to Use:
1. Select your agent name
2. Click on your shift time
3. Fill in all fields with handover information
4. Click "Generate Handover"
5. Click "Copy to Clipboard"
6. Paste in Slack, Teams, or Email

## 📊 Global DC Timings - User Guide

### Features:
- Real-time clock display for each DC
- Business hours indicator
- Non-Business hours window information
- Countdown timer (when change will occur)
- Product list per DC
- Status indicators
- Deployment planner

### How to Use:
1. View all DCs in real-time
2. Filter by Ring or Status using dropdown
3. Click on DC cards to see products
4. Use "Check Availability" to find deployment windows
5. Monitor countdown timers

## 🔧 Customization Guide

### Add More Agents
Edit `handover-generator.html`:
```html
<!-- Find the agent select dropdowns and add: -->
<option value="Agent11">Agent 11</option>
<option value="Agent12">Agent 12</option>
```

### Modify Shift Times
Edit the shift radio buttons in `handover-generator.html`:
```html
<input type="radio" id="shift1" name="shift" value="Your Custom Time">
<label for="shift1">Your Custom Shift</label>
```

### Change Colors
Edit CSS variables at the top of `index.html`:
```css
:root {
    --sap-blue: #89cff0;
    --sap-gold: #F0AB00;
    /* ... more colors ... */
}
```

### Add New Data Centers
Edit the `dataCenters` array in `index.html`:
```javascript
{ 
    id: 'dc-id', 
    name: 'City (CODE)', 
    zone: 'Timezone/Zone',
    ring: 1 or 2,
    maintStart: 19,
    maintEnd: 7,
    checkType: 'LOCAL'
}
```

## 🔐 Security & Privacy

- ✅ **No Backend**: Runs entirely in browser
- ✅ **No Data Transmission**: All data stays on your device
- ✅ **No Database**: Nothing is stored on servers
- ✅ **No Tracking**: No analytics or tracking code
- ✅ **HTTPS Ready**: Secure when hosted on GitHub Pages

## 📱 Browser Support

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🌟 Key Features

### Handover Generator:
- Modern UI with glassmorphism effects
- Dark mode optimized
- Responsive design
- One-click clipboard copy
- Formatted output
- Print-friendly

### DC Timings:
- Live updates every second
- Analog clock displays
- Multi-timezone support
- Deployment planner
- Status indicators
- Countdown timers

## 💡 Best Practices

### For Handovers:
1. Complete all fields for comprehensive documentation
2. Use clear, concise language
3. Include ticket IDs and status
4. List blockers in Special Notes
5. Copy immediately and share with team

### For DC Monitoring:
1. Check before scheduled maintenance
2. Use the deployment planner in advance
3. Monitor business hours windows
4. Check countdown timers
5. Plan operations around non-business hours

## 🐛 Troubleshooting

### Pages not showing after push?
- Wait 1-2 minutes for GitHub Pages to deploy
- Check that repository is set to Public
- Verify GitHub Pages is enabled in Settings

### Time displays incorrect?
- Browser clock is used - check system time
- Timezones are defined in `index.html`
- Refresh page if times seem wrong

### Copy to clipboard not working?
- Ensure you're using HTTPS (GitHub Pages uses HTTPS)
- Some browsers may ask for permission first
- Try again in a few seconds

## 📞 Support & Updates

This is a self-hosted, open-source solution. For issues:
1. Check the file structure is correct
2. Verify all HTML files are in root directory
3. Clear browser cache and reload
4. Check browser console for errors (F12 → Console tab)

## 📄 Version History

- **v1.0.0** (March 2026): Initial release
  - Shift Handover Generator
  - Global DC Timings
  - Landing page
  - Full documentation

## 📋 Deployment Checklist

- [ ] Create GitHub repository
- [ ] Clone repository locally
- [ ] Add all HTML files
- [ ] Add README.md
- [ ] Commit all files
- [ ] Push to GitHub
- [ ] Enable GitHub Pages
- [ ] Test all URLs
- [ ] Share with team

## 🎓 Learning Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [HTML/CSS/JavaScript Basics](https://developer.mozilla.org/en-US/)
- [Web APIs - Clipboard](https://developer.mozilla.org/en-US/docs/Web/API/Clipboard)

## ✨ Credits

Built as a comprehensive operations management solution for 24/7 shift-based teams.

---

**Last Updated**: March 2026  
**Status**: ✅ Production Ready  
**License**: Open Source

