
# React Native Task


This React Native mobile app displays information about movies from various categories using data fetched from different APIs. The app consists of two main pages: the home page and the "See All" page.



# Features
- **Home Page:**
   -   Divided into two sections: Main Movie (First Movie) and Remaining Movies.
    -   Main Movie section includes a poster, name, genres, and release year.
    -   Utilizes a provided example design for layout consistency.
- **"See All" Page:**
    -   Displays all movies in a grid layout.
    -   Implements infinite scroll functionality.
    -   Shows movie posters, titles, and genres for comprehensive browsing.



# Home Page UI
You can view the image by clicking [here](https://i.ibb.co/ws9bM13/TMA-TESt.png) or by copying and pasting the following URL into your browser's address 




# APIs Used

- **Movies API:**

    -   Retrieves all movies, with the first one serving as the main movie in the first section of the home page.
    -   Endpoint: <https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=6b4357c41d9c606e4d7ebe2f4a8850ea&page=1>

-   **Genres Lookup API:**

    -   Fetches the list of genres to use for each movie.
    -   Endpoint: <https://api.themoviedb.org/3/genre/movie/list?api_key=6b4357c41d9c606e4d7ebe2f4a8850ea>


# Static Images URL
```
https://image.tmdb.org/t/p/w370_and_h556_bestv2/POSTER_PATH

Example:
https://image.tmdb.org/t/p/w370_and_h556_bestv2/t6HIqrRAclMCA60NsSmeqe9RmNV.jpg
```



# Implementation Points

-   **API Integration & Data Handling:**
    -   Utilize robust API libraries (e.g., Axios) for efficient data fetching.
    -   Implement error handling and loading states to ensure a smooth user experience.
    -   Consider caching mechanisms for improved performance and offline access.
-   **Clean Code & Architecture:**
    -   Adhere to React Native best practices and coding standards for maintainability.
    -   Structure components modularly and leverage reusable functions/hooks.
    -   Employ TypeScript for type safety and enhanced development experience.
-   **User Interface & Design:**
    -   Implement the provided design faithfully while maintaining responsiveness.
    -   Utilize appropriate UI components and libraries (e.g., React Native Elements)
    -   Consider accessibility guidelines and cross-platform compatibility.
-   **Testing & Debugging:**
    -   Write comprehensive unit tests for components and API interactions.
    -   Utilize debugging tools (e.g., React Native Debugger) for efficient troubleshooting.
    -   Implement end-to-end tests for critical user flows.
-   **Performance & Optimization:**
    -   Implement lazy loading for large data sets to improve initial load times.
    -   Consider performance profiling tools to identify and address bottlenecks.



# Technical Question

**Question:** How would you optimize image loading and caching in the React Native Movie App to ensure efficient resource utilization and improved performance?