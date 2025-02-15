## Python3 Notes

- enumerate() - iterate get both index and element

  ```
  a = ["Geeks", "for", "Geeks", "room", "table", "table"]

  for i, name in enumerate(a):
      print(f"Index {i}: {name}")

  print(list(enumerate(a)))

  Output:
  Index 0: Geeks
  Index 1: for
  Index 2: Geeks
  Index 3: room
  Index 4: table
  Index 5: table
  [(0, 'Geeks'), (1, 'for'), (2, 'Geeks'), (3, 'room'), (4, 'table'), (5, 'table')]
  ```
