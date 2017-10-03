# Valgrind Exercise
To install and compile the repository:
```
git clone --recursive https://github.com/MichiMaestre/Valgrind-exercise.git
cd <path to repository>
mkdir build
cd build
cmake ..
make
Run tests: ./test/cpp-test
Run program: ./app/shell-app
```


The Valgrind ouputs text files from before and after fixing the bugs are called: ```bugs_output.txt``` and ```bugs_output_fixed.txt``` respectively.

The screenshot of the memory profiler output is called ```KCacheGrind_screenshot.png```.
