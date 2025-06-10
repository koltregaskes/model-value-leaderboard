# Setup Guide for AI Model Value Leaderboard

## Quick Start Guide

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and create a new repository
2. Name it something like `ai-model-value-leaderboard`
3. Make it public (required for free GitHub Pages)
4. Don't initialize with README (we have our own)

### 2. Upload Files
Upload these files to your repository:
- `README.md` - Main documentation
- `index.html` - Interactive website
- `ai_model_leaderboard.csv` - Raw data
- `.github/workflows/deploy.yml` - Auto-deployment

### 3. Enable GitHub Pages
1. Go to your repository settings
2. Click "Pages" in the left sidebar
3. Under "Source", select "GitHub Actions"
4. Save the settings

### 4. Access Your Site
- Your site will be available at: `https://yourusername.github.io/ai-model-value-leaderboard`
- First deployment takes 2-3 minutes
- Future updates deploy automatically when you push changes

## Files Overview

### README.md
- Comprehensive table with all AI models
- Performance metrics and pricing
- Use case recommendations
- Value calculations explained

### index.html
- Interactive website with sorting and filtering
- Mobile-responsive design
- Real-time search functionality
- Visual indicators for top models

### ai_model_leaderboard.csv
- Raw data for analysis
- Can be imported into Excel or Google Sheets
- Perfect for creating custom charts

## Data Sources Verified

All data has been verified against:
- ✅ Official provider websites (OpenAI, Google, Anthropic, etc.)
- ✅ GPQA benchmark leaderboards
- ✅ LMSYS Chatbot Arena ratings
- ✅ Recent price announcements (including o3 80% price drop)

## Customization

### Adding New Models
1. Edit the `models` array in `index.html`
2. Add new row to table in `README.md`
3. Update CSV file if needed

### Changing Design
- Modify CSS in `index.html` `<style>` section
- Colors, fonts, and layout can be customized
- Mobile-responsive design maintained

### Updating Data
- All pricing and benchmark data should be updated regularly
- Check provider websites monthly for pricing changes
- Monitor benchmark leaderboards for new scores

## Features Included

### Interactive Website
- 🔍 Search by model name, provider, or notes
- 📊 Sort by multiple criteria (value, performance, price)
- 🏷️ Filter by provider
- 📱 Mobile-responsive design
- 🎨 Modern UI with animations

### Value Metrics
- **GPQA/$**: Performance per dollar (reasoning capability)
- **Arena Elo/$**: User preference per dollar
- **Multiple sorting options**: Find best value for your needs

### Visual Indicators
- 🏆 **BEST** badges for top performers
- 🔥 **HOT** badges for recent price drops
- 🆕 **NEW** badges for recently launched models

## Maintenance

### Monthly Updates
- Check for new model releases
- Verify current pricing
- Update benchmark scores
- Add any new providers

### Quarterly Reviews
- Analyze market trends
- Update methodology if needed
- Add new metrics or features
- Review and update recommendations

## License
MIT License - Feel free to fork and customize for your needs.

## Support
If you find errors or have suggestions:
1. Open an issue on GitHub
2. Submit a pull request
3. Check official provider websites for latest pricing