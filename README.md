# CodingBlue - A Mental Health Awareness Website for Software Developers

<!-- TODO: Place screenshot here -->

A beginner-friendly, responsive webpage focused on mental health awareness, designed to provide accessible information and resources in a supportive and calming environment.

Note: This project is for demonstration purposes, which means that 

## About This Project

This website aims to reduce mental health stigma by providing:
- Clear, accessible information about mental health conditions
- Warning signs to watch for
- Crisis resources and professional help options
- Positive messaging and affirmations
- A clean, supportive user experience using Bootstrap

The site is built with HTML, CSS, and Bootstrap, following web accessibility guidelines and UX design principles to ensure the information is easy to find and understand.

## Features

- **Hero Section**: Welcoming message with positive mental health messaging
- **Information Cards**: Bootstrap card components presenting mental health tips and common conditions
- **Resource Links**: Crisis hotlines and professional help information
- **Statistics Section**: Key mental health facts presented visually
- **Responsive Design**: Mobile-friendly layout using Bootstrap
- **Accessibility**: Semantic HTML and WCAG compliance

## Screenshots

### Desktop View
![Desktop Homepage](screenshots/desktop-home.png)
*Main homepage featuring hero section and navigation*

![Desktop Resources](screenshots/desktop-resources.png)
*Resources section with crisis hotlines and professional help information*

### Mobile View
![Mobile Homepage](screenshots/mobile-home.png)
*Mobile-responsive design showing hero section*

![Mobile Navigation](screenshots/mobile-nav.png)
*Mobile navigation menu*

## Deployment to GitHub Pages

Follow these steps to deploy your website to GitHub Pages:

### Prerequisites
- A GitHub account
- Git installed on your computer
- Your project files ready

### Step 1: Create a GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `mental-health-awareness`)
5. Make sure it's set to "Public"
6. Check "Add a README file" if you haven't created one
7. Click "Create repository"

### Step 2: Upload Your Files
**Option A: Using GitHub Web Interface**
1. In your new repository, click "uploading an existing file"
2. Drag and drop your project files or click "choose your files"
3. Add a commit message like "Initial website upload"
4. Click "Commit changes"

**Option B: Using Git Commands**
```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git

# Navigate to the repository folder
cd YOUR-REPOSITORY-NAME

# Copy your project files to this folder
# Then add, commit, and push
git add .
git commit -m "Initial website upload"
git push origin main
```

### Step 3: Enable GitHub Pages
1. In your repository, click on "Settings" (top menu)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch
5. Leave the folder as "/ (root)"
6. Click "Save"

### Step 4: Access Your Live Website
1. GitHub will provide a URL like: `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`
2. It may take a few minutes for the site to become available
3. You can find the URL in the "Pages" settings or in the "About" section of your repository

### Step 5: Update Your Website
To make changes to your live website:
1. Edit your files locally or directly on GitHub
2. Commit and push changes to the main branch
3. GitHub Pages will automatically update your live site

## Project Structure

```
mental-health-awareness/
│
├── index.html              # Main HTML file
├── assets/
│   └── styles/
│       └── style.css       # Custom CSS styles
├── screenshots/            # Website screenshots
├── README.md               # This file
└── .github/
    └── copilot-instructions.md
```

## Technologies Used

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Custom styling and layout
- **Bootstrap 5.3.2**: Responsive framework and components
- **WebP Images**: Optimized image format for better performance

## Accessibility Features

- Semantic HTML elements for screen readers
- Proper heading hierarchy (h1-h6)
- Alt text for all images
- High contrast color scheme
- Keyboard navigation support
- WCAG 2.1 AA compliance

## Resources and Credits

### Mental Health Resources
- **Crisis Text Line**: Text HOME to 741741
- **National Suicide Prevention Lifeline**: 988
- **International Association for Suicide Prevention**: [https://www.iasp.info/resources/Crisis_Centres/](https://www.iasp.info/resources/Crisis_Centres/)

### Technical Resources
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/WCAG21/quickref/)

## Contributing

This is an educational project, but suggestions for improving accessibility or user experience are welcome. Please open an issue or submit a pull request.