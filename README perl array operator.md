
# Array Operator

Perl provides a number of useful functions to add and remove elements in an array

## Push@Array
Pushes the values of the list onto the end of the array.

## Pop@Array
Pops off and returns the last value of the array.

## Shift@Array
remove one element from the beginning of the array.

## Unshift @ARRAY, LIST
add one element at the beginning of the array



## Slicing Array Elements
You can also extract a "slice" from an array - that is, you can select more than one item from an array in order to produce another array.

example :-

@days = qw/Mon Tue Wed Thu Fri Sat Sun/;

@weekdays = @days[3,4,5];

print "@weekdays\n";

This will produce the following result −

Thu Fri Sat

## Replacing Array Elements
Now we are going to introduce one more function called splice(), which has the following syntax −

splice @ARRAY, OFFSET [ , LENGTH [ , LIST ] ]

This function will remove the elements of @ARRAY designated by OFFSET and LENGTH, and replaces them with LIST, if specified. Finally, it returns the elements removed from the array.

## Sorting Arrays
The sort() function sorts each element of an array according to the ASCII Numeric standards. This function has the following syntax −

sort [ SUBROUTINE ] LIST

## Merging Arrays
Because an array is just a comma-separated sequence of values, you can combine them together as shown below −

@odd = (1,3,5);
@even = (2, 4, 6);

@numbers = (@odd, @even);

print "numbers = @numbers\n";

This will produce the following result −

numbers = 1 3 5 2 4 6

## reverse of an array 
this will reverse the complete original array 

syntax:- 

reverse(list_name);