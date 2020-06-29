# SharedMemCom
Inter Process Communication between e!Cockpit and C-Application

## Solution 1 - With WagoAppMem library:
>Find the e!Cockpit example and C-application in this repo. There is a pre-built target file (target-folder) that can be placed and runned directly on the controller using
a FTP client, or SSH. Make sure you have permission to execute (sudo chmod +x).

## Solution 2 - With external 3S library:

>This example shows how data can be exchanged between a CODESYS controller and other processes by means of shared memory.
[CoDeSys 3.5 library](https://store.codesys.com/shared-memory-communication.html)

>The shared memory can be used to exchange data within a target system when no direct communication is possible, e.g. the data exchange with an external visualization. How to create this shared memory and how to read and write to it is shown in this example.
[CoDeSys 3.5 library](https://store.codesys.com/shared-memory.html)
