# 🎉 Birthday Wish Project

A beautiful and interactive web application to send and celebrate birthday wishes with animated effects and personalized messages.

## ✨ Features

- 🎂 **Birthday Wishes** - Create and send personalized birthday messages
- 🎨 **Animated Effects** - Beautiful animations and visual effects
- 💬 **Interactive Interface** - User-friendly and responsive design
- 🎯 **Customizable Messages** - Personalize wishes with custom text
- 📱 **Responsive Design** - Works seamlessly on all devices
- 🎪 **Visual Elements** - Balloons, confetti, and festive decorations

## 🛠️ Tech Stack

- **HTML** (46.7%) - Markup and structure
- **JavaScript** (29.9%) - Interactive functionality and animations
- **CSS** (23.4%) - Styling and visual effects

## 📁 Project Structure

```
Birthday_Wish-Project/
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Aman-raj048/Birthday_Wish-Project.git
cd Birthday_Wish-Project
```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local server (optional)
   ```bash
   python -m http.server 8000
   # Then navigate to http://localhost:8000
   ```

## 💡 Usage

1. Open `index.html` in your web browser
2. The page loads with smooth animations automatically
3. Background birthday music plays (you can mute if needed)
4. Scroll through 9 animated sections showing:
   - Greeting message with name
   - Birthday announcement
   - Chat-style message
   - Emotional narrative
   - Profile picture with birthday wish
   - Balloon animations
   - Confetti effects
   - Memory gallery
   - Final message with replay button
5. Click the 💞 (replay button) at the end to watch the animation again.


## 🎨 Customization

### Change the Name
- Open index.html
- Line 30: Replace <span id="name">Aman</span> with your desired name
- The name will appear throughout the page

### Customize Greeting Text
- Line 32: Edit id="greetingText" to change the greeting message
- Example: <p class="two" id="greetingText">I think you're awesome! 💕</p>

### Update Birthday Message
- Lines 41-43: Edit the hbd-chatbox paragraph with your custom message
- This is the chat-style message that appears early in the animation
  
### Modify the Birthday Wish
- Lines 71-79: Edit the text inside id="wishText"
- Replace Lorem ipsum with your personalized birthday wish
- Keep the br tags for line breaks

### Add Your Photos
- Profile Picture:
   - Line 67: Replace ./img/aman.jpeg with your image path
   - Recommended size: Square image (300x300px)
- Memory Gallery:
   - Lines 155-170: Replace image paths from ./img/one.jpeg to ./img/fifteen.jpeg
   - Add or remove <img> tags as needed
   - Recommended size: 200x200px square images
Change the gallery title (Line 153): Our Some Memories 💖

### Change Background Music
- Line 21: Replace ./music/hbd.mpeg with your audio file path
- Supported formats: .mp3, .mpeg, .wav
- Keep the audio as background (loops automatically)

### Customize Colors & Fonts
- Open style/main.css
- Update CSS variables and color codes
- Change font sizes, animations timing
  
Modify balloon and confetti colors
Modify Animation Timing
Open script/main.js
Adjust GSAP animation durations
Change animation sequences and delays
Customize scroll triggers if needed




## 📚 Features Breakdown

### Animations
- Fade-in effects for text
- Balloon floating animations
- Confetti burst effects
- Text scaling animations

### Interactive Elements
- Input fields for name and message
- Submit button with hover effects
- Dynamic content updates
- Responsive button interactions

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

- **GitHub**: [@Aman-raj048](https://github.com/Aman-raj048)
- **Project**: [Birthday_Wish-Project](https://github.com/Aman-raj048/Birthday_Wish-Project)

## 💬 Feedback

Have suggestions or found a bug? Feel free to:
- Open an issue on GitHub
- Submit a pull request with improvements
- Contact the author

---

**Happy Birthday! 🎂🎉🎊**

_Made with ❤️ by Aman Raj
