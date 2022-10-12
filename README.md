# valgrind-check

## This is a simple valgrind exercise repository

Please see initial_valgrind_output.txt for valgrind output which was executed with the errors in the program.  

Please see final_valgrind_output.txt for valgrind output executed after the bugs were fixed.  

Please see K.png for visualization of the program.  


## Standard install via command-line
```
git clone --recursive https://github.com/dpiet/cpp-boilerplate
cd <path to repository>
mkdir build
cd build
cmake ..
make
Run tests: ./test/cpp-test
Run program: ./app/shell-app
```

## Building for code coverage (for assignments beginning in Week 4)
```
sudo apt-get install lcov
cmake -D COVERAGE=ON -D CMAKE_BUILD_TYPE=Debug ../
make
make code_coverage
```
This generates a index.html page in the build/coverage sub-directory that can be viewed locally in a web browser.
