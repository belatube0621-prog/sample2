# Restaurant Ordering System

A comprehensive restaurant/hotel ordering system with three separate dashboards for guests, kitchen staff, and owners.

## Features

### 👤 Guest Dashboard
- Browse menu with search and category filtering
- Multi-language support (English, Spanish, French)
- Add items to cart with special instructions
- Order for Table or Room service
- Track order history with real-time status updates
- Receive notifications when orders are ready

### 👨‍🍳 Kitchen Dashboard
- Real-time order management
- Kanban-style workflow (Pending → Preparing → Ready)
- Order statistics and counts
- Sound notifications for new orders
- Secure login required

### 👑 Owner Dashboard
- Complete restaurant management
- Customize restaurant info (logo, name, address, social links)
- Theme customization (colors, background image)
- Category management
- Menu item management with photo upload
- Order management with delete capabilities
- Security settings for Kitchen and Owner credentials

## Default Credentials

| Dashboard | Username | Password |
|-----------|----------|----------|
| Kitchen | `kitchen` | `kitchen123` |
| Owner | `owner` | `owner123` |

> ⚠️ **Important**: Change the default credentials after first login!

## Deployment on Vercel

### Option 1: Deploy with Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. For production deployment:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

### Option 3: Drag and Drop

1. Go to [vercel.com](https://vercel.com)
2. Drag and drop the project folder onto the Vercel dashboard

## Local Development

To run locally:

```bash
# Using npx serve
npx serve .

# Or using Python
python -m http.server 8000

# Or using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Tech Stack

- **HTML5** - Structure
- **Tailwind CSS** - Styling (via CDN)
- **JavaScript** - Functionality
- **LocalStorage** - Data persistence
- **Font Awesome** - Icons

## Data Persistence

All data is stored in the browser's localStorage, including:
- Orders
- Menu items
- Categories
- Restaurant information
- Theme settings
- User credentials

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License
