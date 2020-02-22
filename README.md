# scala-util

A collection of helpful classes for Scala development

# To install locally (to resolve dependencies)
1. Download scala-util source
```
git clone https://github.com/bigwheels16/scala-util.git
cd scala-util/
```

2. Build and Install (run this from the scala-util directory)
```
docker run -it --rm --name scala-util-build -v ~/.m2:/root/.m2 -v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven maven:3.6.3-jdk-11-slim mvn -e clean install
```
