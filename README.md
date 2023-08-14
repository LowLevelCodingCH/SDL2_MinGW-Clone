# SDL2_MinGW-Clone
Clone SDL2 and MinGW easily.

## MinGW setup:

Copy the "mingw64" folder into "C:\Program Files (x86)", that is all

# GCC setup:

Copy the "profile.ps1" script into "C:\Windows\System32\WindowsPowerShell\v1.0"
and run the following command in powershell: "Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser"
to change the policies to run the script, that is all.

# SDL2 setup:

This is easy AF, we just need to copy my SDL2 folder into the project-folder and we're done.

# Run c code:

Now, we need our gcc compiler again, run: "gcc -std=c17 main.c -I SDL2\include -L SDL2\lib -Wall -lmingw32 -lSDL2main -lSDL2 -o main

# If you followed this, you should now be initializing SDL2
