# Flask Chat Application

This is a simple chat application built with Flask and Flask-SocketIO, allowing users to create or join chat rooms and communicate in real-time.

## Features

- **Room Creation:** Users can create new chat rooms with unique codes.
- **Joining Rooms:** Users can join existing chat rooms using room codes.
- **Real-time Messaging:** Communication between users within a room happens in real-time.
- **User Management:** The application tracks the number of users in each room and displays their activity.

## Requirements

- Python 3.x
- Flask
- Flask-SocketIO

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/flask-chat-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd flask-chat-app
    ```

3. Install dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://localhost:5000` to access the application.

3. Enter your name and either join an existing room by providing its code or create a new room.

4. Start chatting with other users in the room!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by [Flask-SocketIO](https://flask-socketio.readthedocs.io/en/latest/) documentation and examples.
