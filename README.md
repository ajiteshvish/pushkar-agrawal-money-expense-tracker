# 🌐 Web3 Expense Tracker

<div align="center">

![Web3 Expense Tracker](https://img.shields.io/badge/Web3-Expense%20Tracker-00ff41?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-ff006e?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-8338ec?style=for-the-badge)

**A futuristic, cyberpunk-themed expense tracking application with Web3 aesthetics**

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Usage](#-usage) • [Technologies](#-technologies) • [Contributing](#-contributing)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [UI/UX Design](#-uiux-design)
- [Core Functionality](#-core-functionality)
- [Data Management](#-data-management)
- [Export Options](#-export-options)
- [Browser Compatibility](#-browser-compatibility)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🎯 Overview

**Web3 Expense Tracker** is a modern, feature-rich personal finance management application designed with a cutting-edge cyberpunk aesthetic. Built with vanilla JavaScript, HTML5, and CSS3, this application provides a seamless experience for tracking income and expenses with real-time visualizations and advanced filtering capabilities.

The application features a unique **terminal-inspired UI** with neon green accents, hexagonal card designs, and animated particle backgrounds, creating an immersive Web3 experience.

---

## ✨ Features

### 💰 Financial Management
- **Income & Expense Tracking**: Add, edit, and delete transactions with detailed information
- **Real-time Balance Calculation**: Automatic calculation of total income, expenses, and current balance
- **Multiple Categories**: 10 pre-defined categories including Food, Transport, Shopping, Bills, Entertainment, Health, Education, Salary, Investment, and Other
- **Payment Methods**: Support for Cash, Card, UPI, and Crypto Wallet payments
- **Transaction Notes**: Optional description field for additional transaction details

### 🎨 Advanced UI/UX
- **Cyberpunk Theme**: Terminal-inspired design with neon green (#00ff41) primary color
- **Hexagonal Cards**: Unique polygon-clipped balance cards with 3D hover effects
- **Animated Background**: Dynamic particle system with connecting lines
- **Glitch Text Effects**: Futuristic text animations on the main title
- **Neon Glow Effects**: Multiple shadow layers creating authentic neon lighting
- **Wireframe Corners**: Technical blueprint-style panel decorations
- **Smooth Animations**: CSS transitions and keyframe animations throughout
- **Responsive Design**: Fully responsive layout for all device sizes

### 📊 Data Visualization
- **Category-wise Pie Chart**: Visual breakdown of expenses by category
- **Income vs Expense Bar Chart**: Comparative analysis with gradient fills and glow effects
- **Real-time Chart Updates**: Charts automatically update when transactions change
- **Custom Canvas Rendering**: Hand-coded chart implementation without external libraries

### 🔍 Filtering & Search
- **Real-time Search**: Instant search across transaction titles and descriptions
- **Category Filter**: Filter transactions by specific categories
- **Type Filter**: Separate income and expense transactions
- **Payment Method Filter**: Filter by payment method
- **Combined Filters**: Multiple filters work simultaneously

### 💾 Data Management
- **Local Storage**: Automatic data persistence using browser localStorage
- **Export to CSV**: Download transactions in CSV format for Excel/Sheets
- **Export to JSON**: Export data in JSON format for backup or migration
- **Auto-save**: All changes are automatically saved

### 🎭 Theme Support
- **Dark Mode**: Default cyberpunk dark theme
- **Light Mode**: Alternative light theme with theme toggle button
- **Persistent Theme**: Theme preference saved across sessions

### 🔔 User Feedback
- **Toast Notifications**: Elegant notification system for user actions
- **Success Messages**: Confirmation for add, update, delete operations
- **Error Handling**: Graceful handling of edge cases
- **Empty States**: Informative messages when no data is available

### 🎮 Interactive Elements
- **3D Tilt Effect**: Mouse-tracking 3D rotation on balance cards
- **Hover Animations**: Interactive hover states on all clickable elements
- **Smooth Scrolling**: Auto-scroll to form when editing transactions
- **Button Feedback**: Visual feedback on all button interactions

---

## 🎬 Demo

### Screenshots

#### Main Dashboard
- Hexagonal balance cards showing Total Income, Current Balance, and Total Expense
- Animated particle background with connecting lines
- Neon green terminal-style interface

#### Transaction Form
- Clean, organized form with multiple input fields
- Category and payment method dropdowns with emoji icons
- Terminal-style input fields with neon borders

#### Transaction List
- Detailed transaction cards with all information
- Edit and delete buttons for each transaction
- Color-coded income (green) and expense (pink) amounts

#### Charts Section
- Category-wise spending pie chart
- Income vs Expense bar chart with gradients
- Real-time updates based on transaction data

---

## 🚀 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/web3-expense-tracker.git
   ```

2. **Navigate to project directory**
   ```bash
   cd web3-expense-tracker
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server (optional)
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

### Alternative: Direct Download
1. Download the ZIP file from the repository
2. Extract the contents
3. Open `index.html` in your web browser

---

## 📖 Usage

### Adding a Transaction

1. **Fill in the form fields:**
   - **Title**: Name of the transaction (e.g., "Grocery Shopping")
   - **Amount**: Transaction amount (e.g., 1500.00)
   - **Category**: Select from dropdown (Food, Transport, etc.)
   - **Date**: Pick transaction date (defaults to today)
   - **Payment Method**: Choose Cash, Card, UPI, or Crypto
   - **Type**: Select Income or Expense
   - **Description**: Optional notes about the transaction

2. **Click "Add Transaction"** button

3. **View the transaction** in the list below

### Editing a Transaction

1. Click the **✏️ Edit** button on any transaction card
2. Form will populate with transaction data
3. Modify the fields as needed
4. Click **"Update Transaction"** button

### Deleting a Transaction

1. Click the **🗑️ Delete** button on any transaction card
2. Transaction will be removed immediately
3. All totals and charts update automatically

### Filtering Transactions

1. **Search**: Type in the search box to filter by title or description
2. **Category Filter**: Select a category from the dropdown
3. **Type Filter**: Choose Income, Expense, or All
4. **Payment Filter**: Filter by payment method
5. **Combine filters** for more specific results

### Exporting Data

1. **CSV Export**: Click "Export CSV" to download Excel-compatible file
2. **JSON Export**: Click "Export JSON" to download JSON backup

### Changing Theme

1. Click the **hexagonal theme toggle** button in the top-right corner
2. Toggle between dark and light modes
3. Theme preference is saved automatically

---

## 📁 Project Structure

```
web3-expense-tracker/
│
├── index.html              # Main HTML structure
├── style.css               # Cyberpunk UI styles and animations
├── script.js               # Core application logic
├── bg-animation.js         # Particle background animation
└── README.md              # Project documentation
```

### File Descriptions

#### `index.html` (Main Structure)
- Semantic HTML5 structure
- Balance summary cards section
- Transaction form with all input fields
- Filter and search controls
- Transaction list container
- Chart canvas elements
- Footer with credits

#### `style.css` (Styling & Animations)
- **CSS Variables**: Customizable color scheme
- **Hexagonal Cards**: Polygon clip-path designs
- **Neon Effects**: Multiple text-shadow and box-shadow layers
- **Animations**: Keyframe animations for glitch, spin, float effects
- **Grid Background**: Animated radial gradients
- **Responsive Design**: Media queries for mobile devices
- **Terminal Font**: Courier New monospace typography

#### `script.js` (Application Logic)
- **Transaction Management**: CRUD operations
- **Local Storage**: Data persistence
- **Chart Rendering**: Custom canvas-based charts
- **Filtering System**: Real-time search and filters
- **Export Functions**: CSV and JSON generation
- **Theme Toggle**: Dark/light mode switching
- **Notifications**: Toast notification system
- **3D Tilt Effect**: Mouse-tracking animations

#### `bg-animation.js` (Background Animation)
- **Particle System**: 80 animated particles
- **Connection Lines**: Dynamic line drawing between nearby particles
- **Canvas Rendering**: Optimized animation loop
- **Gradient Effects**: Radial and linear gradients
- **Responsive**: Adapts to window resize

---

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with custom properties
- **JavaScript (ES6+)**: Modern vanilla JavaScript

### Key Features & APIs
- **Canvas API**: Custom chart rendering and particle animation
- **Local Storage API**: Client-side data persistence
- **Blob API**: File generation for exports
- **Date API**: Date formatting and manipulation
- **DOM API**: Dynamic content rendering

### Design Patterns
- **Module Pattern**: Organized code structure
- **Event-Driven**: Event listeners for user interactions
- **Functional Programming**: Pure functions for calculations
- **Object-Oriented**: Particle class for background animation

### No External Dependencies
- ✅ No jQuery
- ✅ No React/Vue/Angular
- ✅ No Chart.js or other libraries
- ✅ Pure vanilla JavaScript
- ✅ Zero build process required

---

## 🎨 UI/UX Design

### Color Palette

```css
Primary Glow:    #00ff41 (Neon Green)
Secondary Glow:  #ff006e (Hot Pink)
Accent Glow:     #8338ec (Purple)
Background:      #000000 (Pure Black)
Card Background: #0a0a0a (Near Black)
```

### Typography
- **Font Family**: Courier New (Monospace)
- **Letter Spacing**: Wide spacing for futuristic feel
- **Text Transform**: Uppercase for labels and titles
- **Font Weights**: 700-900 for bold, impactful text

### Design Elements

#### Hexagonal Cards
```css
clip-path: polygon(20% 0%, 80% 0%, 100% 20%, 100% 80%, 80% 100%, 20% 100%, 0% 80%, 0% 20%);
```

#### Neon Glow Effect
```css
text-shadow: 
    0 0 10px var(--primary-glow),
    0 0 20px var(--primary-glow),
    0 0 40px var(--primary-glow),
    0 0 80px var(--primary-glow);
```

#### Animated Borders
- Rotating hue animation
- Gradient border flows
- Pulsing scan lines

### Animations

1. **Glitch Text**: Random position shifts
2. **Hex Spin**: 360° rotation
3. **Icon Float**: Vertical oscillation
4. **Border Pulse**: Opacity and glow changes
5. **Scan Line**: Horizontal sweep effect
6. **Grid Move**: Background pattern animation

---

## ⚙️ Core Functionality

### Transaction Management

```javascript
// Transaction Object Structure
{
    id: 1234567890,           // Unique timestamp ID
    title: "Grocery Shopping", // Transaction name
    amount: 1500.00,          // Numeric amount
    category: "Food",         // Category selection
    date: "2024-12-01",       // ISO date format
    description: "Weekly groceries", // Optional notes
    paymentMethod: "Card",    // Payment type
    type: "Expense"           // Income or Expense
}
```

### CRUD Operations

- **Create**: Add new transaction with form validation
- **Read**: Display all transactions with filtering
- **Update**: Edit existing transaction in-place
- **Delete**: Remove transaction with confirmation

### Calculations

```javascript
// Real-time calculations
Total Income = Sum of all Income transactions
Total Expense = Sum of all Expense transactions
Current Balance = Total Income - Total Expense
```

### Data Flow

1. User submits form
2. Data validated and processed
3. Transaction added to array
4. Saved to localStorage
5. UI updated (summary, list, charts)
6. Notification displayed

---

## 💾 Data Management

### Local Storage

```javascript
// Storage Key
'web3_transactions'

// Data Format
JSON array of transaction objects

// Operations
- Save: After every add/edit/delete
- Load: On page load
- Clear: Manual (not implemented)
```

### Data Persistence

- Automatic save on all changes
- Survives browser refresh
- Persists across sessions
- No server required

### Data Export

#### CSV Format
```csv
Title,Amount,Category,Date,Description,Payment Method,Type
Grocery Shopping,1500.00,Food,2024-12-01,Weekly groceries,Card,Expense
```

#### JSON Format
```json
[
  {
    "id": 1234567890,
    "title": "Grocery Shopping",
    "amount": 1500.00,
    "category": "Food",
    "date": "2024-12-01",
    "description": "Weekly groceries",
    "paymentMethod": "Card",
    "type": "Expense"
  }
]
```

---

## 📤 Export Options

### CSV Export
- **Use Case**: Import into Excel, Google Sheets, or other spreadsheet software
- **Format**: Comma-separated values with headers
- **Filename**: `transactions.csv`
- **Encoding**: UTF-8

### JSON Export
- **Use Case**: Backup, migration, or data analysis
- **Format**: Pretty-printed JSON with 2-space indentation
- **Filename**: `transactions.json`
- **Structure**: Array of transaction objects

### Export Process
1. Click export button
2. Data converted to format
3. Blob created with MIME type
4. Download triggered automatically
5. File saved to default download location

---

## 🌐 Browser Compatibility

### Fully Supported
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

### Required Features
- CSS Grid & Flexbox
- CSS Custom Properties
- Canvas API
- Local Storage API
- ES6+ JavaScript
- Clip-path support

### Mobile Support
- ✅ iOS Safari 14+
- ✅ Chrome Mobile 90+
- ✅ Samsung Internet 14+
- ✅ Firefox Mobile 88+

---

## 🚀 Future Enhancements

### Planned Features

#### Phase 1: Enhanced Functionality
- [ ] Budget setting and tracking
- [ ] Recurring transactions
- [ ] Transaction categories customization
- [ ] Multi-currency support
- [ ] Date range filtering

#### Phase 2: Advanced Analytics
- [ ] Monthly/yearly reports
- [ ] Spending trends analysis
- [ ] Budget vs actual comparison
- [ ] Savings goals tracker
- [ ] Financial insights and tips

#### Phase 3: Data & Integration
- [ ] Cloud sync (Firebase/Supabase)
- [ ] Import from CSV/JSON
- [ ] PDF report generation
- [ ] Email reports
- [ ] API integration

#### Phase 4: Web3 Integration
- [ ] Crypto wallet connection
- [ ] Blockchain transaction tracking
- [ ] NFT expense categories
- [ ] DeFi protocol integration
- [ ] Smart contract interactions

#### Phase 5: Social Features
- [ ] Shared expense tracking
- [ ] Group budgets
- [ ] Expense splitting
- [ ] Social comparisons
- [ ] Leaderboards

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Contribution Guidelines

- Follow existing code style
- Add comments for complex logic
- Test thoroughly before submitting
- Update README if adding features
- Keep commits atomic and descriptive

### Bug Reports

Found a bug? Please open an issue with:
- Clear description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable
- Browser and OS information

---

## 📄 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2024 Lakshita Kannaujia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👤 Author

**Lakshita Kannaujia**

- GitHub: [@lakshitakannaujia](https://github.com/lakshitakannaujia)
- Email: lakshita@example.com

---

## 🙏 Acknowledgments

- Inspired by Web3 and cyberpunk aesthetics
- Built with passion for modern web design
- Thanks to the open-source community

---

## 📞 Support

If you like this project, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🤝 Contributing code
- 📢 Sharing with others

---

<div align="center">

**Made with 💚 by Lakshita Kannaujia**

⬡ Built with Web3 Aesthetics ⬡

</div>
