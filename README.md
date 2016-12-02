# Php deprecation detector docker image

Image used for running deprecation-detector on our ci server

## Build command

    docker build -t ekreative/deprecation-detector .

## Build an app

    docker run -ti --rm --volume=$(pwd):/srv -w /srv ekreative/deprecation-detector
