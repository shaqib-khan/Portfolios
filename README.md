# 💬 Chatbot Portfolio

A modern, interactive portfolio website designed as a messaging app where visitors can chat with a bot to learn about your skills, projects, and experience.

## ✨ Features

- **Chat Interface**: Looks and feels like a real messaging app
- **Interactive Chatbot**: Responds to user messages and provides portfolio information
- **Quick Options**: Easy-to-click buttons for common inquiries
- **Social Media Integration**: Beautiful social profile links with hover effects
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **Typing Indicators**: Realistic chat experience with typing animations

## 🚀 Getting Started

1. **Clone or Download** this project to your computer
2. **Customize Your Information** (see customization section below)
3. **Open `index.html`** in your web browser
4. **Deploy** to your preferred hosting platform

## 🎨 Customization

### 1. Update Your Personal Information

Edit the `portfolioData` object in `script.js` (around line 25):

```javascript
this.portfolioData = {
    about: {
        name: "Your Name Here",           // ← Change this
        title: "Your Job Title",          // ← Change this
        description: "Your bio...",       // ← Change this
        location: "Your City, Country",   // ← Change this
        email: "your.email@example.com",  // ← Change this
        phone: "+1 (555) 123-4567",      // ← Change this
        github: "https://github.com/yourusername",        // ← Add your GitHub
        linkedin: "https://linkedin.com/in/yourprofile"   // ← Add your LinkedIn
    },
    // ... continue updating other sections
}
```

### 2. Add Your Skills

Update the `skills` section with your technologies:

```javascript
skills: {
    frontend: ["React", "Vue.js", "JavaScript", "TypeScript"], // ← Add your skills
    backend: ["Node.js", "Python", "Django"],                 // ← Add your skills
    database: ["MongoDB", "PostgreSQL", "MySQL"],             // ← Add your skills
    tools: ["Git", "Docker", "AWS", "Figma"]                  // ← Add your skills
}
```

### 3. Add Your Projects

Replace the sample projects with your own:

```javascript
projects: [
    {
        title: "Your Project Name",
        description: "Brief description of your project",
        technologies: ["React", "Node.js", "MongoDB"],
        link: "https://github.com/yourusername/project",
        status: "Completed" // or "In Progress"
    },
    // Add more projects...
]
```

### 4. Add Your Experience

Update with your work experience:

```javascript
experience: [
    {
        company: "Your Company Name",
        position: "Your Job Title",
        duration: "2022 - Present",
        description: "What you did at this job..."
    },
    // Add more experiences...
]
```

### 5. Customize Colors and Styling

To change the color scheme, edit the CSS variables in `styles.css`:

```css
/* Find these gradient colors and replace them */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* You can use any colors you like, for example: */
background: linear-gradient(135deg, #ff6b6b 0%, #4ecdc4 100%);
```

### 6. Add Your Resume

Replace the resume download link in the `showResume()` function in `script.js`:

```javascript
// Replace the onclick alert with your actual resume link
<a href="path/to/your/resume.pdf" download="YourName_Resume.pdf">
```

## 📱 Mobile Responsive

The chatbot is fully responsive and optimized for all devices:
- 📱 **Mobile phones** (320px - 480px): Full-screen experience with touch-optimized buttons
- 📱 **Large phones** (481px - 768px): Tablet-like experience with rounded corners
- 💻 **Tablets** (769px+): Centered chat window with desktop-like experience
- 🖥️ **Desktop computers**: Original design with hover effects

### Mobile Features:
- **Touch-optimized buttons** with proper tap targets (44px minimum)
- **Prevents zoom on input focus** (iOS Safari)
- **Handles orientation changes** smoothly
- **Keyboard-aware scrolling** when typing
- **iOS Safari viewport fixes** for proper full-height display
- **Smooth scrolling** with momentum on iOS
- **Prevents pull-to-refresh** interference

## 🌐 Deployment

You can deploy this portfolio to any static hosting service:

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select your branch and deploy

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be live instantly

### Vercel
1. Import your GitHub repository
2. Deploy with one click

## 🎯 Customization Tips

1. **Welcome Message**: Edit the initial bot messages in `index.html`
2. **Chat Header**: Change "Portfolio Assistant" to your preferred name
3. **Add New Options**: Add more quick option buttons by editing the HTML and JavaScript
4. **Social Links**: Add LinkedIn, GitHub, or other social media links
5. **Profile Picture**: Replace the avatar icons with your actual photo

## 🔧 Technical Details

- **HTML5**: Semantic structure
- **CSS3**: Modern styling with Flexbox and animations
- **Vanilla JavaScript**: No frameworks required
- **Font Awesome**: Icons for a professional look
- **Google Fonts**: Inter font for clean typography

## 📞 Support

If you need help customizing your portfolio:
1. Check the comments in the code
2. Refer to this README
3. Test your changes by opening `index.html` in a browser

## 🎉 Features to Add (Optional)

- **Dark Mode**: Add a toggle for dark/light themes
- **More Languages**: Add multi-language support
- **Contact Form**: Add a working contact form
- **Blog Integration**: Connect to a blog or CMS
- **Analytics**: Add Google Analytics tracking

---

**Happy coding! 🚀** Your new chatbot portfolio is ready to impress visitors and showcase your skills in a unique, interactive way.
