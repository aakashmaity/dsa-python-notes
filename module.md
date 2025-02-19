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
  word = "ababc"

  for char in word:
      freq[word] += 1
  
  print(freq)
        
  Output:
    
```

- Counter
```
  from collections import Counter
  s = "GeeksforGeeks"
  
  # Count character frequency using Counter
  freq = Counter(s)
  
  print(dict(freq))
  
  Output:
    {'G': 2, 'e': 4, 'k': 2, 's': 2, 'f': 1, 'o': 1, 'r': 1}
```
