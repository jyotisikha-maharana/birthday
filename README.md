# 🎂 Happy Birthday Card for Akshat

A beautiful, interactive web-based birthday card created with HTML, CSS, and JavaScript. This project features animated elements, sound effects, and a personalized birthday message.

## ✨ Features

- 🎈 Animated balloons and confetti
- 🎵 Background music and sound effects
- 🎁 Interactive elements and animations
- 📱 Responsive design for all devices
- 🎨 Beautiful visual effects and transitions

## 🚀 Live Demo

The birthday card is currently running locally at: `http://localhost:3000`

## 🛠️ Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- npm

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd Happy-Birthday-Card
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   NAME='Akshat'
   PIC='sample-pic.jpg'
   ```

4. **Build the project**
   ```bash
   npm run init-index-local
   npm run build:parcel
   ```

5. **Serve locally**
   ```bash
   npx serve dist
   ```

## 🎯 Customization

### Changing the Birthday Person
Edit the `.env` file:
```env
NAME='New Name'
PIC='new-image.jpg'
```

### Adding a Scroll Message
1. Add your message text to `local/scroll-message.txt`
2. Update `.env`:
   ```env
   SCROLL_MSG='scroll-message.txt'
   ```

### Changing the Birthday Message
Add to `.env`:
```env
HBD_MSG='Your custom birthday message'
```

## 📁 Project Structure

```
Happy-Birthday-Card/
├── src/                    # Source files
│   ├── index.html         # Main HTML file
│   ├── js/               # JavaScript files
│   ├── scss/             # SCSS styles
│   └── resources/        # Images, sounds, etc.
├── local/                # Local assets
├── dist/                 # Built files
├── builder/              # Build scripts
└── docs/                 # Documentation
```

## 🎨 Technologies Used

- **HTML5** - Structure
- **CSS3/SCSS** - Styling and animations
- **JavaScript (ES6+)** - Interactivity
- **Parcel** - Build tool
- **Node.js** - Development environment

## 📝 License

This project is open source and available under the [ISC License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and create your own personalized birthday cards!

---

**Made with 💖 for Akshat's Birthday** 