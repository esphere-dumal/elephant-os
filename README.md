# Learning OS
Creating a small OS step by step

running:
- make all
- ./start
- in the bochs, enter "c" to run 

now finished:
- MBR
- boot loader
    - enter protected mode
    - turn paging
    - load and initialize kernel
- a simple kernel
    - with put_something() function for char\string\int
    - simple interupt handle function
- using makefile
- memory
    - able to alloc memory by pages
- process
    - thread