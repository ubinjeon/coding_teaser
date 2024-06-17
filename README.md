### 자료구조
#### Stack
#### deque
#### PriorityQueue
- retrieves entries in priority order (lowest first).
- Entries are typically tuples of the form (priority_number, data)
- External Library에서 불러오기: from queue import PriorityQueue
- 선언하기: myQueue = PriorityQueue()
- entering data (priority_number, data): myQueue.put(1, "priority 1")
- remove and return the item with the lowest priority: myQueue.get()
