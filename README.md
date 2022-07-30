Design your implementation of the circular queue. The circular queue is a linear data structure in which the operations are performed based on FIFO (First In First Out) principle and the last position is connected back to the first position to make a circle. It is also called "Ring Buffer".</br>
One of the benefits of the circular queue is that we can make use of the spaces in front of the queue. In a normal queue, once the queue becomes full, we cannot insert the next element even if there is a space in front of the queue. But using the circular queue, we can use the space to store new values.</br>
Implementation the MyCircularQueue class:</br>
* MyCircularQueue(size) Initializes the object with given size of the queue.
* get_front() Gets the front item from the queue. If the queue is empty, return -1.
* get_rear() Gets the last item from the queue. If the queue is empty, return -1.
* enqueue(value) Inserts an element into the circular queue. Return true if the operation is successful.
* dequeue() Deletes an element from the circular queue. Return true if the operation is successful.
* is_empty() Checks whether the circular queue is empty or not.
* is_full() Checks whether the circular queue is full or not.

# Constraints

1 <= size <= 1000
0 <= value <= 1000
At most 3000 calls will be made to enqueue, dequeue, get_front, get_rear, is_empty, and is_full.
