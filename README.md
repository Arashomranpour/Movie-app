<div align="center">

# 🎬 Entertainment Hub

**A React + Material-UI app to discover trending movies and TV series, filter by genre, search and watch trailers - powered by TMDB.**

![React](https://img.shields.io/badge/React-17-61DAFB?logo=react&logoColor=black)
![Material UI](https://img.shields.io/badge/Material--UI-v4-007FFF?logo=mui&logoColor=white)
![TMDB](https://img.shields.io/badge/TMDB-API-01B4E4)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

</div>

---

> 📚 Built while following a YouTube course, then adapted and extended.

## ✨ Features

- 🔥 **Trending** - this week's trending movies and series.
- 🎞️ **Movies** and 📺 **Series** pages with **genre filters** and **pagination**.
- 🔍 **Search** across movies and TV shows.
- 🪟 **Detail modal** - description, cast carousel and a one-click **trailer on YouTube**.
- 📱 Responsive layout with a bottom navigation bar (Material-UI).

## 🚀 Getting Started

### Prerequisites

- Node.js 14+ and npm
- A free [TMDB API key](https://www.themoviedb.org/settings/api)

### Install & run

```bash
git clone https://github.com/Arashomranpour/Movie-app.git
cd Movie-app
npm install
```

Create a `.env` file in the project root:

```env
REACT_APP_API_KEY=your_tmdb_api_key
```

```bash
npm start       # http://localhost:3000
npm run build   # production build
```

## 🔗 Routes

| Route | Page |
|---|---|
| `/` | Trending |
| `/movies` | Movies by genre |
| `/series` | TV series by genre |
| `/search` | Search |

## 📁 Project Structure

```
src/
├── App.js
├── Pages/            # Trending, Movies, Series, Search
├── components/       # Carousel, ContentModal, Genres, Header, MainNav, Pagination, SingleContent
└── config/config.js  # Image sizes, placeholders
```

## 🛠️ Tech Stack

`React` · `React Router` · `Material-UI` · `Axios` · `react-alice-carousel` · `TMDB API`
