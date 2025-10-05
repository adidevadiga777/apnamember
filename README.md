# Apna Member - Gym Management System

A comprehensive gym management website built with React, TypeScript, and Tailwind CSS. Designed specifically for gym owners to manage their members, track earnings, and streamline operations.

## Features

### 🏠 Landing Page
- Modern, responsive design with gradient backgrounds
- Feature highlights and pricing preview
- Call-to-action buttons for getting started

### 🔐 Authentication
- Secure login system for gym owners
- Demo credentials provided for testing
- Protected routes and user session management

### 💳 Subscription Management
- Two subscription plans: Basic (₹999/year) and Premium (₹1999/year)
- Feature comparison and plan selection
- Simulated payment processing

### 👤 Profile Setup
- Multi-step form for gym profile completion
- Gym details, location, and operating hours
- Progress indicator and form validation

### 📊 Dashboard
- **Earnings Analytics**: Interactive line chart showing monthly earnings in rupees
- **Member Management**: Add, view, and manage gym members
- **Search & Filter**: Find members by name/email and filter by status
- **Status Tracking**: Monitor active, inactive, and unpaid members
- **Real-time Stats**: Total earnings, member counts, and payment status

## Tech Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom components
- **Charts**: Recharts for data visualization
- **Icons**: Lucide React for modern icons
- **Routing**: React Router DOM
- **State Management**: React Context API

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd gym2
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

### Demo Credentials

For testing the application, use these demo credentials:
- **Email**: `owner@gym.com`
- **Password**: `password`

## Application Flow

1. **Landing Page** → Users see the main website with features and pricing
2. **Login** → Gym owners authenticate with their credentials
3. **Subscription** → Choose between Basic or Premium plan
4. **Profile Setup** → Complete gym profile with detailed information
5. **Dashboard** → Main management interface with all features

## Dashboard Features

### Earnings Chart
- Monthly earnings visualization in rupees
- Interactive tooltips with currency formatting
- Responsive design for all screen sizes

### Member Management
- **Add Members**: Modal form to add new gym members
- **Member List**: Table view with all member details
- **Search**: Find members by name or email
- **Filter**: View all members or only unpaid ones
- **Status Indicators**: Color-coded status badges

### Statistics Cards
- Total earnings for the year
- Total member count
- Active members count
- Unpaid members count

## File Structure

```
src/
├── components/          # Reusable UI components
├── contexts/           # React context providers
│   └── AuthContext.tsx # Authentication state management
├── pages/              # Main application pages
│   ├── LandingPage.tsx
│   ├── LoginPage.tsx
│   ├── SubscriptionPage.tsx
│   ├── ProfileSetupPage.tsx
│   └── DashboardPage.tsx
├── App.tsx             # Main application component
├── index.tsx           # Application entry point
└── index.css           # Global styles and Tailwind imports
```

## Customization

### Styling
The application uses Tailwind CSS with custom color schemes. You can modify the colors in `tailwind.config.js`:

```javascript
colors: {
  primary: {
    50: '#eff6ff',
    500: '#3b82f6',
    600: '#2563eb',
    // ... more shades
  }
}
```

### Data
Currently, the application uses mock data. To integrate with a real backend:

1. Replace mock API calls in `AuthContext.tsx`
2. Update member data management in `DashboardPage.tsx`
3. Connect to your preferred backend service

## Deployment

### Build for Production
```bash
npm run build
```

### Deploy Options
- **Vercel**: Connect your GitHub repository for automatic deployments
- **Netlify**: Drag and drop the `build` folder
- **AWS S3**: Upload the `build` folder to an S3 bucket
- **Heroku**: Add a `static.json` file for static site deployment

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support and questions, please contact the development team or create an issue in the repository.

---

**Apna Member** - Empowering gym owners with modern management tools! 💪



