- defaultdict 
```
  Example - 1
    from collections import defaultdict
  
    d = defaultdict(list)
    
    # Add elements to the defaultdict and print it
    d['fruits'].append('apple')
    d['vegetables'].append('carrot')
    print(d)
    
    # No key error raised here and an empty list
    print(d['juices'])
    
    Output:
      defaultdict(, {'fruits': ['apple'], 'vegetables': ['carrot']})
      []

  Example - 2
    freq = defaultdict(int)
    word = "abbcba"
    for char in word:
        freq[char] += 1
      
    print(freq)
    for word,count in freq.items():
        print(word,count)
          
    Output:
      defaultdict(<class 'int'>, {'a': 2, 'b': 3, 'c': 1})
```

- Counter
```
  from collections import Counter
    s = "GeeksforGeeks"
  
    freq = Counter(s)
    print(dict(freq))
    
  Output:
    {'G': 2, 'e': 4, 'k': 2, 's': 2, 'f': 1, 'o': 1, 'r': 1}
```
