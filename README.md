# smlox
Standard ML implementation of jlox

## Environment

### Build

```
docker build -t polyml .
```

### Run

```
docker run -v $(pwd):/var/opt/project -it polyml
cd /var/opt/project/
polyc -o target/smlox src/bundle.sml
./a.out
```
