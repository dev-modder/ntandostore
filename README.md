# ntandostore - Premier ICT Solutions & Products

A modern, responsive e-commerce website for ICT products and services, built with HTML, CSS, and JavaScript, ready for deployment on render.com.

## 🚀 Features

- **Modern Design**: Clean, professional UI with smooth animations
- **Product Catalog**: Browse laptops, smartphones, networking equipment, and accessories
- **Product Filtering**: Filter products by category
- **Shopping Cart**: Add items to cart and manage your shopping experience
- **Services Section**: Professional IT services including support, networking, cloud solutions, and more
- **Responsive Design**: Fully responsive across all devices (desktop, tablet, mobile)
- **Contact Form**: Easy way for customers to reach out
- **Newsletter Subscription**: Keep customers updated with latest offers
- **Smooth Animations**: Engaging user experience with scroll animations
- **Mobile Navigation**: Hamburger menu for mobile devices

## 📦 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Node.js with Express
- **Deployment**: Ready for render.com
- **Icons**: Font Awesome 6.4.0
- **Images**: Unsplash (placeholder images)

## 🛠️ Installation & Local Development

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd ntandostore
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🌐 Deployment on render.com

### Prerequisites
- A render.com account (free tier available)
- Git repository (GitHub, GitLab, or Bitbucket)

### Step-by-Step Deployment

1. **Push your code to a Git repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-repo-url>
   git push -u origin main
   ```

2. **Create a new Web Service on render.com**
   - Log in to your render.com dashboard
   - Click "New +" button
   - Select "Web Service"
   - Connect your Git repository
   - Configure the service:
     - **Name**: ntandostore (or your preferred name)
     - **Environment**: Node
     - **Build Command**: `npm install`
     - **Start Command**: `node server.js`
     - **Instance Type**: Free (or paid for better performance)

3. **Deploy**
   - Click "Create Web Service"
   - Render will automatically build and deploy your application
   - Wait for the deployment to complete (usually 2-5 minutes)

4. **Access your site**
   - Once deployed, render.com will provide a public URL
   - Your site will be live at: `https://ntandostore.onrender.com`

### Custom Domain (Optional)

1. Go to your service settings on render.com
2. Navigate to "Domains"
3. Add your custom domain
4. Update your DNS records as instructed by render.com

## 📁 Project Structure

```
ntandostore/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript functionality
├── server.js           # Express server for production
├── package.json        # Node.js dependencies
├── .gitignore          # Git ignore rules
├── README.md           # This file
└── todo.md             # Project todo list
```

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #0f172a;
    /* ... other variables */
}
```

### Adding Products
Edit the product cards in `index.html`:
```html
<div class="product-card" data-category="laptops">
    <div class="product-image">
        <img src="your-image-url" alt="Product Name">
        <div class="product-overlay">
            <button class="btn-add-cart" data-product="Product Name" data-price="1299">
                <i class="fas fa-cart-plus"></i> Add to Cart
            </button>
        </div>
    </div>
    <div class="product-info">
        <span class="product-category">Laptops</span>
        <h3>Product Name</h3>
        <p>Product description</p>
        <div class="product-price">$1,299</div>
    </div>
</div>
```

### Updating Contact Information
Edit the contact section in `index.html` with your actual business details.

## 🔧 Configuration

### Environment Variables
Create a `.env` file for local development (optional):
```
PORT=3000
```

### Performance Optimization
The site includes:
- Gzip compression
- Static file caching
- Optimized images
- Minified CSS and JavaScript (recommended for production)

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 767px and below

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 📞 Support

For support, please contact:
- Email: info@ntandostore.com
- Phone: +26378 683 1091

## 🌟 Features Coming Soon

- User authentication
- Payment integration (Stripe, PayPal)
- Product search functionality
- User reviews and ratings
- Admin dashboard
- Order tracking
- Email notifications

---

Built with ❤️ for ntandostore
