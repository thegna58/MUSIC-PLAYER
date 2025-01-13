# MUSIC-PLAYER
Music Player Program
Overview
This command-line music player program allows users to manage a virtual music library, create playlists, and play songs. It is written in C and supports basic functionalities to interact with songs, playlists, and song details.

Features
Create Songs: Users can add new songs to the music library by providing details such as title, album, year, duration, ID, and URI.
Playlist Management: Create, modify, and delete playlists.
Navigation: Navigate through playlists, play next/previous tracks, and view detailed song information.
CSV Data Import: Import songs from a CSV file (rawdata.csv) to populate the initial song pool.
Usage
Run the compiled executable (music_player).
Follow the on-screen instructions and use the numeric menu options to navigate and perform actions.
For adding songs manually, follow the prompts to input song details.
Use the CSV import feature by placing a rawdata.csv file with song details in the root directory.
File Structure
main.c: Contains the main code for the music player.
rawdata.csv: CSV file containing song details used for initial song pool loading.
