# fizzbuzz
Test Driven Development (TDD) and Pair Programming challenge.  
  
##How it works:  
The program is passed a number.  
When passed a number that is a multiple of 3, the program returns the message "fizz".  
When passed a number that is a multiple of 5, the program returns the message "buzz".  
When passed a number that is a multiple of 3 and 5, the program returns the message "fizzbuzz".  
When the number is neither of the above, the number is returned.  
  
To run, type in Irb or Pry:  

```  
$ require "./lib/fizzbuzz"  
  
$ (1..20).each {|num| puts "#{num} --> #{fizzbuzz(num)}"}  
1 --> 1  
2 --> 2  
3 --> fizz  
...  

```  

