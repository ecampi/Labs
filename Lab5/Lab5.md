## Step 4:

### Output of ctest -W:

UpdateCTestConfiguration  from :/mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/DartConfiguration.tcl
UpdateCTestConfiguration  from :/mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/DartConfiguration.tcl
Test project /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build
Constructing a list of tests
Done constructing a list of tests
Updating test list for fixtures
Added 0 tests to meet fixture requirements
Checking test dependency graph...
Checking test dependency graph end
test 1
    Start 1: Runs

1: Test command: /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/Tutorial "25"
1: Test timeout computed to be: 9.99988e+06
1: Computing sqrt of 25 to be 13
1: Computing sqrt of 25 to be 7.46154
1: Computing sqrt of 25 to be 5.40603
1: Computing sqrt of 25 to be 5.01525
1: Computing sqrt of 25 to be 5.00002
1: Computing sqrt of 25 to be 5
1: Computing sqrt of 25 to be 5
1: Computing sqrt of 25 to be 5
1: Computing sqrt of 25 to be 5
1: Computing sqrt of 25 to be 5
1: The square root of 25 is 5
1/5 Test #1: Runs .............................   Passed    0.02 sec
test 2
    Start 2: Usage

2: Test command: /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/Tutorial
2: Test timeout computed to be: 9.99988e+06
2: /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/Tutorial Version 1.0
2: Usage: /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/Tutorial number
2/5 Test #2: Usage ............................   Passed    0.01 sec
test 3
    Start 3: Comp25

3: Test command: /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/Tutorial "25"
3: Test timeout computed to be: 9.99988e+06
3: Computing sqrt of 25 to be 13
3: Computing sqrt of 25 to be 7.46154
3: Computing sqrt of 25 to be 5.40603
3: Computing sqrt of 25 to be 5.01525
3: Computing sqrt of 25 to be 5.00002
3: Computing sqrt of 25 to be 5
3: Computing sqrt of 25 to be 5
3: Computing sqrt of 25 to be 5
3: Computing sqrt of 25 to be 5
3: Computing sqrt of 25 to be 5
3: The square root of 25 is 5
3/5 Test #3: Comp25 ...........................   Passed    0.02 sec
test 4
    Start 4: Comp-25

4: Test command: /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/Tutorial "-25"
4: Test timeout computed to be: 9.99988e+06
4: The square root of -25 is 0
4/5 Test #4: Comp-25 ..........................   Passed    0.01 sec
test 5
    Start 5: Comp0.0001

5: Test command: /mnt/c/Users/campae/Dropbox/OSS/cmake/Tests/Tutorial/Step4/build/Tutorial "0.0001"
5: Test timeout computed to be: 9.99988e+06
5: Computing sqrt of 0.0001 to be 0.50005
5: Computing sqrt of 0.0001 to be 0.250125
5: Computing sqrt of 0.0001 to be 0.125262
5: Computing sqrt of 0.0001 to be 0.0630304
5: Computing sqrt of 0.0001 to be 0.0323084
5: Computing sqrt of 0.0001 to be 0.0177018
5: Computing sqrt of 0.0001 to be 0.0116755
5: Computing sqrt of 0.0001 to be 0.0101202
5: Computing sqrt of 0.0001 to be 0.0100007
5: Computing sqrt of 0.0001 to be 0.01
5: The square root of 0.0001 is 0.01
5/5 Test #5: Comp0.0001 .......................   Passed    0.02 sec

100% tests passed, 0 tests failed out of 5

Total Test time (real) =   0.13 sec
