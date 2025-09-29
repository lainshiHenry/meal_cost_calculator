# 🍽️ Meal Cost Calculator

A simple, mobile-first web application for calculating the total cost of your meal including tax and tips, with real-time budget tracking.

![Meal Cost Calculator](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

- **Real-time Calculations** - Automatically updates totals as you enter costs
- **Budget Tracking** - Set a budget and instantly see if you're over or under
- **Customizable Tax & Tips** - Adjust tax and tip percentages to match your needs
- **Mobile-Optimized** - Responsive design perfect for use on your phone at restaurants
- **Clean Interface** - Modern, intuitive design with gradient styling
- **No Dependencies** - Pure HTML, CSS, and JavaScript - no frameworks required

## 🚀 Demo

Simply open `index.html` in any modern web browser to start using the calculator.

## 📱 Usage

1. **Set Your Budget** - Enter your meal budget at the top
2. **Add Meal Items** - Fill in the name and cost for each item:
   - Entree 1
   - Entrée 2
   - Alcoholic Beverage
   - Appetizer/Dessert
3. **Adjust Tax & Tips** - Modify the percentage values if needed (defaults: 12% tax, 10% tips)
4. **Monitor Your Total** - Watch your total update in real-time
   - Green indicator: Under budget ✅
   - Red indicator: Over budget ⚠️

## 💻 Installation

### Option 1: Download
```bash
# Clone the repository
git clone https://github.com/yourusername/meal-cost-calculator.git

# Navigate to the directory
cd meal-cost-calculator

# Open in your browser
open index.html
```

### Option 2: Direct Use
Simply download the `index.html` file and open it in any web browser. No installation or build process required!

## 🛠️ Technical Details

- **Pure Vanilla JavaScript** - No frameworks or libraries
- **Responsive Design** - Works on all device sizes
- **Browser Compatibility** - Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- **Lightweight** - Single HTML file under 10KB

## 📋 Default Values

- **Budget**: $140
- **Tax Rate**: 12%
- **Tip Rate**: 10%
- **All Costs**: $0

All values are fully editable and update calculations instantly.

## 🎨 Customization

You can easily customize the calculator by editing the HTML file:

- **Colors**: Modify the gradient in the CSS (`.body` and `.summary-section`)
- **Default Values**: Change initial values in the HTML input fields
- **Tax/Tip Defaults**: Adjust the `value` attribute in the percentage inputs

## 📝 Example Calculation

```
Entree 1:           $25.00
Entrée 2:           $30.00
Alcoholic Beverage: $12.00
App/Desert:         $10.00
------------------------
Subtotal:           $77.00
Tax (12%):           $9.24
Tips (10%):          $7.70
------------------------
Total:              $93.94

Budget: $140.00
Remaining: $46.06 ✅
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 💡 Future Enhancements

- [ ] Save meal history
- [ ] Split bill between multiple people
- [ ] Currency conversion support
- [ ] Dark mode toggle
- [ ] Export receipt as PDF
- [ ] Add service charge option

## 📄 License

This project is licensed under the MIT License - feel free to use it for personal or commercial projects.

## 👨‍💻 Author

Created with ❤️ for making dining out more budget-friendly.

## 🙏 Acknowledgments

- Inspired by the need for quick meal cost calculations while dining out
- Designed with mobile users in mind

---

**Star ⭐ this repository if you find it helpful!**