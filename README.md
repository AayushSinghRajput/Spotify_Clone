# Spotify Clone

A modern web application that replicates core functionality of Spotify, built with React and Tailwind CSS.

![Spotify Clone](src/assets/spotify_logo.png)

## Features

- 🎵 Music player with play, pause, next, and previous controls
- 🔍 Browse featured albums and songs
- 🎧 Real-time audio playback
- 📱 Responsive design for various screen sizes
- 📑 Queue management for songs
- 🎚️ Volume control
- 🔄 Looping and shuffle functionality

## Tech Stack

- **Frontend Framework**: React (v18.3.1)
- **Routing**: React Router DOM (v7.1.3)
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Code Quality**: ESLint

## Screenshots

The application includes:
- Home view with featured albums and today's biggest hits
- Album view displaying songs in an album
- Music player with playback controls
- Responsive sidebar for navigation

## Project Structure

```
src/
├── assets/          # Images, icons, and song files
├── components/      # React components
│   ├── AlbumItem.jsx       # Album display component
│   ├── Display.jsx         # Main content display area
│   ├── DisplayAlbum.jsx    # Album view component
│   ├── DisplayHome.jsx     # Home view component
│   ├── Navbar.jsx          # Navigation component
│   ├── Player.jsx          # Music player component
│   ├── Sidebar.jsx         # Side navigation component
│   └── SongItem.jsx        # Song display component
├── context/         # React context for state management
│   └── PlayerContext.jsx   # Music player state and controls
├── App.jsx          # Main application component
├── index.css        # Global styles
└── main.jsx         # Application entry point
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AayushSinghRajput/Spotify_Clone.git
   cd Spotify_Clone
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

## Usage

- Click on albums to view their songs
- Use the player controls at the bottom to control music playback
- Navigate through different sections using the sidebar
- Search for songs using the search bar in the navbar

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Spotify](https://www.spotify.com/) for design inspiration
- [React](https://reactjs.org/) for the UI library
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Vite](https://vitejs.dev/) for the build tool
