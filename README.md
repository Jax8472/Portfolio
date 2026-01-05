# Portfolio Website Template

This is a clean, minimal portfolio template inspired by Heinrich Zaunschirm's design aesthetic.

## What You Got

- **portfolio-template.html** - The main page structure
- **styles.css** - All the styling (colors, fonts, layout)

## How to Use This

### 1. BASIC SETUP
- Create a folder on your computer called "my-portfolio"
- Put both files in that folder
- Create a subfolder called "images" for your project photos
- Open `portfolio-template.html` in a web browser to see it

### 2. CUSTOMIZE THE TEXT
Open `portfolio-template.html` in any text editor (even Notepad works).

**Replace these:**
- Line 6: Change "Your Name - Portfolio" to your actual name
- Line 14: Change "your name" to your name (this appears in the top left)
- Lines 15-17: Update the navigation links if needed
- Lines 23-24: Write your own intro (the "Hello!" section)
- Lines 32-74: Add your projects

**For each project:**
```html
<div class="project-item">
    <a href="project1.html">  <!-- Link to project detail page -->
        <div class="project-image">
            <img src="images/project1.jpg" alt="Project 1">  <!-- Your image -->
        </div>
        <h2>PROJECT TITLE</h2>  <!-- Your project name -->
        <p class="project-description">Short description</p>  <!-- What it is -->
    </a>
</div>
```

### 3. ADD YOUR IMAGES
- Save your project photos as JPGs in the "images" folder
- Name them something simple like: project1.jpg, project2.jpg, etc.
- Update the image paths in the HTML to match your filenames

### 4. CUSTOMIZE THE LOOK
Open `styles.css` to change colors, fonts, sizes.

**Common things to change:**
- **Colors**: Search for color codes like `#333` (dark gray) or `#fff` (white) and replace them
- **Fonts**: Line 8 has the font family - you can add Google Fonts here
- **Spacing**: Look for `padding` and `margin` values to adjust spacing
- **Grid layout**: Line 84 controls how many columns (`minmax(350px, 1fr)` - change 350px to make columns wider/narrower)

### 5. GOING LIVE
Once you're happy with it:
- You can host it for free on GitHub Pages, Netlify, or Vercel
- Just upload your folder and they'll give you a URL

## Key Design Features

- **Minimal aesthetic** - Clean, lots of white space
- **Image hover effect** - Images zoom slightly when you hover
- **Responsive** - Automatically adjusts for phones/tablets
- **Typography-focused** - Simple, readable fonts

## Need to Add More?

**More projects:** Just copy-paste one `<div class="project-item">` block and change the content

**New pages:** Create new HTML files like `about.html` and link to them in the navigation

**Contact form:** You'll need to add JavaScript or use a service like Formspree

## Questions?

The HTML file is the CONTENT (what you see).
The CSS file is the STYLE (how it looks).

Change HTML to change words/images.
Change CSS to change colors/fonts/layout.
