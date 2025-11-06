# Employee Portal - Managely

A comprehensive Human Resource Management System (HRMS) with dual-portal architecture for both administrators and employees, built with modern web technologies.

## 🌟 Overview

Managely is a feature-rich HR management platform that provides separate interfaces for administrators and employees with comprehensive functionality for attendance tracking, leave management, payroll processing, performance monitoring, and document management.

## 🚀 Features

### 🔐 Authentication & Role Management
- **Dual Portal System**: Separate interfaces for Admin and Employee roles
- **Role-based Access Control**: Different permissions and views based on user role
- **Secure Login System**: Form validation and session management

### 👨‍💼 Admin Portal Features
- **Dashboard Analytics**: Comprehensive overview with charts and metrics
- **Employee Management**: Full CRUD operations for employee records
- **Department Management**: Organizational structure management
- **Attendance Tracking**: Real-time monitoring and reporting
- **Leave Management**: Approval workflow and tracking
- **Payroll Processing**: Salary management and distribution
- **Performance Monitoring**: Employee performance metrics
- **Reporting**: Advanced analytics and reporting tools
- **System Settings**: Configuration and customization

### 👩‍💻 Employee Portal Features
- **Personal Dashboard**: Individual performance and attendance overview
- **Attendance Management**: Check-in/out functionality with history
- **Leave Management**: Application and tracking system
- **Payroll Access**: Salary details and payslip downloads
- **Performance Tracking**: Personal metrics and feedback
- **Project Management**: Task and project tracking
- **Document Center**: Centralized document repository
- **Profile Management**: Personal information management
- **Support System**: Help desk and ticket management

### 🎨 UI/UX Features
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Dark/Light Theme**: Toggleable theme system with CSS variables
- **Interactive Charts**: Data visualization with Chart.js
- **Modern Components**: Card-based layout with hover effects
- **Loading States**: Smooth transitions and loading indicators
- **Toast Notifications**: User feedback system

## 🛠 Technology Stack

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript ES6+**: Modern JavaScript features
- **Chart.js**: Data visualization library
- **Font Awesome**: Icon library

### Architecture
- **Single Page Application (SPA)**: Client-side routing
- **Component-based Design**: Modular UI components
- **Theme System**: CSS custom properties for theming
- **SDK Integration**: Extensible plugin architecture

## 📁 Project Structure

```
managely-hrms/
├── index.html                 # Main application file
├── README.md                  # Project documentation
└── SDK Integration/
    ├── element_sdk.js         # UI component SDK
    └── data_sdk.js           # Data management SDK
```

## 🚀 Installation & Setup

### Prerequisites
- Modern web browser with JavaScript enabled
- Web server for deployment (optional for local development)

### Quick Start
1. Clone or download the project files
2. Serve the `index.html` file through a web server
3. Open the application in your browser

## 💻 Usage

### Portal Selection
1. **Access Application**: Open the application in your browser
2. **Choose Role**: Select either Admin or Employee portal
3. **Login**: Use the respective login forms (demo implementation)

### Admin Access
- Username: Any text (demo)
- Password: Any text (demo)

### Employee Access
- Employee ID: Any text (demo)
- Password: Any text (demo)

## 🔧 Configuration

### SDK Integration
The application supports external SDKs for:
- **Element SDK**: UI customization and theming
- **Data SDK**: Data persistence and real-time updates

### Theme Customization
```css
/* Light Theme */
:root {
  --bg-primary: #ffffff;
  --bg-secondary: #f8fafc;
  --text-primary: #1e293b;
  --text-secondary: #64748b;
}

/* Dark Theme */
.dark {
  --bg-primary: #1e293b;
  --bg-secondary: #334155;
  --text-primary: #f1f5f9;
  --text-secondary: #cbd5e1;
}
```

## 🎯 Key Components

### Navigation System
- **Sidebar Navigation**: Collapsible menu for mobile
- **Breadcrumb Navigation**: Context-aware navigation
- **Profile Dropdown**: User management and settings

### Data Management
- **Leave Requests**: CRUD operations with validation
- **Attendance Records**: Time tracking and reporting
- **Payroll Data**: Salary calculations and history

### Chart Components
- **Line Charts**: Trend analysis (employee growth, payroll trends)
- **Bar Charts**: Comparative analysis (attendance, salary distribution)
- **Pie/Doughnut Charts**: Proportional data (department distribution, leave status)
- **Radar Charts**: Multi-dimensional analysis (performance metrics)

## 🔒 Security Features

- **Form Validation**: Client-side input validation
- **Role-based Access**: Separate data views per role
- **Session Management**: Login/logout functionality
- **XSS Prevention**: Input sanitization

## 📱 Responsive Design

The application is fully responsive with breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎨 Customization

### Branding
Update company information through the SDK:
```javascript
const config = {
    company_name: "Your Company",
    company_tagline: "Your Tagline",
    employee_name: "Employee Name",
    employee_position: "Position",
    employee_department: "Department"
};
```

### Styling
Modify CSS custom properties for brand colors:
```css
.btn-primary {
    background: linear-gradient(135deg, your-color-1, your-color-2);
}
```

## 🔄 Data Flow

1. **User Authentication** → Role-based portal selection
2. **Dashboard Loading** → Initial data fetch and chart rendering
3. **User Interactions** → Form submissions and data updates
4. **Real-time Updates** → SDK-driven data synchronization
5. **Theme Management** → CSS variable updates

## 📊 Performance Considerations

- **Lazy Loading**: Charts initialize on demand
- **Efficient DOM Updates**: Minimal re-renders
- **Optimized Assets**: CDN-hosted libraries
- **Progressive Enhancement**: Graceful degradation

## 🐛 Known Issues

1. **Demo Authentication**: Login forms accept any input (intentional for demo)
2. **Data Persistence**: Requires backend integration for production
3. **Browser Compatibility**: Optimized for modern browsers

## 🚧 Development Roadmap

### Phase 1 (Current)
- [x] Core UI/UX implementation
- [x] Basic functionality for all modules
- [x] Theme system
- [x] Responsive design

### Phase 2 (Planned)
- [ ] Backend integration
- [ ] Database design
- [ ] API development
- [ ] Authentication system

### Phase 3 (Future)
- [ ] Mobile application
- [ ] Advanced analytics
- [ ] Integration capabilities
- [ ] Multi-language support

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 🌐 Live Demo

🔗 **Visit Site:** [https://arefinzaman-dev.github.io/managely-frontend/](https://arefinzaman-dev.github.io/managely-frontend/)

---

## 👨‍💻 Developer Info

**Author:** Shaikh Arefin Zaman  
**Project Type:** Frontend Prototype  
**Email:** arefinzamandev@gmail.com  

## 📞 Support

For support, email arefinzamandev@gmail.com or create an issue in the repository.

---

## 📄 License

This project is open-source and available under the **MIT License**.  
You’re free to modify and distribute it with proper credit.

---
## 🙏 Acknowledgments

- Tailwind CSS for the utility-first CSS framework
- Chart.js for data visualization
- Font Awesome for icons
- The open-source community for inspiration and tools

**Note**: This is a frontend demonstration. For production use, integrate with a backend system for data persistence, authentication, and business logic.
