# Linked List

```Python
class Node:
  def __init__(self, first, next = None):
    self.first = first
    self.next = next
  def __len__(self):
    if self.next == None:
      return 1
    else:
      return 1 + len(self.next)
  def insert(self, num):
    new_node = Node(num)
    self.next = new_node
  def delete(self, num):
    pass
  def search(self, num):
    pass
```
