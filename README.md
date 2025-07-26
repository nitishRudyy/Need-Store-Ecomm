# Need-Store-Ecomm Website    " https://need-store.netlify.app/"

A modern e-commerce website built with vanilla JavaScript and Vite.

## Features

- 🛍️ Product listing with dynamic cards
- 🛒 Shopping cart functionality
- ➕ Quantity increment/decrement
- 💾 Local storage for cart persistence
- 🔔 Toast notifications
- 📱 Responsive design

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Vite (Build Tool)
- Font Awesome Icons
- LocalStorage API

## Project Structure

```
Ecomm_site/
├── api/
│   └── products.json
├── src/
│   ├── addToCart.js
│   ├── homeProductCards.js
│   ├── homeQuantityToggle.js
│   ├── incrementDecrement.js
│   ├── removeProdFromCart.js
│   ├── showToast.js
│   └── updateCartValue.js
├── index.html
├── addToCart.html
├── products.html
├── about.html
├── contact.html
├── style.css
├── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/Ecomm_site.git
```

2. Navigate to project directory
```bash
cd Ecomm_site
```

3. Install dependencies
```bash
npm install
```

4. Start development server
```bash
npm run dev
```

5. Build for production
```bash
npm run build
```

## Usage

- Browse products on the home page
- Click +/- to adjust quantities
- Add items to cart
- View cart to see selected items
- Remove items from cart as needed

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Vite.js team for the build tool
- Font Awesome for icons
- Contributors and reviewers
