# 🎮 FilmVerse

**FilmVerse** is a full-featured movie and TV show database explorer. Dive into film metadata, search, filter, and discover new titles through a sleek, intuitive interface powered by modern technologies.

## 🚀 Features

- 📊 **Detailed Info** – See ratings, release dates, plot summaries, cast & crew.
- ⭐ **Personal Rating/Review** – Log your own ratings.
- 🎥 **Watchlist Management** – Add to, remove from, and view your watchlist.
- 🎨 **Responsive UI** – Works great on desktop, tablet, and mobile.
- 🌐 **Rich API Integration** – Uses TMDb API for up-to-date film data.

## 🛠️ Technologies

- **Backend**: Node.js + Express
- **Database**: MongoDB
- **Frontend**: React.js
- **API**: TMDb
- **Deployment**: Vercel

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/MathewX470/FilmVerseDB.git
cd FilmVerseDB
```

### 2. Configure environment variables

Create a `.env` file in both `backend/` and `frontend/` directories with the necessary keys:

```dotenv
# backend/.env
TMDB_API_KEY=your_tmdb_key
DB_URL=your_database_url
JWT_SECRET=your_jwt_secret
```

### 3. Run in development mode

```bash
# Start the backend server
cd backend
npm run dev

# In a new terminal, start the frontend server
cd frontend
npm start
```

### 4. Access the app

## ⚙️ Usage

- Browse popular films on the homepage
- Use the search bar—try typing “Inception (2010)”
- Click any title to view details, cast, reviews
- Login/signup to add to watchlist, or write reviews


⭐ *By MathewX470.*
