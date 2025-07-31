## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone git@github.com:Mahesh2552/Product-Card-UI.git
   cd Product-Card-UI
   ```

2. **Install dependencies**
   ```bash
   npm install --legacy-peer-deps
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 📁 Project Structure

```
src/
├── components/
│   ├── ProductCard.jsx      # Main product card component
│   ├── ProductCard.css      # Product card styles
│   ├── Products.jsx         # Products listing page
│   └── Navbar.jsx           # Navigation component
├── pages/
│   ├── ProductCardDemo.jsx  # Demo showcase page
│   ├── ProductCardDemo.css  # Demo page styles
│   └── Product.jsx          # Single product page
└── redux/
    └── action/
        └── index.js         # Cart actions
```

## 🎨 Key Components

### ProductCard Component
- Responsive grid layout
- Image with overlay effects
- Price display with original price
- Size variant selection
- Add to cart functionality
- Out of stock handling
- Loading states

### Features
- **Mobile-first responsive design**
- **Touch-friendly interface** (44px minimum touch targets)
- **Accessibility considerations**
- **Smooth animations and transitions**
- **Local data management** (no external API calls)

## 🚀 Available Scripts

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm run deploy` - Deploys to GitHub Pages

## 📱 Responsive Design

The application is built with a mobile-first approach:
- **Mobile**: Single column layout
- **Tablet**: Two columns
- **Desktop**: Multiple columns with optimal spacing

## 🎯 Demo Pages

- `/` - Home page
- `/demo` - Product Card Demo showcase
- `/product` - Products listing
- `/product/:id` - Single product view

## 🔧 Troubleshooting

If you encounter any issues:

1. **Port conflicts**: Make sure ports 3000 and 4000 are available
2. **Dependencies**: Use `npm install --legacy-peer-deps`
3. **Build issues**: Clear node_modules and reinstall

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!
