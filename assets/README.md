# Assets Folder

This folder contains images for the Innovation Challenge presentation.

## Profile Photo

1. Add your photo as `profile.jpg` (or `profile.png`) in this folder
2. Recommended size: 400x400 pixels (square)
3. Recommended format: JPG or PNG
4. File size: Keep under 500KB for faster loading

## How to Update Your Profile

1. Place your photo in this folder as `profile.jpg`
2. Open `index.html` in a text editor
3. Find the profile photo section around line 700
4. Replace the placeholder div with:

```html
<img src="assets/profile.jpg" alt="Your Name">
```

5. Update your details in the profile section:
   - Replace "Your Name" with your actual name
   - Replace "your.email@example.com" with your email
   - Update the title if needed

## Current Profile Section in index.html

```html
<div class="profile-photo">
    <!-- Add your photo as 'profile.jpg' in the assets folder -->
    <div class="placeholder">👨‍💻</div>
    <!-- To use your photo, replace the div above with: -->
    <!-- <img src="assets/profile.jpg" alt="Your Name"> -->
</div>
<div class="profile-info">
    <span class="badge">🚀 Innovation Challenge 2025</span>
    <h1>Your Name</h1>
    <p class="title">Full Stack Developer | AI Enthusiast | Innovation Pioneer</p>
    <div class="contact">
        <span>📧</span>
        <a href="mailto:your.email@example.com">your.email@example.com</a>
    </div>
</div>
```

## Example

If your name is "John Doe" and email is "john.doe@company.com", update it to:

```html
<div class="profile-photo">
    <img src="assets/profile.jpg" alt="John Doe">
</div>
<div class="profile-info">
    <span class="badge">🚀 Innovation Challenge 2025</span>
    <h1>John Doe</h1>
    <p class="title">Full Stack Developer | AI Enthusiast | Innovation Pioneer</p>
    <div class="contact">
        <span>📧</span>
        <a href="mailto:john.doe@company.com">john.doe@company.com</a>
    </div>
</div>
```
