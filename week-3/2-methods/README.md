[Week 3 Home](../)

#U1.W3: Variables and Methods

## Learning Competencies
- Define local variables and methods
- Run a Ruby program from the command line

## Summary
Now is your chance to put what you've learned together!

## Releases

## Release 0: Read Ch. 5: Mixing it up
I can't tell you how many times you will (probably) make this mistake. It's incredibly important to know which kind of variable you are working with. If you don't know, you will get some crazy errors. Use IRB to practice as you read through it.

## Release 1: Try it out
Complete the two mini-challenges Pine created using Sublime and running it through your terminal. Paste your solution into the my_solution.md file associated with this challenge.

- Full name greeting: Write a program that asks for a person's first name, then middle, then last. Finally, it should greet the person using their full name.

- Bigger, better favorite number: Write a program that asks for a person's favorite number. Have your program add 1 to the number, and then suggest the result as a bigger and better number.

## Release 2: Creating Methods
We are going to deviate a bit from Pine's introduction for a minute by introducing you to the idea of creating your own methods.

You can assign blocks of code to an object called a method. This encapsulates code to run when you call the name of the method instead of writing the full code each time. For example, imagine writing return addresses on envelopes (who does that anymore)? Instead of writing it out every. single. time., it would be easier to create a label. This is basically the same idea as using methods. If I were to use Pine's instructions to get an address from a user, it would look something like this:

```ruby

puts "What is your name?"
name = gets.chomp
puts "What is your street address?"
street_address = gets.chomp
puts "What is your city, state, and zip code?"
city_state_zip = gets.chomp
puts #this will add a new line
puts name
puts street_address
puts city_state_zip

```

That's a lot of code for one simple address!

Here is how we can use a method to "wrap" the code. We are changing how the code works a bit here, instead of getting user input for the arguments, we are defining them when we call the method.

```ruby
# print_address is a method we've defined
# print_address takes three arguments (name, street_address, city_state_zip)

def print_address(name, street_address, city_state_zip)
  puts name
  puts street_address
  puts city_state_zip
end

print_address("Maria Piper", "633 Folsom Street", "San Francisco, CA 94107")
# this last statement calls the method which will output to the screen

```

In the next few exercises, we will be asking you to "wrap" logic into a method.

Now's your chance to practice! Complete the [Define an Empty Method](../exercises/4-defining-method) challenge.

## Release 3: Read Ch. 6: More About Methods
Read through the entire chapter to get a better feel for the built-in methods Ruby has. (There are a LOT more, by the way).

## Release 4: More small challenges!
Now you'll want to expand your brain a bit by working on the following challenges.

- [Return a Formatted Address](../exercises/5-format-address)
- [Defining Math Methods](../exercises/6-math-methods)

## Release 5: Reflect
In your [my_reflection.md](my_reflection.md) use the [reflection guidelines](https://github.com/Devbootcamp/phase-0-handbook/blob/master/coding-references/reflection-guidelines.md) to reflect on your learning. Remember, reflections should be directed toward an audience, but they don't need to be lengthy. A short paragraph will suffice. Try to keep your reflection writing to 10-15 minutes.