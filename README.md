# MDU Cafe ☕ - Smart Shop & Table Booking App

A modern, full-featured cafe management and ordering system built with vanilla HTML, CSS, and JavaScript. Perfect for students, office workers, and cafe owners!

## 🌟 Features

### For Customers 👥
- **Smart Menu Browsing** - Filter items by category (Drinks, Food, Snacks, Ice Cream)
- **Shopping Cart** - Add items, adjust quantities, and checkout
- **Table Booking System** - Reserve tables with instant QR code generation
- **Order Management** - Enter delivery details and complete orders
- **Responsive Design** - Works seamlessly on desktop and mobile devices

### For Staff 👨‍💼
- **Add Menu Items** - Create new products with prices and quantities
- **Inventory Management** - View real-time stock levels
- **Custom Categories** - Create custom product categories
- **Image Upload** - Add product images easily
- **Staff Dashboard** - Manage the menu from a dedicated panel

### For Owners 👑
- **Analytics Dashboard** - Track total items, stock, and inventory value
- **Security Controls** - Update staff and owner access codes
- **Complete Inventory View** - Monitor all products and their values
- **Staff Management** - Control staff access with secure codes

## 🚀 Quick Start

### Option 1: Deploy to GitHub Pages (Recommended)

#### Step 1: Create a New GitHub Repository
1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. Name it `mdu-cafe` (or any name you prefer)
4. Choose **Public** (so it's accessible online)
5. Click **Create repository**

#### Step 2: Add Files to Your Repository
1. Click **uploading an existing file**
2. Upload the `index.html` file you downloaded
3. Click **Commit changes**

Or use Git commands:
```bash
git clone https://github.com/YOUR_USERNAME/mdu-cafe.git
cd mdu-cafe
# Copy index.html here
git add index.html
git commit -m "Add MDU Cafe app"
git push
```

#### Step 3: Enable GitHub Pages
1. Go to your repository settings
2. Scroll to **Pages** section
3. Select **main** branch as the source
4. Click **Save**
5. Your site will be live at: `https://YOUR_USERNAME.github.io/mdu-cafe/`

### Option 2: Deploy to Netlify (Even Easier!)

1. Go to [Netlify](https://netlify.com)
2. Drag and drop the `index.html` file
3. Your site is instantly live with a free URL!

### Option 3: Deploy to Vercel

1. Go to [Vercel](https://vercel.com)
2. Click **New Project**
3. Upload the `index.html` file
4. Deploy!

### Option 4: Run Locally

Simply open `index.html` in your web browser. No server required!

## 🔐 Default Access Codes

- **Staff Code**: `1234`
- **Owner Code**: `5678`

⚠️ **IMPORTANT**: Change these codes immediately in the Owner Dashboard for security!

## 📱 How to Use

### As a Customer
1. Browse the menu and add items to cart
2. Click the cart icon to view your order
3. Enter your details and checkout
4. Use "Book Table" to reserve a table and get a QR code

### As Staff
1. Click "Staff/Owner" → Select "Staff Portal"
2. Enter the staff code (default: `1234`)
3. Add new items, set prices, quantities, and categories
4. View current inventory

### As Owner
1. Click "Staff/Owner" → Select "Owner Portal"
2. Enter the owner code (default: `5678`)
3. View analytics and inventory value
4. Update staff and owner access codes in Security Settings

## 📂 Project Structure

```
mdu-cafe/
├── index.html          # Complete app (HTML + CSS + JS)
└── README.md           # This file
```

## 💻 Technology Stack

- **HTML5** - Structure and semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript (Vanilla)** - No frameworks needed!
- **QR Code JS** - For table booking QR codes (CDN)

## 🎨 Customization

### Change Colors
Open `index.html` and modify the CSS variables at the top:
```css
:root {
    --primary-dark: #33210d;
    --primary-brown: #4b3621;
    /* ... more colors ... */
}
```

### Add Menu Items
Edit the `inventory` array in the JavaScript section:
```javascript
let inventory = [
    {
        id: 1,
        name: 'Your Item Name',
        price: 100,
        quantity: 50,
        category: 'drinks',
        image: 'image-url.jpg'
    }
    // ... more items
];
```

### Change Restaurant Name
Search for "MDU Cafe" and replace with your cafe name

## 🔒 Security Notes

- All data is stored in browser memory (localStorage can be added for persistence)
- Access codes should be changed immediately after deployment
- This is a demo app - for production, use a backend database
- Implement proper payment gateway integration

## 📋 Features Checklist

- ✅ Customer menu browsing
- ✅ Shopping cart with checkout
- ✅ Table booking with QR codes
- ✅ Staff panel for inventory
- ✅ Owner dashboard with analytics
- ✅ Responsive design
- ✅ Category filtering
- ✅ Image uploads
- ✅ Access code security
- ✅ Order management

## 🌐 Deploy Now!

Choose your favorite hosting:
- **GitHub Pages** - Free, integrated with GitHub
- **Netlify** - Free, drag-and-drop, fastest
- **Vercel** - Free, optimized for Next.js but works with static files
- **Firebase Hosting** - Free, Google-backed

## 📞 Support

For issues or questions:
1. Check the browser console (F12) for errors
2. Verify all files are uploaded correctly
3. Clear browser cache and reload
4. Try in a different browser

## 📝 License

This project is open source and available under the MIT License.

## 🎉 Ready to Launch?

1. ✅ Download `index.html`
2. ✅ Create a GitHub repository
3. ✅ Upload the file
4. ✅ Enable GitHub Pages
5. ✅ Share your link!

Your MDU Cafe is now live! 🚀☕

---

**Made with ❤️ for cafe owners and students everywhere**

Need more features? Consider adding:
- Backend database (Firebase, MongoDB)
- Payment integration (Stripe, PayPal)
- User authentication
- Real-time notifications
- Admin dashboard
- Analytics

Get started now and customize as needed!
