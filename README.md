# 🍝 Bella Vista - Italian Restaurant Website

A modern, full-featured restaurant website showcasing authentic Italian cuisine with complete online functionality. Built with both React/TypeScript and standalone HTML versions for maximum flexibility and deployment options.

![Bella Vista Restaurant](https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&h=400)

## ✨ Features

- 📱 **Fully Responsive Design** - Mobile-first approach with seamless experience across all devices
- 🍽️ **Interactive Menu System** - Category filtering with appetizers, pasta, pizza, mains, and desserts
- 📅 **Online Reservations** - Complete booking system with date/time selection and party size options
- 🛒 **Shopping Cart** - Persistent cart with quantity management and checkout process
- 🖼️ **Image Gallery** - Lightbox functionality for showcasing restaurant ambiance and dishes
- 📞 **Contact System** - Contact form with validation and restaurant information
- 🎨 **Modern UI/UX** - Professional Italian restaurant design with smooth animations
- ♿ **Accessibility Focused** - Screen reader friendly and keyboard navigation support
- 🔄 **Real-time Updates** - Efficient data handling and state management
- 💾 **Local Storage** - Cart persistence across browser sessions

## 🌟 Two Implementation Options

### 1. Full-Stack React Application
Complete React/TypeScript application with Express.js backend:
- Modern component architecture
- Type-safe development
- Server-side API endpoints
- Development and production builds

### 2. Standalone HTML File (`bella-vista-standalone.html`)
Single-file implementation perfect for:
- **Portfolio websites** - Easy integration with existing portfolios
- **Quick deployment** - No build process required
- **GitHub Pages** - Direct hosting capability
- **Live demos** - Instant preview functionality

## 🚀 Quick Start (Standalone Version)

The easiest way to get started is using the standalone HTML file:

1. Download `bella-vista-standalone.html`
2. Open in any modern web browser
3. Enjoy the full restaurant experience!

**Perfect for:**
- Adding to your portfolio with a "Live Demo" button
- Showcasing web development skills
- Client presentations
- Educational purposes

## 🛠️ Technologies Used

### Full-Stack Version
- **React 18** with TypeScript
- **Tailwind CSS** for styling
- **Express.js** backend
- **Vite** build system
- **React Query** for state management
- **Zod** schema validation

### Standalone Version
- **Vanilla JavaScript** (ES6+)
- **Tailwind CSS** (CDN)
- **Font Awesome** icons
- **Google Fonts** typography
- **Local Storage** API
- **Modern CSS** animations

## 🎯 Portfolio Integration

### Adding to Your Portfolio

1. **Download the standalone file:**
   ```bash
   curl -o bella-vista.html https://raw.githubusercontent.com/yourusername/bella-vista/main/bella-vista-standalone.html
   ```

2. **Add to your portfolio:**
   ```html
   <div class="project">
     <h3>Bella Vista Restaurant</h3>
     <p>Full-featured Italian restaurant website with menu, reservations, and ordering system.</p>
     <a href="./bella-vista.html" target="_blank" class="demo-btn">Live Demo</a>
     <a href="https://github.com/yourusername/bella-vista" class="code-btn">View Code</a>
   </div>
   ```

3. **Deploy to GitHub Pages:**
   - Upload the file to your repository
   - Enable GitHub Pages
   - Access via: `https://yourusername.github.io/repository/bella-vista.html`

## 📋 Development Setup (Full-Stack)

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/bella-vista-restaurant.git
   cd bella-vista-restaurant
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   ```
   http://localhost:5000
   ```

## 📂 Project Structure

```
bella-vista-restaurant/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── hooks/          # Custom React hooks
│   │   ├── lib/           # Utility functions
│   │   └── pages/         # Page components
│   └── index.html         # HTML template
├── server/                # Express.js backend
│   ├── routes.ts          # API routes
│   ├── storage.ts         # Data storage layer
│   └── index.ts           # Server entry point
├── shared/                # Shared TypeScript schemas
├── bella-vista-standalone.html  # Single-file version
└── README.md             # Project documentation
```

## 🎨 Design Features

### Color Palette
- **Primary Orange:** #D97706 - Warm, inviting Italian-inspired color
- **Secondary Dark:** #1F2937 - Professional contrast for text
- **Accent Red:** #EF4444 - Highlighting important elements

### Typography
- **Headings:** Playfair Display (elegant serif)
- **Body Text:** Inter (modern sans-serif)
- **Professional hierarchy** with proper font weights

### Interactive Elements
- **Smooth scrolling** navigation
- **Hover animations** on menu items
- **Cart badge animations** 
- **Form validation** with user feedback
- **Image lightbox** for gallery viewing
- **Mobile-responsive** design

## 📱 Mobile Experience

- **Mobile-first design** approach
- **Touch-friendly** interface elements
- **Collapsible navigation** menu
- **Optimized images** for faster loading
- **Responsive grid** layouts
- **Swipe gestures** support

## 🚀 Deployment Options

### Option 1: Static Hosting (Standalone)
Perfect for portfolios and demos:
- **Netlify:** Drag and drop deployment
- **Vercel:** Git-based deployment
- **GitHub Pages:** Free hosting for public repos
- **Firebase Hosting:** Google's hosting platform

### Option 2: Full-Stack Deployment
For production applications:
- **Railway:** Easy Node.js deployment
- **Render:** Free tier for web services
- **Heroku:** Classic platform-as-a-service
- **DigitalOcean:** Virtual private servers

## 🔧 Customization

### Menu Items
Edit the `menuItems` array in the standalone HTML or `server/storage.ts`:
```javascript
{
  id: 'unique-id',
  name: 'Dish Name',
  category: 'appetizers|pasta|pizza|mains|desserts',
  price: 19.99,
  description: 'Detailed description',
  image: 'https://image-url.com/image.jpg'
}
```

### Restaurant Information
Update contact details and restaurant info in the Contact section:
- Address, phone, email
- Operating hours
- Social media links

### Styling
Modify the Tailwind CSS classes or add custom CSS:
- Color scheme in the `tailwind.config` section
- Animations and transitions
- Layout and spacing

## 📊 Features Breakdown

### Menu System
- ✅ Category filtering (All, Appetizers, Pasta, Pizza, Mains, Desserts)
- ✅ High-quality food photography
- ✅ Detailed descriptions and pricing
- ✅ Add to cart functionality

### Reservation System
- ✅ Date/time selection with validation
- ✅ Party size options (1-7+ people)
- ✅ Contact information collection
- ✅ Special requests field
- ✅ Form validation and success feedback

### Shopping Cart
- ✅ Persistent storage (localStorage)
- ✅ Quantity management (+/- buttons)
- ✅ Item removal functionality
- ✅ Total price calculation
- ✅ Checkout process simulation

### Gallery & Media
- ✅ Professional restaurant photography
- ✅ Lightbox image viewer
- ✅ Responsive image loading
- ✅ Alt text for accessibility

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Unsplash** for high-quality food photography
- **Tailwind CSS** for the utility-first CSS framework
- **Font Awesome** for the icon library
- **Google Fonts** for beautiful typography

## 📞 Support

If you have any questions or need help with implementation:

- Open an issue on GitHub
- Check the documentation
- Review the code comments in the standalone file

---

**Perfect for showcasing modern web development skills in your portfolio!** 

The standalone HTML file makes it incredibly easy to demonstrate a complete, functional restaurant website with just a single file upload.
   
