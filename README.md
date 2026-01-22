# Anirban Ray - Personal Academic Website

A modern, responsive personal website inspired by PhD student portfolios from MIT, Stanford, Oxford, and Cambridge.

## 🎯 Features

- **Clean, Modern Design**: Minimalist academic aesthetic with professional typography
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in effects and smooth scrolling for better UX
- **SEO Optimized**: Semantic HTML structure for better discoverability
- **Fast Loading**: Lightweight CSS and vanilla JavaScript

## 📁 Project Structure

```
personal_website/
├── index.html                 # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css        # All styling
│   ├── js/
│   │   └── main.js           # Interactive features
│   └── images/
│       └── profile.jpg       # Your profile photo (ADD THIS!)
└── README.md                  # This file
```

## 🚀 Setup Instructions

### 1. Add Your Profile Photo

Copy your photo from the temple (the one you shared) to:
```bash
/Users/anirbanray/CascadeProjects/personal_website/assets/images/profile.jpg
```

The website expects a file named `profile.jpg` in the `assets/images/` folder.

### 2. View Locally

Simply open `index.html` in your web browser:

```bash
# Option 1: Double-click index.html

# Option 2: From terminal
open index.html

# Option 3: Use Python's built-in server
cd /Users/anirbanray/CascadeProjects/personal_website
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

### 3. Deploy Online

#### Option A: GitHub Pages (Free, Recommended)

1. Create a GitHub repository named `your-username.github.io`
2. Push your files:
   ```bash
   cd /Users/anirbanray/CascadeProjects/personal_website
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```
3. Your site will be live at `https://your-username.github.io`

#### Option B: Netlify (Free, Drag & Drop)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your `personal_website` folder
3. Site goes live instantly with a custom URL

#### Option C: Vercel (Free, Fast)

1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload folder
3. Deploys in seconds

## ✏️ Customization

### Update Content

All content is in `index.html`. Key sections:

- **Line 30-50**: Hero section (name, title, contact)
- **Line 60-75**: About text
- **Line 80-120**: Research/Thesis work
- **Line 130-180**: Projects
- **Line 190-240**: Experience timeline
- **Line 250-290**: Achievements
- **Line 300-330**: Contact information

### Modify Colors

Edit color variables in `assets/css/styles.css` (lines 9-18):

```css
:root {
    --primary-color: #2563eb;      /* Change to your preferred color */
    --secondary-color: #1e40af;
    /* ... */
}
```

### Add Social Links

Add to the contact section in `index.html`:

```html
<a href="https://github.com/yourusername" class="btn-secondary">GitHub</a>
<a href="https://linkedin.com/in/yourprofile" class="btn-secondary">LinkedIn</a>
<a href="https://scholar.google.com/citations?user=YOUR_ID" class="btn-secondary">Google Scholar</a>
```

## 📱 Mobile Responsive

The website automatically adapts to:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🎨 Design Inspiration

Inspired by academic portfolios from:
- MIT CSAIL PhD students
- Stanford AI Lab researchers
- Oxford Computer Science Department
- Cambridge Machine Learning Group

## 📝 Future Enhancements

Consider adding:
- [ ] Google Scholar integration for publications
- [ ] Blog section for research updates
- [ ] Dark mode toggle
- [ ] PDF resume download
- [ ] Research project demos/videos
- [ ] Publication citation metrics

## 🐛 Troubleshooting

**Profile photo not showing:**
- Ensure the file is named exactly `profile.jpg`
- Check the file path: `assets/images/profile.jpg`
- Clear browser cache (Cmd+Shift+R on Mac)

**Layout issues:**
- Try different browsers (Chrome, Safari, Firefox)
- Check browser console for errors (F12)

**Deployment issues:**
- Ensure all file paths are relative (no absolute paths)
- Check that all files are uploaded
- Verify folder structure is maintained

## 📧 Contact

**Anirban Ray**  
Email: anirbanray100@gmail.com  
Phone: +91-6294605824  
Location: IIT Delhi, New Delhi, India

---

Built with ❤️ using HTML, CSS, and vanilla JavaScript  
No frameworks, no dependencies, just clean code!
