# Flask Movie Recommender

Movie Recommender System is a web application that allows users to get movie recommendations based on their preferences. Users can search for movies, get detailed information, and receive recommendations for similar movies.

## Features

- User authentication (sign up, log in, log out)
- Movie search functionality
- Display detailed movie information
- Recommend similar movies
- Responsive design

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/flask-movie-recommender.git
    cd flask-movie-recommender
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables. Create a `.env` file in the root directory of the project and add the following:

    ```env
    FLASK_APP=app.py
    FLASK_ENV=development
    SECRET_KEY=your_secret_key
    ```

5. Run the application:

    ```bash
    flask run
    ```

6. Open your browser and go to `http://127.0.0.1:5000`.

## Usage

- **Home Page:** Browse the homepage to see featured movies.
- **Search:** Use the search bar to find movies by name.
- **Details:** Click on a movie to see detailed information.
- **Recommendations:** Get recommendations for similar movies based on your preferences.
- **User Account:** Sign up and log in to save your preferences and recommendations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a new Pull Request.

## Author

- **Manjundhar Adagiri** - *Initial work* - [Manjundhar](https://github.com/Manju025)
- **LinkedIn Account** - [Adagiri-Manjundhar](https://www.linkedin.com/in/manjundhar-adagiri)
## Acknowledgments

- Inspiration from various movie recommendation systems.
- Thanks to the Flask community for their extensive documentation and support.

