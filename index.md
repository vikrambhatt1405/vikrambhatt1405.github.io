<!-- ---
layout: default
--- -->
# Protocol buffers

>
Protocol buffers are Google's language-neutral, platform-neutral, extensible mechansim for serializing structured data. It's faster and simpler. It has support for
C++, C#, DART, GO, JAVA, PYTHON.

- With protocol buffers, you write a ```.proto``` description of the data structure you want to store.

- From that, protocol buffer compiler creates a class that implements automatic encoding and parsing of the protocol buffer data with efficient binary format.

- The generated class provides getters and setters for the fields that make up a protocol buffer and takes care of the details of reading and writing the protocol buffer as a unit.

- Importantly, the protocol buffer format supports the idea of extending the format over time in such a way that the code can still read data encoded with the old format.

Let's work with a simple example.
- ```touch example.proto```

 Create an empty example.proto file.
