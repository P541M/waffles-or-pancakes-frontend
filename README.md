# Waffles or Pancakes?

A full-stack interactive voting web application that settles the age-old breakfast debate! Built with modern web technologies, featuring real-time voting, animated character feedback, and a responsive design that works seamlessly across all devices.

## Live Demo

**Frontend**: [Live Application](https://waffles-or-pancakes.vercel.app) *(deployed on Vercel)*  
**Backend**: [API Endpoint](https://waffles-or-pancakes-backend.vercel.app) *(RESTful API)*

## Features

- **Real-Time Voting System**: Cast your vote and see results update instantly
- **Interactive Character Animations**: Watch the mascot character change based on your selection
- **Vote Switching**: Change your mind? Switch votes with fun animated messages
- **User Session Tracking**: Persistent voting using localStorage and unique user IDs
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, playful interface with smooth animations and hover effects
- **API Integration**: Full-stack architecture with secure backend communication

## Tech Stack

### Frontend
- **React 18** - Modern functional components with hooks
- **Tailwind CSS** - Utility-first styling and responsive design
- **Axios** - HTTP client for API communication
- **UUID** - Unique user identification
- **Vercel** - Deployment and hosting

### Backend
- **Node.js** - Server runtime environment
- **Express.js** - Web application framework
- **RESTful API** - Clean API architecture
- **Environment Variables** - Secure configuration management
- **CORS** - Cross-origin resource sharing

### Development Tools
- **Prettier** - Code formatting
- **PostCSS** - CSS processing
- **React Scripts** - Build and development tools

## Screenshots & Demo

*Visit the live demo to experience the full interactive voting system!*

## Project Structure

```
waffles-or-pancakes/
├── public/                 # Static assets
├── src/
│   ├── components/
│   │   └── Vote.jsx       # Main voting component
│   ├── assets/
│   │   ├── characters/    # Character images and animations
│   │   └── conceptArt/    # Design assets
│   ├── App.js            # Root component
│   └── index.js          # Application entry point
├── package.json          # Dependencies and scripts
├── tailwind.config.js    # Tailwind configuration
└── vercel.json          # Deployment configuration
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/P541M/waffles-or-pancakes.git
   cd waffles-or-pancakes
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   # Create .env.local file
   REACT_APP_API_KEY=your_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## Development Process & Challenges

### Key Technical Implementations
- **State Management**: Utilized React hooks (useState, useEffect, useCallback) for efficient state handling
- **User Experience**: Implemented smooth animations and transitions for enhanced interactivity
- **Data Persistence**: localStorage integration for maintaining user voting sessions
- **API Security**: Environment variable configuration for secure API communication
- **Responsive Design**: Mobile-first approach using Tailwind's responsive utilities

### Problem-Solving Highlights
- **Vote Switching Logic**: Developed dynamic messaging system for vote changes
- **Animation Timing**: Coordinated multiple animation states for smooth user feedback
- **Cross-Device Compatibility**: Ensured consistent experience across different screen sizes
- **API Error Handling**: Implemented robust error handling for network requests

## Future Enhancements

- [ ] Vote analytics dashboard with charts and statistics
- [ ] Social sharing functionality for results
- [ ] User authentication and personalized voting history
- [ ] Real-time voting notifications and live results
- [ ] Additional breakfast food options (French toast, cereal, etc.)
- [ ] Dark/light theme toggle
- [ ] Internationalization support

## Design & Collaboration

This project showcases effective collaboration between frontend development and UI/UX design, resulting in a cohesive and engaging user experience.

## Contributors

- **Backend Development & Frontend Framework**: [Psalm Eleazar G. Videna](https://github.com/P541M)
- **Concept Art, Design & Frontend Development**: [Emily Chang](https://github.com/milychang19)

## Let's Connect!

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:videna.psalmeleazar@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pevidena/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/P541M)

---

*Built with care and a lot of syrup*
