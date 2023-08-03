# Hot Dog Classifier

**Note: The original example might not work due to CORS restrictions when running it locally. This forked version provides a workaround to resolve this issue.**

This project demonstrates a simple Hot Dog Classifier using a pre-trained neural network model and web-based interface. It is a fork of the original repository [mastering-js/not-hot-dog](https://github.com/mastering-js/not-hot-dog), and all credits go to the [mastering-js](https://github.com/mastering-js) organization.

## How to Use

1. Clone this forked repository to your local machine.
2. Navigate to the project directory in your terminal or command prompt.

### Setup

Make sure you have Node.js installed on your machine. If you don't have it, download and install it from https://nodejs.org/

### Starting the Web Server

1. Install the `http-server` package globally using npm. This package will serve your files as a local web server.

    ```
    npm install -g http-server
    ```

2. Start the local web server:

    ```
    http-server
    ```

3. Open your web browser and navigate to `http://localhost:8080` to access the Hot Dog Classifier.

### How It Works

The Hot Dog Classifier allows you to select an image file from your computer and click the "Run" button to classify it as either a hot dog or not a hot dog.

The classifier uses a pre-trained neural network model for image embedding, which is loaded using the "brain.js" library. The training data consists of sample images of hot dogs and not hot dogs. The model runs on the embeddings of the selected image and predicts the classification.

### Training Data

The training data for the Hot Dog Classifier is included in the project:

-   Hot Dog Images: `./data/hot-dog/`
-   Not Hot Dog Images: `./data/not-hot-dog/`

## Credits

This project is based on the work of [mastering-js](https://github.com/mastering-js). Thank you for sharing this awesome project with the community! 🌭🔥
