# Music-player
# 🎵 Responsive Music Player

A beautiful, fully-functional music player built with HTML, CSS, and vanilla JavaScript. Features a modern design with smooth animations and complete audio controls.

![Music Player](https://img.shields.io/badge/Music-Player-purple?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

### Core Functionality
- ▶️ **Play/Pause Control** - Smooth playback controls
- ⏮️ **Previous Track** - Go back to previous song
- ⏭️ **Next Track** - Skip to next song
- 📊 **Progress Bar** - Visual progress with clickable seek functionality
- 🔊 **Volume Control** - Adjustable volume slider with dynamic icons
- ℹ️ **Song Information Display** - Shows title, artist, and duration

### Bonus Features
- 📀 **Full Playlist** - Interactive playlist with 5 sample tracks
- 🔁 **Autoplay Mode** - Automatically plays next song when current ends
- 🎨 **Rotating Album Art** - Visual animation while playing
- 🎯 **Active Song Highlighting** - Shows currently playing track
- 👆 **Click-to-Play** - Click any song in playlist to play instantly

## 🎨 Design Features

- **Modern UI/UX** - Clean, intuitive interface
- **Gradient Theme** - Beautiful purple gradient design
- **Glass-morphism Effect** - Frosted glass aesthetic
- **Smooth Animations** - Polished transitions and hover effects
- **Responsive Layout** - Works perfectly on mobile, tablet, and desktop
- **Dynamic Icons** - Volume icon changes based on level

## 🚀 Demo

[Live Demo](#)  https://minahil2117.github.io/Music-player/

## 🛠️ Technologies Used

- **HTML5** - Structure and audio element
- **CSS3** - Styling, animations, and responsive design
- **JavaScript** - Audio controls and interactive functionality
- **Audio API** - HTML5 Audio for playback

## 🎵 Adding Your Own Music

To add your own songs, edit the `playlist` array in the JavaScript code:

```javascript
const playlist = [
    {
        title: "Your Song Title",
        artist: "Artist Name",
        duration: "3:45",
        src: "path/to/your/audio.mp3"
    },
    // Add more songs...
];
```

## 📱 Responsive Breakpoints

- **Desktop**: 481px and above
- **Mobile**: 480px and below

## 🎯 Features Breakdown

### Audio Controls
- Play/Pause toggle
- Previous/Next track navigation
- Seek functionality via progress bar
- Volume adjustment (0-100%)

### Playlist Management
- Display all available tracks
- Click to play any track
- Visual indication of active track
- Smooth transitions between songs

### Autoplay System
- Toggle on/off functionality
- Seamless track transitions
- Loop through entire playlist

## 🌟 Key Highlights

- **Zero Dependencies** - Pure vanilla JavaScript
- **Lightweight** - Single HTML file
- **Cross-browser Compatible** - Works on all modern browsers
- **Mobile-First Design** - Optimized for touch devices
- **Accessible** - Keyboard and screen reader friendly

## 🎨 Color Scheme

- Primary Gradient: `#667eea` → `#764ba2`
- Background: Gradient purple theme
- Text: `#333` (dark) / `#666` (medium) / `#999` (light)
- Accent: White with transparency

## 📝 Code Structure

```
music-player/
│
├── index.html          # Main HTML file with embedded CSS & JS
├── README.md          # Project documentation
└── assets/            # (Optional) Store audio files here
```

## 🔧 Customization

### Change Colors
Modify the CSS gradient values:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Adjust Animation Speed
Change the rotation speed:
```css
animation: rotate 20s linear infinite;
```

### Modify Player Size
Update max-width in `.player-container`:
```css
max-width: 400px; /* Change this value */
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Minahil Fatima**
- GitHub: [https://github.com/Minahil2117]
- LinkedIn: [www.linkedin.com/in/minahil-fatima17]

## 🙏 Acknowledgments

- Sample audio files from [SoundHelix](https://www.soundhelix.com/)
- Inspired by modern music player designs
- Icons using Unicode emoji characters

## 📞 Contact

Have questions or suggestions? Feel free to reach out!

- Email: fminahil862@gmail.com

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

---

Made with ❤️ and JavaScript
