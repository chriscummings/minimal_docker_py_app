# Absolute Minimal Docker Example

    cd <repo dir>
    docker built -t my-image .
    docker run -d -p 80:80 --name my-container my-image