# Task
This kata is about multiplying a given number by eight if it is an even number and by nine otherwise.

# My solution
```ruby
def simple_multiplication(number)
  if number % 2 == 0
    number * 8
  else 
    number * 9
  end
end
```

# Better solution
```ruby
def simple_multiplication(number)
  number.even? ? number * 8 : number * 9
end
```
