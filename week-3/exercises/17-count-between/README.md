[Week 3 Home](../../)

# U1.W3: Count the number of elements between two bounds

## Learning Competencies
- Define a method that accepts and uses arguments
- Use conditionals (if/elsif/else)
- Iterate over arrays
- Apply string, array, hash, and/or enumerable methods

## Summary
Write a method `count_between` which takes three arguments as input:

1. An `Array` of integers
2. An integer lower bound
3. An integer upper bound

`count_between` should return the number of integers in the `Array` between the two bounds, including the bounds

It should return `0` if the `Array` is empty.

Some examples:

```ruby
count_between([1,2,3], 0, 100)      # => 3
count_between([-10, 1, 2], 0, 100)  # => 2
count_between([10, 20, 30], 10, 30) # => 3
count_between([], -100, 100)        # => 0
count_between([0], 0, 0)            # => 1
```

## Releases

## Release 0: Pseudocode
Consider what you need to do to solve the challenge. You can write it down if it will help you, or you can move on to the next release.

## Release 1: Initial Solution
Code your solution in the [my_solution.rb](my_solution.rb) file.

## Release 2: Test
Run the tests to make sure your code passes!

Remember, type `rspec` followed by the spec file name (and make sure you are in the proper directory).

## Release 3: Refactor
Make any necessary changes based on the tests. Then run the tests again.

Make sure all the tests pass before moving on.

## Release 4: Publish
When your solution is passing all of the tests, commit and push your changes!