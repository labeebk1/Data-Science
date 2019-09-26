# Tree

```Python
class Node:
  def __init__(self, num, left = None, right = None):
    self.num = num
    self.left = left
    self.right = right
  def __len__(self):
    if self.left == None and self.right == None:
      return 1
    else:
      return 1 + len(self.left) + len(self.right)
  def __str__(self):
    pass
  def insert(self, num):
    pass
  def delete(self, num):
    pass
  def search(self, num):
    pass
```
