**NOTE** : There are probably better solutions to the things addressed here. These were done with a quick/lightweight approach.
Additionally, I'm not considering extending this further for now, as I will probably be done with C# for the time being (i.e. until I have to use Unity again)

In short, **this is not supported on a regular basis at all**.

### **Various Extensions**

A few simple general utility classes that can be used in probably any project.

Though the present code is in c#, it can be easily converted to other languages.

For now, this repository contains :

- EasyObserver and MultiEventObserver (two variant Observer pattern implementations)

- "RefWrapper", a class which can be used to wrap an object and allow only one active reference to it.
This can be useful if you need to be sure that the object is not left out alive by the garbage collector, for example.
This unique reference to the object is accessed via the "RefWrapper" wrapper object. If used with events or something like an easy observer, something similar to a C++ "Destructor" can be achieved. (**TODO : ADD AN EXAMPLE**)

- A simple Tree data structure implementation
