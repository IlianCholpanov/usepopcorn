# FilmFrenzy

A React project focused on components, composition, and custom hooks for searching and rating movies.

## Features

- Search movies using the OMDb API
- View movie details and IMDb ratings
- Rate movies with a customizable star rating component
- Track and manage your watched movies list (with local storage persistence)
- Responsive and modern UI

## Getting Started

### Prerequisites

- Node.js (v14 or newer)
- npm

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/07-usepopcorn.git
   cd 07-usepopcorn
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the App

Start the development server:

```sh
npm start
```

The app will be available at [http://localhost:3000](http://localhost:3000).

### Building for Production

```sh
npm run build
```

## Project Structure

```
07-usepopcorn/
├── public/
│   └── index.html
├── src/
│   ├── App.js                   # Main application component (contains all UI logic)
│   ├── App-v1.js                # Initial version for reference
│   ├── StarRating.js            # Reusable star rating component
│   ├── useMovies.js             # Custom hook for fetching movies
│   ├── useLocalStorageState.js  # Custom hook for localStorage state
│   ├── useKey.js                # Custom hook for keyboard events
│   ├── index.js                 # Entry point
│   └── index.css                # Styles
├── package.json
└── README.md
```

## Custom Hooks

- `useMovies`: Fetches movies from OMDb API based on search query.
- `useLocalStorageState`: Persists state to localStorage.
- `useKey`: Handles keyboard shortcuts.

## License

MIT
