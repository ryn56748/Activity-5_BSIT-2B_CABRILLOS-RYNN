A linked-list stack pushes items at the head because it is faster and takes O(1) time. 
Adding items at the tail would require finding the last node if there is no tail reference.
An array queue must be circular so it can reuse empty spaces at the beginning of the array after items are removed.
Without circular movement, the queue might run out of space even when some array positions are empty.