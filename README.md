# frida-afl-instr

One upon a time there was frizzer, a fuzzer based on Frida, and a guy, Andrea, that sometimes writes stuffs for the awesome project AFLplusplus.
One day Andrea found frizzer walking on GitHub and so decided to try to implement an instrumentation for AFLplusplus based on Frida with the aim to discover bugs in Andorid applications.
That day, Andrea loose 2 hours of his precious time.

This shit **works**. How works is a problem. 3 exec/s on my laptop fuzzing the test binary.

Do you want to use it? Good luck.

`afl-fuzz -U -i in -o out -- python3 fuzz.py`
