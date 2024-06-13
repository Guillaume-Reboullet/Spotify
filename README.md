
# Spotify

## Introduction

Spotify is a web application that mimics the functionality of a music streaming service. It utilizes React for the frontend and interacts with an API to fetch data.

## Project Setup

**Requirements:**
- Node.js
- Docker

**Installation:**

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd spotify
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up the API using Docker:
    ```bash
    cd .. (be in the foler where there is docker-compose.yml)
    docker-compose up -d
    ```

4. Start the development server:
    ```bash
    npm start
    ```

## Features

- **Album Listing:** View a paginated list of all albums
- **Album Details:** View details of an album and play tracks
- **Genre Listing:** View a list of all music genres
- **Genre Details:** View albums under a specific genre
- **Artist Listing:** View a paginated list of artists
- **Artist Details:** View albums by a specific artist
- **Search:** Search for albums, genres, and artists
- **Homepage:** Display a random listing of albums
