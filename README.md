# tensorflow-proj-template
* How to build
```
docker build -f proj.dockerfile -t myproj .
```

* How to run
```
docker run -it --rm -p 8899:8888 -v $(pwd):/home/jovyan/work myproj
```

* Access to `http://127.0.0.1:8899`

# TODO
* work folder
* access to data folder

