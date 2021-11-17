# Ruby Interview Cheatsheet
This is a lightweight document to refresh the ruby syntax.

## Array manipulations
First element of an array
```
arr[0]
```
Last element of an array
```
arr[-1]
arr.last
```
Second from the last element
```
arr[-2]
```
Add an element in the end of an array
```
arr.push(5)
```
Remove the last element
```
last = arr.pop #returns the element
```
Add an element in the begining of an array
```
arr.unshift(5)
```
Iterate through an array
```
arr.each do |element|
```
Iterate with an index
```
arr.each_with_index do |element, index|
```
Range of the second utill the last element
```
arr[1..-1]
```
Is an array empty?
```
arr.empty?
```
Reverse an array
```
arr.reverse
```
## Constants
Max possible number
```
max = Float::INFINITY
```
