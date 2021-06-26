# youtube-dl docker-compose wrapper

Docker-compose wrapper for running [youtube-dl](https://github.com/ytdl-org/youtube-dl) without having to install it. Based on [wernight/youtube-dl](https://hub.docker.com/r/wernight/youtube-dl).

Example usage: `docker-compose run extract-audio https://www.youtube.com/watch?v=dQw4w9WgXcQ`

## Contributing

If you think about other commands that could be added, please make them runnable as services with this format (minimal arguments): `docker-compose run <service-name> $YOUTUBE_URL`.
