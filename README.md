### **Various Extensions**

A few small general utility classes that can be used in an project.

Though the present code is in c#, it can be easily converted to other languages.

For now, this repository contains :

- EasyObserver and MultiEventObserver (two Observer pattern implementation)

- "Reference Wrapper", a class which can be notably used to wrap an object and allow only one active reference to it.
This can be useful if you need to be sure that the object is not left out alive by the garbage collector, for example.
This unique reference to the obejct is accessed via the wrapper object. The "Reference Wrapper" also offers a workaround to achieve something similar to a C++ "Destructor".
When "DestroyWrappedReference" is called, the reference to the wrapped object is set to null, and "on destruction" callbacks are launched. These callbacks can be registered or unregistered through the wrapper from anywhere by anything.  

- Tree data structure implementation