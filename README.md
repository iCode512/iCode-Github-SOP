# iCode-Github-SOP

## Purpose
To keep student GitHub repositories organized, easy to navigate, and simple to review. All instructors are required to instruct students to follow the folder structure and naming conventions outlined below.

## 1. Repository Naming Convention
Repositories should use the following labeling format:
belt-sprint-project-student's initials-year

### Examples of this would be:
<ul>
 <li>Orange-belt-sprint-5-javascript-to-do-list-AB-26</li>
 <li>Orange-belt-sprint-9-final-project-web-dev-portfolio-CD-26</li>
 <li>Green-belt-sprint-3-python-data-analysis-EF-26</li>
</ul>

### Guidelines:
<ul>
  <li> CHOOSE DESCRIPTIVE WORDS THAT REPRESENT YOUR PROJECT  </li>
  <li>Separate words with hyphens or underscore if necessary</li>
  <li>Do not use spaces</li>
  <li>Void special characters</li>
</ul>


## 2. Required Folder Structure

Each project folder should have a descriptive name. Within that folder, each project should follow this basic structure:

### Example

```text 
project-name/ 
│ 
├── assets/ 
│ ├── images/ 
│ ├── icons/ 
│ └── fonts/ 
│ 
├── css/ 
│ └── styles.css 
│ 
├── js/ 
│ └── main.js 
│
├── html/ 
|  └── about.html 
│ 
├── README.md 
├── .gitignore 
└── index.html
```

## 3. File Naming Convention:

### Use lowercase letters

Good
<ul>
 <li>about.html</li>
 <li>styles.css</li>
 <li>main.js</li>
</ul>


Avoid
<ul>
 <li>About.html</li>
 <li>Main.JS</li>
 <li>Styles.CSS</li>
</ul>

### Separate words with hyphens

Good

<ul>
 <li>contact-form.js</li>
<li>student-profile.html</li>
<li>landing-page.css</li>
</ul>


Avoid
<ul>
 <li>contactForm.js</li>
 <li>Student Profile.html</li>
</ul>

### Keep names descriptive

Good

<ul>
 <li>login.js</li>
 <li>dashboard.css</li>
 <li>profile-card.js</li>
</ul>


Avoid

<ul>
 <li>file1.js</li>
<li>new.js</li>
<li>temp.css</li>
</ul>

### Image Naming

Use descriptive names:

Good
<ul>
 <li>hero-image.jpg</li>
<li>student-photo.png</li>
<li>logo.svg</li>
</ul>


Avoid

<ul>
 <li>IMG1234.jpg</li>
<li>image.png</li>
<li>photo-final-final.png</li>
<li>screenshot-8.23.26 at 3:48.46PM.png</li>
</ul>

## 4. Documentation

Every repository should include a README.md containing:

<ul>
<li>Project title</li>
<li>Project description</li>
<li>Technologies used</li>
<li>Installation instructions (if applicable)</li>
<li>How to run the project</li>
<li>Screenshots (optional)</li>
<li>What was learned </li>
<li>What could be improved</li>
<li>Follow ups</li> 
</ul>

## 5. Files That Should Not Be Committed

Students should use a .gitignore file to exclude unnecessary files such as:

<ul>
<li>node_modules/</li>
<li>.env</li>
<li>.DS_Store</li>
<li>dist/</li>
<li>build/</li>
</ul>

Do not commit passwords, API keys, or other sensitive information.
