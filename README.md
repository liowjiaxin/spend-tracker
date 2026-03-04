# 💰 Spend Tracker

A minimal, fast, and beautiful expense tracking web app. Track your spending across categories, analyze trends, and manage your finances with an intuitive interface optimized for mobile.

## Features

### 📝 Quick Entry
- **Numpad Input**: Fast number entry with familiar calculator-style interface
- **7 Categories**: Food, Transport, Shopping, Health, Entertainment, Bills, and Other
- **Custom Notes**: Add descriptions to each transaction for better tracking
- **Date Selection**: Specify transaction dates with an integrated calendar picker
- **Auto-Save**: All entries are automatically saved to your device

### 📊 Analytics
- **Income Breakdown**: Visualize spending by category with progress bars
- **Multiple Views**: Analyze spending by Month, Year, or All Time
- **6-Month Trend**: See spending patterns with a visual trend chart
- **Transaction Count**: Track the number of transactions in each period

### 📜 History
- **Full Transaction Log**: Browse all your entries with dates and notes
- **Swipe to Delete**: Remove entries with a simple swipe gesture
- **Category Filtering**: View transactions across different time periods
- **Sortable Views**: Organize by Month, Year, or All Time

### 💾 Data Management
- **Local Storage**: All data stored securely on your device
- **Export Backup**: Save your data as JSON for backup
- **Import Backup**: Restore data from a previous backup (merges with existing data)
- **Export to TXT**: Export transactions as plain text
- **Save as PDF**: Print or export your analysis as PDF

### 📱 Mobile-Optimized
- **Responsive Design**: Built with mobile-first approach
- **Safe Area Support**: Handles notches and safe areas on modern phones
- **Dark Theme**: Easy on the eyes with a dark color scheme
- **Installable**: Add to home screen on iOS and Android (PWA)

## Getting Started

### Basic Usage

1. **Open the App**: Open `index.html` in a web browser
2. **Add an Entry**: 
   - Select a category
   - Enter an amount using the numpad
   - Optionally add a note
   - Choose a date (defaults to today)
   - Tap "Add"
3. **View Analytics**: Switch to the Analysis tab to see spending breakdown and trends
4. **Browse History**: Check the History tab to view all transactions

### Categories

- 🍜 **Food**: Restaurants, groceries, meals
- 🚇 **Transport**: Public transit, rideshare, gas
- 🛍️ **Shopping**: Clothes, retail, goods
- 💊 **Health**: Medical, fitness, wellness
- 🎮 **Fun**: Entertainment, hobbies, games
- 📋 **Bills**: Utilities, rent, subscriptions
- 📦 **Other**: Everything else

## Data Storage

- **Location**: Browser's localStorage (persistent across sessions)
- **Format**: JSON
- **Key**: `spndtrk_v5`
- **Privacy**: All data stays on your device—no cloud sync or tracking

## Backup & Restore

### Export Backup
1. Go to Analysis tab
2. Tap "Export backup"
3. JSON data is copied (or downloaded)
4. Save it somewhere safe

### Import Backup
1. Go to Analysis tab
2. Tap "Import backup"
3. Paste your backup JSON
4. Confirm import (new data merges with existing)

## Technical Details

- **Built With**: Vanilla HTML5, CSS3, JavaScript
- **Framework**: None (single HTML file)
- **Browser Support**: Modern browsers (iOS Safari, Chrome, Firefox, Edge)
- **Storage**: Browser localStorage (~5-10MB available)
- **Offline**: Works completely offline once loaded
- **Size**: ~23KB minified

## Keyboard Shortcuts

- **Numpad**: Use number keys to enter amounts
- **Backspace**: Delete last digit
- **C Button**: Clear all digits
- **Enter**: Add entry (when focus is on Add button)

## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome/Edge | ✅ Full support |
| Firefox | ✅ Full support |
| iOS Safari | ✅ Full support |
| Samsung Internet | ✅ Full support |

## Installation

### As a Web App (PWA)

**iOS:**
1. Open in Safari
2. Tap Share → Add to Home Screen
3. Name it "Spend" and tap Add

**Android:**
1. Open in Chrome
2. Tap the menu (⋮) → "Add to Home Screen"
3. Name it "Spend" and tap Add

## Privacy & Data

- ✅ No cloud storage
- ✅ No tracking or analytics
- ✅ No ads
- ✅ No account required
- ✅ All data stays on your device
- ✅ Only localStorage permissions needed

## License

Open source and free to use.

## Tips & Tricks

- **Quick Categorization**: Set your most-used category to make entries faster
- **Regular Backups**: Export your data monthly as a precaution
- **Date Range Analysis**: Use History view with different time filters
- **PDF Reports**: Export PDF for expense reports or personal records
- **Offline Access**: Bookmark or install as PWA for quick access anytime