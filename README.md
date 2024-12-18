# Find-c-64-libraries-that-support-abf-format
## Find c++64 libraries that support abf format

**ABF（Axon Binary File）**

## specific content

Looking for a C++64 library that could completely replace pyabf, I tried to filter through search engines to achieve this goal:

1. [https://sourceforge.net/projects/libaxon/](https://sourceforge.net/projects/libaxon/)

I found that he could read some attributes of the abf file, but could not read the data correctly:
![image](https://github.com/user-attachments/assets/d7204b6d-3bd8-4fa8-9a87-70373c9ed833)


[Bottleneck, can't find out how to read and write data in abf]

2. [https://github.com/swharden/ABF-SDK](https://github.com/swharden/ABF-SDK)

This is a great ABF SDK, but it only supports x86, which is quite frustrating.

3. [https://github.com/1AoB/ABFview](https://github.com/1AoB/ABFview)

This is a 32-bit C # library, which is clearly not what we need.

4. [https://github.com/yamad/libabf](https://github.com/yamad/libabf)

This library has no documentation or examples, making it difficult to develop. Based on the current progress, it can read the total number of data points. As for how to read and write specific data, I don't know the API, it's difficult.

I choose abf2_stream version:
![image](https://github.com/user-attachments/assets/e2ea0f18-db72-4c30-9245-eb12b950041d)

[Bottleneck, can't find out how to read and write data in abf]

5. [https://github.com/ogdenkev/abfutil](https://github.com/ogdenkev/abfutil)

a glimmer of light, but it provides abffio.dll or ABFFIO.DLL are 32-bit, and 64-bit systems are incompatible! This is disappointing!

However, it seems to provide source code, I will try to use them in 64-bit systems.

There are other things to do now...
see you this afternoon.

6. 
