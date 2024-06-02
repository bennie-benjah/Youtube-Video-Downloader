# YouTube Video Downloader

A Flask application to download YouTube videos as MP4 files with real-time progress updates.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
This project allows users to download YouTube videos by providing a link. The download progress is displayed in real-time using Flask-SocketIO.

## Features
- Download YouTube videos as MP4.
- Real-time progress updates.
- Simple and intuitive user interface.
- Uses Flask and SocketIO for real-time communication.

## Installation
To run this application locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/youtube-video-downloader.git
    cd youtube-video-downloader
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```
NOTE: Step 2 is not a mandatory
3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set the Flask secret key:**
    ```bash
    export FLASK_SECRET_KEY='your_secret_key'  # On Windows use `set FLASK_SECRET_KEY=your_secret_key`
    ```

5. **Run the application:**
    ```bash
    flask run
    ```

## Usage
1. Open your web browser and navigate to `http://127.0.0.1:5001`.
2. Enter the YouTube video URL in the provided input field and submit.
3. The download will start and you will see real-time progress updates.

## Technologies Used
- **Python**
- **Flask**
- **Flask-SocketIO**
- **yt-dlp**
- **HTML**
- **CSS (Bootstrap)**

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
If you have any questions or suggestions, feel free to reach out:

- GitHub: [bennie-benjah](https://github.com/bennie-benjah)
- Email: mutisob78@gmail.com
