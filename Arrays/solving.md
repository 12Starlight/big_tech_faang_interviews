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