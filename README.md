
An if statement alone cannot determine whether text such as "abc" can be converted into an integer. The int() function raises a ValueError when it receives invalid text, so try and except are needed to handle the error safely.
