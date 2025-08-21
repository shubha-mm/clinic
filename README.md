# MediCare Pro - Clinic Management System

A comprehensive, modern clinic management system built with HTML, CSS, JavaScript, and Firebase deployment.

## Features

### Core Functionality
- **Dashboard Analytics** - Real-time metrics, charts, and key performance indicators
- **Appointment Management** - Complete scheduling, rescheduling, and status tracking
- **Patient Management** - Comprehensive patient records and medical history
- **Billing & Invoicing** - Automated billing, payment tracking, and financial reporting
- **Staff Management** - Employee profiles, schedules, and performance tracking
- **Reports & Analytics** - Detailed reports with data visualization

### Design Features
- **Modern UI/UX** - Clean, professional design with intuitive navigation
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Interactive Charts** - Real-time data visualization using Chart.js
- **Smooth Animations** - Micro-interactions and transitions for better UX
- **Accessibility** - WCAG compliant with proper contrast and keyboard navigation

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **Icons**: Font Awesome
- **Fonts**: Inter (Google Fonts)
- **Deployment**: Firebase Hosting

## Project Structure

```
public/
├── index.html              # Main application file
├── styles/
│   ├── main.css           # Core styles and variables
│   └── dashboard.css      # Dashboard-specific styles
├── js/
│   ├── app.js            # Main application logic
│   ├── dashboard.js      # Dashboard charts and analytics
│   ├── appointments.js   # Appointment management
│   ├── patients.js       # Patient management
│   ├── billing.js        # Billing and invoicing
│   ├── reports.js        # Reports and analytics
│   └── staff.js          # Staff management
firebase.json               # Firebase configuration
.firebaserc                # Firebase project settings
```

## Firebase Deployment Steps

### Prerequisites
1. Install Node.js (https://nodejs.org/)
2. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```

### Deployment Steps

1. **Login to Firebase**
   ```bash
   firebase login
   ```

2. **Initialize Firebase Project**
   ```bash
   firebase init
   ```
   - Select "Hosting: Configure files for Firebase Hosting"
   - Choose "Use an existing project" or "Create a new project"
   - Set public directory to `public`
   - Configure as single-page app: Yes
   - Set up automatic builds and deploys with GitHub: No (optional)

3. **Deploy to Firebase**
   ```bash
   firebase deploy
   ```

4. **View Your Live Site**
   After deployment, Firebase will provide a URL like:
   `https://your-project-id.web.app`

### Alternative Deployment Commands

- **Deploy only hosting**: `firebase deploy --only hosting`
- **Preview before deploy**: `firebase hosting:channel:deploy preview`
- **Set custom domain**: Configure in Firebase Console

## Demo Credentials

- **Email**: admin@clinic.com
- **Password**: admin123

## Features Overview

### Dashboard
- Real-time statistics and KPIs
- Interactive charts for appointments and revenue
- Quick action buttons
- Today's appointment overview

### Appointments
- Advanced filtering and search
- Status management (pending, confirmed, completed, cancelled)
- Doctor and patient assignment
- Time slot management

### Patients
- Comprehensive patient profiles
- Medical history tracking
- Contact information management
- Appointment history

### Billing
- Invoice generation and management
- Payment tracking
- Outstanding balance monitoring
- Revenue analytics

### Staff
- Employee profile management
- Schedule tracking
- Performance metrics
- Contact information

### Reports
- Patient demographics
- Revenue analysis
- Appointment statistics
- Exportable reports

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Performance Features

- Optimized CSS with custom properties
- Efficient JavaScript with modular architecture
- Lazy loading for better performance
- Responsive images and assets

## Security Features

- Client-side authentication simulation
- Role-based access control structure
- Secure data handling practices
- Input validation and sanitization

## Customization

The system uses CSS custom properties for easy theming:

```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #10b981;
  --accent-color: #f59e0b;
  /* ... more variables */
}
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Support

For support and questions, please contact the development team or create an issue in the repository.