# 📊 Scratch Statistics Dashboard

A comprehensive, real-time statistics dashboard for the Scratch community with admin tools for managing verified users and featured content.

## ✨ Features

### Public Dashboard
- **Live Community Statistics**: Total users, projects, studios, and comments
- **Featured Content**: Showcase featured projects, studios, and verified users
- **Real-time Updates**: Statistics refresh every 5 minutes
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile

### Admin Control Panel
- **Verify Users**: Mark community members as verified
- **Feature Content**: Showcase projects, studios, and users
- **Manage Featured Items**: Add, remove, or organize featured content
- **Developer Badge**: Shows your status as a verified developer
- **Secure Authentication**: Password-protected admin panel

## 🔐 Security Features

- ✅ Secure password hashing
- ✅ Session-based authentication
- ✅ 24-hour session expiration
- ✅ XSS protection
- ✅ Input validation and sanitization
- ✅ Token-based session management


## 🚀 Getting Started

### Option 1: GitHub Pages (Recommended)
1. The site is already live at: **https://DukeScratch.github.io/scratch-stats.github.io**
2. Click "Login" and use your admin credentials
3. Start managing verified users and featured content!

### Option 2: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/DukeScratch/scratch-stats.github.io.git
   cd scratch-stats.github.io
   ```

2. Open `index.html` in your browser:
   ```bash
   open index.html
   ```

## 📁 File Structure

```
scratch-stats.github.io/
├── index.html          # Main HTML file with dashboard and admin panel
├── styles.css          # Beautiful responsive styling
├── script.js           # Dashboard functionality and state management
├── auth.js             # Secure authentication module
└── README.md           # This file
```

## 🎮 How to Use

### Public Dashboard
1. Open the website
2. View live Scratch community statistics
3. Explore featured projects, studios, and users
4. Statistics auto-refresh every 5 minutes

### Admin Panel
1. Click "Login" button
2. Enter admin credentials
3. Access three admin tools:

#### Verify Users Tab
- Enter any username to mark as verified
- View all verified users
- Remove verification when needed

#### Feature Content Tab
- Add project to featured list (requires project ID/URL and title)
- Add studio to featured list (requires studio ID/URL and title)
- Add users to featured list (just need username)

#### Manage Featured Tab
- View all featured projects, studios, and users
- Remove items from featured lists
- Keep up to 6 items per category

## 💾 Data Storage

- All admin data is stored in **browser localStorage**
- Data persists across browser sessions
- No server required - works entirely client-side
- Clear browser data to reset all admin changes

## 🎨 Design

- Modern purple gradient theme
- Smooth animations and transitions
- Mobile-friendly responsive layout
- Accessible color contrast
- Clean, intuitive interface

## 📈 Statistics

The dashboard displays:
- **Total Users**: Estimated Scratch community members
- **Total Projects**: Total projects created on Scratch
- **Total Studios**: Community studios available
- **Total Comments**: Total comments across the platform

*Note: Currently using mock data. Can be connected to Scratch API for live data.*

## 🔒 Security Notes

- Passwords are hashed before storage
- Sessions expire after 24 hours
- All user inputs are validated and sanitized
- No sensitive data stored in localStorage
- Uses sessionStorage for temporary auth tokens

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox/grid
- **Vanilla JavaScript**: No dependencies required
- **GitHub Pages**: Free hosting

## 🔌 API Integration

The dashboard currently uses mock data but can be easily connected to:
- Scratch REST API for live statistics
- Custom backend for persistent data storage
- User authentication system

## 🚀 Deployment

The site is automatically deployed to GitHub Pages at:
```
https://DukeScratch.github.io/scratch-stats.github.io
```

Any changes pushed to the `main` branch are automatically deployed.

## 💡 Future Enhancements

- [ ] Integration with Scratch API for live data
- [ ] Backend database for persistent admin data
- [ ] User role management
- [ ] Advanced analytics charts
- [ ] Email notifications
- [ ] API for external integrations
- [ ] Multi-language support

## 📄 License

MIT License - Feel free to use, modify, and distribute

## 🤝 Support

For issues or feature requests, please open an issue on GitHub.

---

**Made with ❤️ for the Scratch community**
