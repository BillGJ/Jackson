# Exercise: Jackson

This is a simple Java Exercise where the goal is 
to serialize a class called `UdacisearchClient` to JSON 
and then deserialize it from JSON using the [Jackson](https://github.com/FasterXML/jackson) JSON Library.

## How does it work?
You may be wondering how Jackson works. 
The secret is sauce Java Reflection. 
Jackson uses Java's Reflection APIs to examine the `UdacisearchClient` class structure at run time, 
and make serialization/deserialization decisions based on what it finds.

## Compiling and Running

    javac -cp ".;lib/*" Main.java
    java -cp ".;lib/*" Main client.json