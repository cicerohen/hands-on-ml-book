# Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow

This repository contains my personal notes and Jupyter notebooks as I work through the book **"Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow"** by Aurélien Géron.

## Project Structure

- `hands_on_chapter_2.ipynb`: End-to-End Machine Learning Project
- `hands_on_chapter_3.ipynb`: Classification
- `docker-compose.yaml`: Docker configuration for running the Jupyter environment

## Getting Started

This project uses Docker to ensure a consistent environment with all necessary dependencies installed.

### Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Running the Notebooks

1. Clone the repository (if you haven't already):

   ```bash
   git clone <repository-url>
   cd hands-on-ml-book
   ```

2. Start the Jupyter Lab server:

   ```bash
   docker-compose up
   ```

3. Look for the URL in the terminal output. It will look something like this:

   ```
   http://127.0.0.1:8888/lab?token=<your-token>
   ```

4. Open that URL in your web browser to access the notebooks.

## Usage

The notebooks are located in the `work` directory within the Jupyter Lab interface (due to the volume mount config). You can open `hands_on_chapter_2.ipynb` or `hands_on_chapter_3.ipynb` to see the code and experiments.

## License

This project is for educational purposes.
