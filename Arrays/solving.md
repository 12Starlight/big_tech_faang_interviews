# How To Solve A Question
&nbsp;
"Given an array of integers, return the indices of the two numbers that add up
to a given target"
&nbsp;

### **Step1**: [Verify the Constraints]()

&nbsp;

What are `Constraints`?

Answer: Constraints are ways in which you can understand the question better
so that you know what kind of edge cases you will need to consider as well as
all the different variables that might impact how you solve the question. This
usually comes in the form of a dialogue which means you want to ask your 
interviewer certain questions in order for you to answer and figure out what
these constraints are. Here are some examples of questions that you must ask for
this particular question:

* Are all the numbers positive or can there be negatives?
  * This is a great question to ask when you are working with integers bc
    depending on whether or not the numbers are positive or negative, this
    changes the approach and the solution that we come up with.

* Are there duplicate numbers in the array? 
  * Meaning are all of the numbers inside the array received, unique or can 
  there be duplicates

* Will there always be a solution available?
  * Meaning given the array and the target, will we always be able to find two
    numbers in the array that will add up to this target
  * The most common answer will be no there may not always be a solution
    * Examples: No two numbers add up to the target, receive an empty array, 
      receive an array that only has one value instead of two 

* What do we return, if there is no solution? 
  * Do you want us to return `-1`, an empty array `[]`, null, what do you want 
    us to return?

* Can there be multiple pairs that add up to the target?
  * No, only 1 pair of numbers will add up to the target (example)

&nbsp;

### **Step2**: [Write out some test cases]()

&nbsp;

Now that we have written all these questions, it is time to combine them all
together into different test cases. Test cases are just different combinations
of the inputs that we can receive. So, different combinations of the array and
the target that we could get that will best capture all these different edge
cases that our solution wants to account for. This is a process that you work
with your interview on by asking, is it okay that we come up with some test
cases together that best capture these different questions that you have helped
me answer for our constraints?
  * Think about what test cases could occur from the constraints that we just 
    answered

&nbsp;

Now we are going to come up with all the different test cases based on the
following answers the questions we used for constraints.

      Are the numbers positive or can there be negatives?
        All numbers are positive

      Are there duplicate numbers?
        No, there are no duplicates

      What do we return, if there is no solution?
        Just return null

      Will there always be a solution available?
        Yes, there is always a solution

      Can there be multiple piars that add up to the target?
        No, only 1 pair of numbers add up to the target

  