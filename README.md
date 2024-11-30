---

# Movie Watchlist - Oracle Apex Application

## Overview

The **Movie Watchlist** is an Oracle Apex application designed to help users manage and organize movies they wish to watch. Leveraging the TMDb API, the application provides a seamless experience for discovering and tracking movies. 

This project was developed as a learning exercise to better understand Oracle Apex, the platform used by my university for hosting its systems. It also serves as a foundation for my work with the local honors college to revitalize their websites using Oracle Apex.

---

## Features

- **Add Movies:** Search for movies using TMDb API and add them to your watchlist or mark them as already watched.  
- **Filter by Length:** Filter movies based on their runtime for easy planning.  
- **Search Functionality:** Quickly find movies using the integrated search feature.  
- **Track Progress:** Manage your watchlist and keep track of watched movies.  
- **Planned Enhancements:**  
  - Rate movies after watching them.  
  - Leave personal comments or notes on each movie.

---

## Tech Stack

- **Frontend:** Oracle Apex (Interactive Grids, Reports, and Forms)  
- **Backend:** Oracle Database (PL/SQL for custom logic)  
- **API Integration:** TMDb API for movie data  
- **Hosting Platform:** Oracle Apex Workspace provided by the university  

---

## Installation and Setup

1. **Import the Application**  
   - Download the application export file (`movie_watchlist.sql`).  
   - Log in to your Oracle Apex workspace.  
   - Navigate to **App Builder > Import** and upload the file.  

2. **Set Up Database Tables**  
   - Run the `schema_setup.sql` file provided to create necessary tables and sample data.  

3. **Configure TMDb API**  
   - Obtain an API key from TMDb ([link](https://www.themoviedb.org/settings/api)) and update the application’s API integration settings.  

4. **Deploy**  
   - Deploy the application in your Oracle Apex workspace for personal use or share it with others.  

---

## Usage

1. Launch the application from your Oracle Apex dashboard.  
2. Use the **Search** feature to find movies via TMDb API.  
3. Add movies to your watchlist or mark them as watched.  
4. Filter movies by runtime or search your library.  
5. Explore planned features like ratings and comments as they are added.

---

## Learning Outcomes

This project provided valuable experience with:  
- Integrating third-party APIs (TMDb) into Oracle Apex applications.  
- Designing user-friendly forms, reports, and filters.  
- Developing interactive features using Oracle Apex and PL/SQL.  
- Managing application deployment in a professional environment.  

---

## Future Enhancements

- Enable users to rate movies.  
- Add a comments/notes section for personal movie reviews.  
- Improve the UI/UX with custom themes and advanced visualizations.  

---

## Contact

If you have any questions or suggestions about this project, feel free to reach out!  

--- 
