## Docker image: Ubuntu 16.04 + IntelliJ Idea 2016.1.3

What's inside:
- Ubuntu 16.04
- Open JDK 8
- Git
- IntelliJ Idea 2016.1.3

## Why

By using this container you can try IntelliJ Idea without cluttering your system.  Here is how you can run it in a disposable container:

```
docker run --rm -it --net host -v "$HOME/.Xauthority:/root/.Xauthority:rw" -v $(pwd):/project --env=DISPLAY gtrafimenkov/ubuntu1604-intellij-idea
```

## How to get

`docker pull gtrafimenkov/ubuntu1605-intellij-idea`

## License

MIT
