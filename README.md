# Spotify-Inspired Web Player



A Spotify-inspired music player interface built from scratch using HTML and CSS. I created this project to practice building a clean, responsive frontend and to understand how real-world music streaming interfaces are structured.

The current version focuses on the UI and layout. It includes a sidebar, library section, music cards, navigation controls, and a bottom music-player section.
This is a personal learning project and is not affiliated with or endorsed by Spotify.

# What I Built
- Sidebar with Home, Search, and Library sections
- Playlist and podcast cards in the library
- Recently Played section
- Trending music section
- Featured Charts section
- Music cards with images and descriptions
- Top navigation with back/forward controls
- Install App and profile controls
- Bottom music-player interface
- Responsive layout for different screen sizes
- Custom styling with CSS
- Font Awesome icons and Google Fonts

# Technologies
- HTML5 – structure and content
- CSS3 – layout, styling, Flexbox, and responsiveness
- Font Awesome – interface icons
- Google Fonts – typography
- Git & GitHub – version control and project hosting

# Project Structure
spotify-inspired-web-player/
│
├── assets/
│   ├── logo.png
│   ├── library_icon.png
│   ├── backward_icon.png
│   ├── forward_icon.png
│   ├── player_icon1.png
│   ├── player_icon2.png
│   ├── player_icon3.png
│   ├── player_icon4.png
│   ├── player_icon5.png
│   └── card images...
│
├── index.html
├── style.css
├── README.md
├── .gitignore
└── LICENSE

Getting Started
You don't need any special setup to run this project.
1. Clone the repository:
git clone https://github.com/Gopi-Krishna-Rajarapu/spotify-inspired-web-player.git
2. Open the project folder:
cd spotify-inspired-web-player
3. Open index.html in your browser.
For development, I recommend using the Live Server extension in VS Code.

How the Interface Is Organized
The page is divided into three main areas:
┌──────────────────────────────────────────────────┐
│                    Top Navigation                 │
├───────────────┬──────────────────────────────────┤
│               │                                  │
│    Sidebar    │          Main Content            │
│               │                                  │
│  Home         │  Recently Played                 │
│  Search       │  Trending Music                  │
│  Library      │  Featured Charts                 │
│               │                                  │
├───────────────┴──────────────────────────────────┤
│                  Music Player                    │
└──────────────────────────────────────────────────┘

# What I Learned
While building this project, I practiced:
- Structuring a webpage with semantic HTML
- Creating layouts with CSS Flexbox
- Building reusable card-style sections
- Working with images and local assets
- Using external icon and font libraries
- Managing spacing, sizing, and alignment
- Creating fixed and sticky UI elements
- Making a layout responsive
- Organizing a frontend project for GitHub

# Future Improvements
The current project is mainly a frontend UI. My next improvements would be to add JavaScript functionality and eventually connect it to a backend.

Some planned features are:

- Play and pause functionality
- Previous and next song controls
- Working progress bar
- Volume control
- Song selection
- Dynamic playlists
- Search functionality
- User login and registration
- Playlist creation
- Listening history

A future full-stack version could use:

HTML + CSS + JavaScript
          ↓
       FastAPI
          ↓
     PostgreSQL
          ↓
        REST API

# Project Goal
The main goal of this project was not to reproduce the complete Spotify application, but to understand how a modern music-player interface can be designed and structured using basic web technologies.

It is also a starting point for gradually moving from a static frontend project toward a functional full-stack application.

# Author
Gopi Krishna

Computer Science Engineering | Data Science

Interested in:
- Python
- SQL
- Web Development
- FastAPI
- MERN Stack
- Data Science



License
This project is available for educational and portfolio purposes under the MIT License.