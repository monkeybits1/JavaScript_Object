# JavaScript_Object

How to deep compare JavaScript objects? 

This code helps to deep compare objects containing string, number, boolean, function, array, and nested objects.

The fastest way to compare two objects is to use JSON parsing methods, unless the ordering in both objects are different. 

Then you need to hard code by using for-in loop. 

The idea is to use JSON-first methods:

1. Firstly compare object size by Object.keys().length and/or Array.length

2. Secondly compare objects by JSON.parse()

3. thirdly compare objects based on data type


