# 🍿 usePopcorn

A React-based movie search and watchlist application that allows users to discover movies and create their personal watchlist with ratings.

## ✨ Features

- **Movie Search**: Search for movies using the OMDB API
- **Movie Details**: View detailed information about movies including plot, cast, director, and ratings
- **Personal Watchlist**: Add movies to your personal watchlist with custom ratings
- **Star Rating System**: Rate movies using an interactive star rating component
- **Local Storage**: Your watchlist persists between sessions
- **Responsive Design**: Clean, modern interface with dark theme
- **Keyboard Navigation**: Press Enter to focus search, Escape to close movie details

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd usepopcorn
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## 🎯 How to Use

1. **Search Movies**: Type in the search bar to find movies
2. **View Details**: Click on any movie to see detailed information
3. **Rate Movies**: Use the star rating system to rate movies (1-10 stars)
4. **Add to Watchlist**: Click "Add to List" after rating a movie
5. **Manage Watchlist**: View your watchlist summary with average ratings and runtime
6. **Remove Movies**: Click the X button to remove movies from your watchlist

## 🛠️ Built With

- **React** - Frontend framework
- **Custom Hooks** - For state management and side effects
- **OMDB API** - Movie data source
- **CSS3** - Styling and responsive design
- **Local Storage** - Data persistence

## 📁 Project Structure

```
src/
├── App.js              # Main application component
├── StarRating.js       # Star rating component
├── useMovies.js        # Custom hook for movie API calls
├── useLocalStorageState.js  # Custom hook for localStorage
├── useKey.js           # Custom hook for keyboard events
├── index.js            # React app entry point
└── index.css           # Global styles
```

## 🎨 Key Components

- **Movie Search**: Real-time search with debouncing
- **Movie List**: Displays search results with posters and basic info
- **Movie Details**: Comprehensive movie information view
- **Watchlist Summary**: Shows statistics about watched movies
- **Star Rating**: Interactive rating component with hover effects

## 🔧 Custom Hooks

- [`useMovies`](src/useMovies.js) - Handles movie API calls and loading states
- [`useLocalStorageState`](src/useLocalStorageState.js) - Manages localStorage state
- [`useKey`](src/useKey.js) - Handles keyboard event listeners

## 🌟 Features in Detail

### Smart Search
- Minimum 3 characters required
- Automatic loading states
- Error handling for API failures

### Persistent Watchlist
- Automatically saves to localStorage
- Tracks user ratings and viewing statistics
- Calculates average ratings and total runtime

### Keyboard Shortcuts
- **Enter**: Focus search input
- **Escape**: Close movie details

## 📱 Responsive Design

The app is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile devices

## 🚀 Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (one-way operation)

## 🎬 API

This project uses the [OMDB API](http://www.omdbapi.com/) to fetch movie data. The API provides:
- Movie search functionality
- Detailed movie information
- Poster images
- Ratings from various sources

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- [OMDB API](http://www.omdbapi.com/) for providing movie data
- Create React App for the initial project setup
- React community for excellent documentation and resources