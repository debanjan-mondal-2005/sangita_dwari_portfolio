# Sangita Dwari - Professional Nursing Portfolio

A modern, responsive portfolio website for BSc Nursing student at NSMS Nursing Institute.

## 🌟 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean and professional design with smooth animations
- **Interactive Elements** - Smooth scrolling, navigation highlighting, and skill progress bars
- **Contact Form** - Integrated contact form for professional inquiries
- **Social Media Integration** - LinkedIn and other social media links

## 📁 Project Structure

```
Portfolio Two/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with all styling
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🚀 How to Deploy on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Name your repository (e.g., `nursing-portfolio` or `<your-username>.github.io`)
5. Make sure it's set to **Public**
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. On your repository page, click **"uploading an existing file"**
2. Drag and drop all files (`index.html`, `styles.css`, `script.js`)
3. Click **"Commit changes"**

**Option B: Using Git Command Line**
```bash
# Navigate to your project folder
cd "c:\Users\USER\OneDrive\Desktop\Portfolio Two"

# Initialize Git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Add portfolio website"

# Add your GitHub repository as remote (replace with your repository URL)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **"Settings"**
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"main"** branch
5. Click **"Save"**
6. Your site will be published at: `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

### Step 4: Access Your Website

After a few minutes, your website will be live! Visit:
- If repository name is `<username>.github.io`: `https://<username>.github.io/`
- Otherwise: `https://<username>.github.io/<repository-name>/`

## ✏️ Customizing Content with LinkedIn Information

### Update the Following Sections:

#### 1. **Personal Information** (index.html)
- Replace placeholder email: `sangita.dwari@example.com`
- Add phone number
- Update location
- Update social media links

#### 2. **About Section**
- Update the bio paragraphs with actual information from LinkedIn "About" section
- Add a profile photo (replace the placeholder icon)

#### 3. **Education Section**
- Add complete education history from LinkedIn
- Include:
  - Degree name
  - Institution name
  - Dates
  - Key achievements or coursework

#### 4. **Skills Section**
- Review and update skill proficiency percentages
- Add or remove skills based on LinkedIn profile
- Customize skill categories

#### 5. **Experience Section**
- Update clinical rotations and training details
- Add any volunteer work or internships
- Include specific accomplishments

#### 6. **Certifications** (if needed)
- Add a new section for certifications from LinkedIn
- Include First Aid, BLS, or other nursing certifications

### How to Add a Profile Photo:

1. Save your profile photo in the project folder
2. In `index.html`, find this section:
```html
<div class="image-placeholder">
    <i class="fas fa-user-nurse"></i>
</div>
```

3. Replace it with:
```html
<img src="your-photo.jpg" alt="Sangita Dwari" style="width: 250px; height: 250px; border-radius: 50%; object-fit: cover; box-shadow: 0 10px 30px rgba(0,0,0,0.15);">
```

## 🎨 Customization Options

### Change Color Scheme
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c5f8d;      /* Main blue color */
    --secondary-color: #4a90c5;    /* Light blue */
    --accent-color: #e85d75;       /* Pink/red accent */
}
```

### Add New Sections
Copy the structure of existing sections and modify as needed.

### Modify Contact Form
The contact form currently uses mailto. For real form submission, integrate with:
- [Formspree](https://formspree.io/)
- [EmailJS](https://www.emailjs.com/)
- [Web3Forms](https://web3forms.com/)

## 📱 Responsive Design

The website automatically adapts to:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🔧 Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
- **JavaScript** - Interactivity and dynamic features
- **Font Awesome** - Icons

## 📝 To-Do After Deployment

- [ ] Update all placeholder content with real information from LinkedIn
- [ ] Add profile photo
- [ ] Verify all links work correctly
- [ ] Test contact form functionality
- [ ] Add resume/CV download link (optional)
- [ ] Set up Google Analytics (optional)
- [ ] Add custom domain (optional)

## 📄 License

Free to use and modify for personal portfolio purposes.

## 📞 Support

For questions or issues, please contact through the website's contact form.

---

**Note**: Remember to update all placeholder information with actual details from the LinkedIn profile before sharing the website publicly!
