**YouTube Video Downloader using Pytube and Tkinter**

This Python script utilizes the Pytube library and Tkinter GUI toolkit to create a simple YouTube video downloader. Users can input a YouTube video URL, choose a download location through a file dialog, and download the video in the highest resolution available as an MP4 file.

**Instructions:**

1. **Installation:**
   - Ensure you have Python installed on your system.
   - Install the required libraries by running `pip install pytube3` in your terminal or command prompt.

2. **Usage:**
   - Run the script in a Python environment.
   - Enter a valid YouTube video URL when prompted.
   - Choose a location to save the downloaded video using the file dialog that appears.
   - The video will be downloaded to the specified location in the highest available resolution.

3. **Code Overview:**
   - The script imports the necessary modules: Pytube for YouTube video handling and Tkinter for the GUI.
   - It defines a function `download_video` that takes a YouTube video URL and a download path as input and downloads the video in the highest resolution available as an MP4 file.
   - Another function `open_file_dialog` is used to open a file dialog for selecting the download location.
   - The main part of the script prompts the user for a video URL, opens the file dialog to choose a download location, and then initiates the download process.

4. **Dependencies:**
   - Python 3.x
   - Pytube library (`pip install pytube3`)
   - Tkinter library (usually comes pre-installed with Python)

5. **Note:**
   - Ensure the entered YouTube video URL is valid and accessible.
   - Make sure to choose a valid download location using the file dialog.
   - The script currently supports downloading MP4 format videos in the highest resolution.

Feel free to modify and enhance the script as per your requirements, such as adding error handling, supporting additional video formats, or improving the user interface. Enjoy downloading YouTube videos with ease using this Python script!
