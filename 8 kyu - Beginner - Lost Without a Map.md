# Task
Given an array of integers, return a new array with each value doubled.

For example:

[1, 2, 3] --> [2, 4, 6]

For the beginner, try to use the map method - it comes in very handy quite a lot so is a good one to know.

# My solution
```ruby
def maps(x)
  x.map{ |y| y * 2 }
end
```

# Better / Factored 1 line solution
```ruby
def maps(x) x.map {|n| n * 2 } end
```
