1. **What goal will your website be designed to achieve?**  
   We’re building an app that will allow a user to experience possible music tastes of different famous people through various eras.

2. **What kind of users will visit your site? In other words, what is the demographic of your users?**  
   Music enthusiasts, history and culture enthusiasts, educational and academic communities, creative professionals.

3. **What data do you plan on using?**  
   Here are the possible API's: 
   - [Spotify Web API](https://developer.spotify.com/documentation/web-api)
   - [Last.fm API](https://www.last.fm/api)
   - [Deezer API](https://developers.deezer.com/login?redirect=/api)

4. **In brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). Answer questions like the ones below, but feel free to add more information:**

   a. **What does your database schema look like?**
   - **FamousPerson:**
     - PersonID (Primary Key)
     - Name
     - Years of living
     - Profession
     - If played/plays any musical instrument
   - **MusicTracksData:**
     - PersonID (Foreign Key)
     - Track ID (Primary Key)
     - Track name
     - (other info about the track, needs to be checked in API)

   b. **What kinds of issues might you run into with your API?**
   - API downtime or unavailability
   - Rate limits and quotas
   - Latency and performance issues
   - Updates or changes in API's structure
   - Incomplete or inconsistent data
   - Limited data coverage
   - Security and authentication challenges (API keys, tokens, or other security measures)
   - Cost concerns (in case of heavy usage)
   - Lack of documentation or support

   c. **Is there any sensitive information you need to secure?**
   - No, unless I decide to add a UI which will allow the user to create their profile.

   d. **What functionality will your app include?**
   - Character selection
   - Dynamic data fetching
   - Display music information and information about the character
   - API integration
   - Real-time interaction
   - Music playback

   e. **What will the user flow look like?**
   - Home page with the 'play' button (User visits the home page that invites them to start the game).
   - Character page (User chooses the character, click on it, and this leads to the song page).
   - Song page (User is taken to the page with the information about this song, the character and the music playback button).

   f. **What features make your site more than CRUD? Do you have any stretch goals?**
   - User profiles and history, user authentication: allow users to create profiles, save favorite personalities, and view their browsing history, providing a personalized experience.
   - Interactive educational content: integrate interactive educational content, quizzes, or trivia related to the chosen famous personalities, their contributions, and the era they lived in.
   - Social sharing and integration: enable users to share music or interesting information about the famous personalities on social media platforms, promoting user engagement and app visibility.
   - Multi-language support: provide multi-language support to make the app accessible to a wider audience and enhance its inclusivity.
   - Integration with music streaming services: integrate with popular music streaming services, allowing users to add the song associated with a famous personality to their playlist.
   - Music playlists and customization: allow users to create and customize playlists based on their favorite famous personalities and associated music.
   - Location-based features: incorporate features that provide information about famous personalities from a user's specific location or region, making the app more locally relevant.
   - Integration with historical events: link famous personalities to significant historical events, providing a broader context and understanding of their impact.
   - Accessibility features: incorporate accessibility features such as screen reader support, high contrast modes, and text resizing for users with different abilities.
