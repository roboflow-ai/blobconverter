# BlobConverter

## Usage

- Docker-Compose

    ```
    docker-compose build
    docker-compose up
    ```

- Docker

    ```
    docker build -t blobconverter .
    docker run -p 5000:5000 blobconverter
    ```

- System - python 3.5 or higher required

    ```
    pip install -r requirements.txt
    python main.py
    ```

## TODO

- remove uploaded files after conversion (to prevent disk space consumption)
