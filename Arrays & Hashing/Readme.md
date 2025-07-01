Arrays & Hashing Learnings - 

1) String is not directly iterable in Java like a collection (e.g. List<Character>).
Java requires to explicitly convert String to char[] first.
So for iterating a loop across string you need to convert it to string.toCharArray()
