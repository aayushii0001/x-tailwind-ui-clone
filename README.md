# Twitter/X Clone - Social Media Interface

A responsive, modern social media feed interface built with HTML, CSS (Tailwind), and Material Icons. This project replicates the core UI/UX of Twitter/X's home feed with a dark theme design.

## 📋 Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Responsive Design](#responsive-design)
- [Customization](#customization)
- [Future Enhancements](#future-enhancements)

## ✨ Features

- **Responsive Layout**: Adapts seamlessly to mobile, tablet, and desktop screens
- **Dark Theme**: Modern black and gray color scheme matching X's branding
- **Interactive Sidebar Navigation**: Quick access to Home, Explore, Notifications, Messages, and more
- **Post Feed**: Display of user posts with engagement metrics (comments, retweets, likes, views)
- **Trending Section**: Shows trending topics and hashtags by region
- **Who to Follow**: Curated list of accounts to follow with Follow buttons
- **Post Composition**: Text input area for composing new posts
- **Engagement Icons**: Interactive icons for comments, retweets, likes, and analytics
- **Hover Effects**: Smooth hover states on interactive elements

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Styling via Tailwind CSS utility framework
- **Tailwind CSS**: Responsive utility-first CSS framework
- **Material Design Icons**: Icon set from Google's Material Symbols
- **Responsive Design**: Mobile-first approach with breakpoints

## 📸 Preview 
<img width="1411" height="814" alt="Screenshot 2026-02-07 191944" src="https://github.com/user-attachments/assets/a7e7a3aa-7a35-4eeb-adb5-c595eb1606fc" />



## 📦 Installation

1. **Clone or download the project**:
   ```bash
   git clone <repository-url>
   cd twitter-clone
   ```

2. **No build process required** - This is a static HTML/CSS project
   - Simply open `index.html` in your browser, or
   - Use a local server for best results

3. **Using a local server** (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js (with http-server)
   npx http-server

   # Using Live Server in VS Code
   # Install the Live Server extension and right-click > Open with Live Server
   ```

4. **Access the application**:
   - Open `http://localhost:8000` in your browser (adjust port if different)

## 🚀 Usage

Simply open the `index.html` file in a web browser. The interface displays:

1. **Left Sidebar**: Navigation menu with icons (visible on all screen sizes)
2. **Center Feed**: Main content area with the post composition box and feed
3. **Right Sidebar**: Trending topics and "Who to Follow" section (visible only on large screens)

All elements are styled and ready for JavaScript interactivity to be added.

## 📁 File Structure

```
twitter-clone/
├── index.html              # Main HTML file
├── css/
│   └── output.css         # Compiled Tailwind CSS styles
├── README.md              # This file
└── assets/                # (optional) Place images and icons here
```

### Key HTML Sections

**Sidebar Navigation** (Left Column):
- Logo
- Navigation menu items with icons
- Post button

**Main Feed** (Center Column):
- Tab navigation ("For you" and "Following")
- Post composition area
- Feed of posts from various users
- Each post includes username, timestamp, content, image, and engagement metrics

**Trending/Follow** (Right Column):
- Search bar
- "What's Happening" trending section
- "Who to Follow" recommendations

## 📱 Responsive Design

The layout uses Tailwind's responsive breakpoints:

- **Mobile (default)**: Single column with collapsed sidebar
- **Medium (md)**: Two columns with expanded sidebar
- **Large (lg)**: Three columns with full sidebar and right sidebar visible

**Breakpoint Classes Used**:
- `hidden lg:block` - Hide on mobile, show on large screens
- `md:w-64` - Apply width on medium screens and up
- `sm:px-4` - Add padding on small screens and up

## 🎨 Customization

### Colors

Update the color scheme by modifying Tailwind utility classes:

- **Primary Blue**: `#1d9bf0` (used for buttons, links, hover states)
- **Background**: `bg-black` (main dark theme)
- **Secondary Background**: `#16181c` (cards, sections)
- **Borders**: `border-gray-500`

### Fonts

Material Symbols Outlined is imported from Google Fonts. To change icons, update the `<span class="material-symbols-outlined">` elements with different icon names from the [Material Symbols library](https://fonts.google.com/icons).

### Layout Spacing

Tailwind utility classes control spacing:
- `gap-4`, `gap-3`, `gap-2` - Gap between flex items
- `my-3`, `my-4` - Vertical margin
- `px-2`, `px-4` - Horizontal padding

## 🔧 Future Enhancements

- **JavaScript Functionality**:
  - Post submission and display
  - Like/retweet/comment interactions
  - Dynamic user following
  - Search functionality
  - Notifications system

- **Backend Integration**:
  - User authentication
  - Database for posts and user data
  - Real-time updates using WebSockets
  - Image upload handling

- **Additional Features**:
  - Dark/Light theme toggle
  - User profile pages
  - Direct messaging
  - Thread/reply system
  - Media gallery
  - Advanced filtering

## 📝 Notes

- This is a **frontend-only** project with static content
- Images are currently sourced from external URLs
- No backend or database integration is included
- All interactivity would need to be added via JavaScript

## 🤝 Contributing

Feel free to fork, modify, and improve this project. Consider adding:
- JavaScript interactivity
- Backend API integration
- Additional features
- Performance optimizations

## 📄 License

This project is open source and available for educational purposes.

## 🔗 Resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Material Symbols Icons](https://fonts.google.com/icons)
- [X/Twitter Design Reference](https://twitter.com/home)

---

Built with ❤️ as a Twitter/X interface clone
