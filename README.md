MusicStream

MusicStream is a web-based music streaming application built using Next.js and Tailwind CSS. It allows users to explore millions of songs, discover trending tracks, and play music directly in the browser. The app is responsive, works on both desktop and mobile, and comes with a modern dark-themed UI.

Live Demo

You can view the live version of the app here:
MusicStream Live on Vercel https://music-streaming-api-next.vercel.app/

Project Objectives

- Provide a modern and intuitive platform for music streaming.  
- Showcase featured and trending songs to users.  
- Allow users to explore more songs with an easy refresh option.  
- Include a built-in music player for playback.  
- Ensure a responsive and user-friendly interface across devices.

Features

Here’s what you can do with MusicStream:
-Featured Music – Highlights top songs with album art, title, and artist name.
-Trending Songs – Shows the most popular songs currently.
-Discover More – Explore additional songs with a refresh option to load new tracks.
-Music Player – Built-in player with play, pause, and track switching.
-Responsive Design – Works smoothly on mobile, tablet, and desktop.
-Dark Theme – Modern, eye-friendly dark mode applied globally.
-Dynamic Data Fetching – Fetches songs from the backend with loading and error handling.

Technologies Used

-Next.js 14.x – React framework for server-side rendering, routing, and building scalable web apps.
-React 18.x – Core library for building interactive user interfaces.
-Tailwind CSS – Utility-first CSS framework for fast and responsive styling.
-Axios – Library to fetch data from the backend API.
-React Icons – Provides icons for UI components like music notes and trending symbols.


Installation & Setup

1.Clone the repository

 git clone https://github.com/Nahfer/music-streaming-frontend

2.Go to the project folder

  cd music-stream

3.Install dependencies
 
npm install

4.Add environment variables (if needed)

Create a .env.local file in the root folder:
   NEXT_PUBLIC_API_URL=https://music-streaming-api-next.vercel.app/

5.Run the project

npm run dev

6.Open in browser
 Go to http://localhost:3000 to see the app.

Project Structure

/app           → Next.js pages (Home, Discover, Artist pages)
/components    → Reusable UI components (Player, CreatePlaylist, etc.)
/services      → API helper functions for fetching songs
/public        → Static assets (images, icons)
/styles        → Tailwind CSS and custom styles



Team Members & Contributions

- Tihitna Ejigu – Frontend Development: Built UI, implemented pages, integrated music player, and styled the app with Tailwind CSS.  
- Nahom Derege – Backend Development: Built API endpoints, managed the database, and handled song data fetching.

Additional Notes

Known Issues:  
- Some songs may not load if the backend API is unavailable.  
- Minor layout issues may appear on very small mobile screens.  

Future Enhancements:  
- Add search functionality for songs and artists.  
- Enable playlist creation and management.  
- Allow users to mark favorite songs and create personalized playlists.

