# Movie Genre Flutter App

This Flutter app is designed to display information about movies by genre. The splash screen of the app features three horizontal-scrolling lists arranged in a column, each representing a different movie genre. Each list includes a header banner indicating the genre and at least four items (movies) in the list's body. The header remains visible as the list is scrolled horizontally.

## Features

- **Splash Screen:**
  - Displays three horizontal-scrolling lists, each representing a movie genre.
  - Header banners indicate the genre of each list.

- **List Items:**
  - Each list item includes a thumbnail picture of the movie poster.
  - Two one-line text strings with different font sizes:
    - Larger font (top) displays the name of the movie.
    - Smaller font (bottom) contains the names of one or two actors starring in the movie.

- **Scrolling:**
  - Initially shows one or two movies across the display.
  - Users can scroll the list horizontally to view additional movies.
  - The display of lists not being scrolled remains unchanged.

- **Click Actions:**
  - Short Click:
    - Opens a new screen with the entire picture of the selected movie.
    - Users can return to the list screen using the back soft button in the toolbar.
  - Long Click:
    - Opens a browser screen showing the IMDb website for the selected movie when clicking anywhere on the displayed picture.

## Implementation Notes

- Utilizes Flutter's ListView and ListTile widgets for the horizontal-scrolling lists.
- The header of the list remains fixed while scrolling.
- Implements navigation to a new screen for short clicks to display the entire picture of the selected movie.
- Implements opening the IMDb website in the browser for long clicks on the displayed picture.

## Getting Started

1. Clone the repository.

2. Open the project in your preferred Flutter IDE.

3. Run the app on your emulator or physical device.

## Note

Ensure that the necessary dependencies are installed using `flutter pub get` before running the app.

Feel free to extend the functionality or customize the app as needed for your specific use case.
