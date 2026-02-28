<div align="center">
  <img src="https://raw.githubusercontent.com/kalviumcommunity/S66_AbdulRahman_Capstone_GenreFilter/main/frontend/public/WhatsApp_Image_2025-06-27_at_10.41.04_AM-removebg-preview.png" alt="Spopify Logo" width="120" />
  <h1>Spopify - Advanced Spotify Playlist Manager</h1>
  <p><strong>Filter your Spotify playlists by genre, remove duplicates, and create new AI-named mixes with ease!</strong></p>

  [![Visit Spopify](https://img.shields.io/badge/Visit_Website-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://spopifyy.vercel.app)
</div>

<br />

## 🎵 Overview
**Spopify** is a full-stack web application designed to supercharge your Spotify experience! Ever wanted to extract just the *House* or *R&B* tracks from your massive 500-song liked playlist? Spopify makes it happen. 

By integrating with the official Spotify API and the Last.fm API, Spopify intelligently detects the genres of your tracks. It allows you to filter your existing playlists, weed out annoying duplicate songs, create brand-new customized playlists directly to your Spotify account, and even uses AI to generate creative playlist names for your newly curated mixes!

---

## ✨ Key Features
- **Spotify Authentication**: Secure login using Spotify OAuth.
- **Advanced Genre Filtering**: Intelligently filter playlist tracks based on genres detected from Spotify artists, cross-referenced with Last.fm's expansive tagging system.
- **Custom Genre Tagging**: Add or remove your own custom genres for individual tracks via a sleek modal interface—your tags are saved!
- **Playlist Deduplication**: Automatically identify and cleanly remove duplicate songs from your messy playlists with one click.
- **Playlist Creation**: Generate new playlists from your filtered songs directly into your Spotify account.
- **AI-Powered Suggestions**: Uses LangChain.js & Google Gemini to suggest creative, fun playlist names based on the genres you selected.
- **Modern Responsive UI**: Built with React and strictly styled using Tailwind CSS for a premium, dark-mode-first glowing design aesthetic.

## Technologies
- **Frontend**: React, React-Select, Tailwind CSS, InfiniteLoader, ClipLoader
- **Backend**: Node.js, Express, Mongoose (MongoDB)
- **APIs**: Spotify API, Last.fm API
- **AI**: LangChain.js with Cohere
- **Security**: Helmet, Rate Limiting (express-rate-limit)
- **Containerization**: Docker
- **Deployment**: Planned on Render (backend) and Vercel (frontend)

## Prerequisites
- Node.js (v18.x or later)
- MongoDB Atlas account (free tier)
- Spotify Developer Account (for API credentials)
- Last.fm API Key
- Cohere API Key (for AI suggestions)

## Installation

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/kalviumcommunity/S66_AbdulRahman_Capstone_GenreFilter
   cd backend