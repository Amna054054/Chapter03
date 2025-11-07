Chapter 03 CODES
Spawning:



<img width="828" height="201" alt="spawning py" src="https://github.com/user-attachments/assets/74d521dc-38a1-463d-a5a0-1a2361b7baba" />



Killing:



<img width="1136" height="282" alt="ss output" src="https://github.com/user-attachments/assets/22dbe6c4-43c5-4990-a00c-e6a0eba057c3" />



Naming:



<img width="788" height="377" alt="naming py" src="https://github.com/user-attachments/assets/5913548f-f7cb-4230-86f4-ae6f72729778" />






Conclusion:
In Chapter 03 we learn the process of Spawning, Killing and Naming, Discuss briefly below:
Spawning:
This is the process which runs asynchronously i.e first the process starts using a method 'start()' and then the parent process waits for its child process to complete using method 'join()'
Naming:
In Python’s **multiprocessing**, each process can be given a unique **name** to easily identify it during execution or debugging. By default, processes are named like *Process-1*, *Process-2*, etc., but you can assign custom names using the `name` parameter when creating a process. This naming system is helpful for monitoring, logging, and understanding which process is performing a specific task in concurrent programs.
Killing:
In Python’s **multiprocessing**, a process can be **killed** or **terminated** using the `terminate()` method. This immediately stops the process, even if it hasn’t finished its task, and releases its resources. It’s useful when a process is stuck or no longer needed, but should be used carefully because it doesn’t allow the process to clean up before ending.

