# Overview: 

FlutterFlow supports basic return data types such as **String**, **int**, **boolean**, and **List<T>** types. However, while working with more **complex data structures** like a custom model or a class, these are not directly supported as return types.

However, there is actually a way to implement this: by **wrapping the complex data structure in a JSON string**, which will return it as type **String**. After that, we can **parse that string** to extract usable fields inside FlutterFlow.

This approach allows us to **implement structured data** without any need to return an actual object.
