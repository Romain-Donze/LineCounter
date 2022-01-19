# LineCounter
A simple command to count lines recursivly in a project

### Count lines in a QtQuick project
```console
find . -name '*.cpp' -or -name '*.h' -or -name '*.qml' | xargs wc -l
```
The output result can also be sorted:
```console
find . -name '*.cpp' -or -name '*.h' -or -name '*.qml' | xargs wc -l | sort -n
```

### Count lines in other type of prject
Just replace file extensions with what you need
```console
find . -name '*.py' | xargs wc -l
```
