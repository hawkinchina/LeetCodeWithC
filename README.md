# LeetCodeWithC
the answers to the leetcode questions

## dir 
├── gtest        //google test
├── leetcode     //source code
├── main         //run file
├── Makefile      // Make file ,to do
├── README.md     //
└── testcase      //test case file


##compile

<code>
  
    g++ -o 001_two_sum.o -c ./leetcode/src/001_Two_Sum.c  -I ./leetcode/include/

    g++ -o leetcode_test.o -c ./testcase/src/leetcode_test.cpp -I ./ -I ./leetcode/include/

    g++ -o TestAll.o -c ./gtest/main/TestAll.cpp -I ./

    g++ -o main *.o -I./include -L./gtest/lib -lgtest -lpthread\

</code>
