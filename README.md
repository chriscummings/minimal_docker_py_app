# Absolute Minimal Docker Example

    cd <repo dir>
    docker build -t my-image .
    docker run -d -p 80:80 --name my-container my-image
