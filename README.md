# Golden Fork Restaurant Website

A comprehensive restaurant website built with HTML, CSS, and JavaScript featuring all essential modules for a modern restaurant business.

## Features

### Core Modules
- **Home Page** - Welcome page with featured dishes, search functionality, and quick links
- **Menu Display** - Categorized menu with filtering, dietary tags, and dish ratings
- **Dish Booking System** - Multi-step booking process for dine-in, takeaway, or delivery
- **Restaurant Rating System** - Comprehensive rating system with multiple categories
- **Dish Rating System** - Individual dish ratings and reviews
- **User Registration & Login** - Secure authentication system
- **About Us** - Restaurant history, mission, team, and operating hours
- **Contact** - Contact form with map integration

### Additional Modules
- **Online Ordering System** - Full shopping cart with checkout functionality
- **Gallery** - Image gallery with categories and lightbox view
- **Events & Specials** - Event calendar and special promotions
- **Blog/News** - Blog posts with categories and tags
- **Reviews & Testimonials** - Customer reviews with filtering
- **Loyalty Program** - Points-based reward system with tiers
- **Admin Dashboard** - Complete admin panel for managing bookings, orders, users, and reviews
- **Newsletter Subscription** - Email subscription functionality

## Project Structure

```
restaurant/
├── index.html          # Home page
├── menu.html           # Menu display
├── booking.html         # Dish booking system
├── rating.html          # Restaurant rating
├── dish-rating.html     # Individual dish rating
├── login.html           # User login
├── register.html        # User registration
├── order.html           # Online ordering
├── gallery.html         # Photo gallery
├── events.html          # Events & specials
├── blog.html            # Blog/News section
├── reviews.html         # Reviews page
├── about.html           # About us
├── contact.html         # Contact page
├── profile.html         # User profile
├── admin.html           # Admin dashboard
├── loyalty.html         # Loyalty program
├── css/
│   └── styles.css       # Main stylesheet
└── js/
    └── common.js        # Common JavaScript functions
```

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **No server required**: This is a client-side only application using localStorage for data persistence
3. **Test features**: 
   - Register a new account
   - Browse the menu
   - Make a booking
   - Place an order
   - Rate dishes and restaurant

## Key Features

### User Features
- **Registration & Login**: Create account with email verification simulation
- **Menu Browsing**: Filter by category, dietary preferences, search functionality
- **Dish Booking**: Multi-step booking process with date/time selection
- **Online Ordering**: Add items to cart, checkout, order tracking
- **Ratings & Reviews**: Rate restaurant and individual dishes
- **Loyalty Program**: Earn points with purchases, redeem rewards
- **Profile Management**: View bookings, orders, update profile

### Admin Features
- **Dashboard**: View statistics and manage all aspects
- **Booking Management**: View, edit, delete bookings
- **Order Management**: Track orders, update status
- **User Management**: View registered users
- **Review Moderation**: Approve or delete reviews
- **Contact Form Management**: View customer inquiries

## Data Storage

The application uses **localStorage** to persist data:
- User accounts
- Bookings
- Orders
- Ratings and reviews
- Cart items
- Loyalty points
- Contact form submissions

**Note**: All data is stored locally in the browser. For production use, integrate with a backend database.

## Design Features

- **Responsive Design**: Works on mobile, tablet, and desktop
- **Modern UI**: Clean, professional design with smooth animations
- **Accessibility**: Semantic HTML, keyboard navigation support
- **Color Scheme**: Golden/amber theme with dark accents
- **Typography**: Clean, readable fonts
- **Interactive Elements**: Hover effects, transitions, animations

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Customization

### Colors
Edit CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #d4af37;
    --secondary-color: #8b4513;
    --accent-color: #ff6b35;
    /* ... */
}
```

### Menu Items
Edit menu data in `menu.html` and `order.html` JavaScript sections.

### Restaurant Information
Update contact details, hours, and information in:
- `about.html`
- `contact.html`
- Footer sections (all pages)

## Future Enhancements

- Backend integration (database, API)
- Payment gateway integration
- Email notifications
- Real-time order tracking
- Multi-language support
- Advanced search functionality
- Social media integration
- Mobile app version

## License

This project is created for educational and demonstration purposes.

## Support

For questions or issues, please refer to the project documentation or contact the development team.

---

**Golden Fork Restaurant** - Experience Culinary Excellence

