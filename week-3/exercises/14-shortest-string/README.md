[Week 3 Home](../../)

# U1.W3: Find the shortest string in an array

## Learning Competencies
- Define a method that accepts and uses arguments
- Apply string, array, hash, and/or enumerable methods
- Use conditional statements

## Summary
Write a method `shortest_string` which takes as its input an `Array` of `Strings` and returns the shortest `String` in the `Array`.

For example:

```ruby
# 'cat' is 3 characters long
shortest_string(['cat', 'zzzzzzz', 'apples'])  # => "cat"

# '' is 0 characters long, but it's the only string
shortest_string(['']) # => ''

shortest_string([]) # => nil
```

If the input `Array` is empty `shortest_string` should return `nil`.

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