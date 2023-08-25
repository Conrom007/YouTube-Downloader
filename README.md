# YouTube-Downloader
Youtube Downloader using the pytube library
# Motivation
This notebook was made to serve as a convenient medium to use pytube in order to download videos. 
# Features
* Added logic when running the function that differentiates between single videos and playlists.
* Added support for authentication to handle age-restricted content.
* The initial setup is performed by running each code block in sequential order. This ensures that a bug that prevents the age-authorisation from working is fixed (this only needs to be performed the first time it's ran after a complete runtime deletion)
* The videos are saved directly in your Google Drive storage.
* Along with the videos a log file is created for each playlist that stores each video successfully downloaded from it. This allows it to skip the videos it has already downloaded if the downloader is stopped and restarted for any reason.

# Dependencies 
* ALL the dependencies are handled in the first code block the only requirement is that you use the Google Colab environment for the seamless Google Drive integration.
