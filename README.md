# fizzbuzz
create an application that plays FizzBuzz. 
 // We declare a variable i and assign it 1: the initial value of the variable i in our loop. The second clause, i <= answer is our condition. We want to loop until i is greater than answer. The third clause, i++, tells our loop to increment i by 1 every iteration. As a result, if the user inputs 10, this loop would print numbers 1 - 10 to the console. 

 //The first condition now checks if i is divisible by 3 and 5 instead of checking if i is just divisible by 3. We’ve had to do this because if we kept it the way it was, it would run the first condition if (i % 3 === 0), so that if i was divisible by 3, it would print Fizz and then move on to the next number in the iteration, even if i was divisible by 5 as well.

 //With the condition if (i % 3 === 0 && i % 5 === 0) coming first, we check that i is divisible by both 3 and 5 before moving on to check if it is divisible by 3 or 5 individually in the else if conditions.
 //