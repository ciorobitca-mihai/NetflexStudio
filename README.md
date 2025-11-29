# Netflex Studio

**Netflex Studio** is a web platform for streaming movies and TV shows. Videos are hosted on [Videas.fr](https://videas.fr) for reliable streaming, while metadata like seasons, episodes, and parts are managed via **Supabase**. The live platform can be accessed at: [https://netflex-studio.vercel.app/](https://netflex-studio.vercel.app/)

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)

---

## Features

- Browse movies, TV series, seasons, episodes, and parts  
- Dynamic video playback with previous/next navigation  
- Supabase backend for storing media metadata  
- Videos hosted externally on **Videas.fr**  
- Asset mapping for featured content  
- Fully deployed at [https://netflex-studio.vercel.app/](https://netflex-studio.vercel.app/)

---

## Tech Stack

- **Backend:** Node.js, Express  
- **Database:** Supabase (PostgreSQL)  
- **Video Hosting:** Videas.fr  
- **Frontend:** EJS templates  
- **Caching:** apicache (optional)  
- **Environment Config:** dotenv  