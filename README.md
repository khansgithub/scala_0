# scala_0

```
curl -fLo coursier https://github.com/coursier/launchers/raw/master/coursier &&
    chmod +x coursier &&
    ./coursier

./coursier setup
source ~/.bash_profile

// create new project
sbt new scala/scala3.g8

cd helloworld
sbt
//Type ~run. The ~ is optional and causes sbt to re-run on every file save, allowing for a fast edit/run/debug cycle. sbt will also generate a target directory which you can ignore.
~run
```
