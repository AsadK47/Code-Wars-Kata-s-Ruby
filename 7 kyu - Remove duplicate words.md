# Task
Your task is to remove all duplicate words from string, leaving only single (first) words entries.

Example:

Input:

'alpha beta beta gamma gamma gamma delta alpha beta beta gamma gamma gamma delta'

Output:

'alpha beta gamma delta'

# My solution
```ruby
def remove_duplicate_words(s)
  s.split().uniq.join(' ')
end
```

# Better solution
```ruby
def remove_duplicate_words(s)
  s.split.uniq*' '
end
```
