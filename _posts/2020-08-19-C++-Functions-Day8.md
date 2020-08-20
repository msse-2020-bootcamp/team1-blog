---
layout: post
title: "C++ Functions, Data Passing, Throwing Errors & File IO"
author: Ron Yadin
---

Day eight of the MSSE bootcamp expanded on  this week’s introduction of C++ by focusing on function building. We learned that in C++, each function definition must start with a specification of the return type. This specification comes right before the function name, and describes the data type that will be returned when the function is called - and therefore, it must accord with what follows “return” at the end of the function body. 

We also learned about the three main ways that data is passed to a function in C++. Namely, this is done by copy, by reference, and by constant reference. When passing data by copy, the function reads the data values and then initializes a new local variable using those data values. The new local variable has a separate address from the initial data passed, and modifications to the local variable will not modify the original data. When passing data by reference, a reference to the data is created for use in the function, which shares the original data’s address and is mutable. When using the term “const” to pass data by constant reference, an immutable reference is used which is the original data at the same address, but cannot be changed. 

And lastly, we touched on examples of throwing errors and file I/O. We used try and catch to practice throwing errors in our temperature function, which we had modified to accept a std::vector of temperatures as an input type.  And we practiced writing and reading a simple txt file. 
