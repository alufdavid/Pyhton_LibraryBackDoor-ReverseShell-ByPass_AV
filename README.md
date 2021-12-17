# BackDoor-py-Lib
# This Exploit Is Based on the single malicious functionallity technique

The Idea is to inject a single function into a popular python Library
that when the main function is imported - creates a Reverse Shell to an attacker even if you have an Anti-Virus Running.

How to use:
1. set the attacker-server: [im testing on localhost - so im setting on a loopback]

  ![image](https://user-images.githubusercontent.com/89795917/134780233-182d8460-e8e2-4e29-9dc6-2c2f0a578921.png)

2. Set the Python-lib backdoor to connect to the server:

  ![image](https://user-images.githubusercontent.com/89795917/134780256-8ed5327e-2e23-4019-bcec-4c2c26edf1e3.png)

3. run the attacker-server - to start listening for connection:
  ![image](https://user-images.githubusercontent.com/89795917/134787943-316459ba-8758-44a8-9b9a-455de345ab46.png)

4. in parallel run the call module - as if someone would have called the main function in the library you have created:
  ![image](https://user-images.githubusercontent.com/89795917/134787958-4525be81-2c6b-48c0-ae8b-8ae99490b99e.png)
  
5. run commands from user privalges:
  ![image](https://user-images.githubusercontent.com/89795917/134787966-5bc1f4c3-26c4-489e-bb24-32ef67046c82.png)

now you have a shell.


enjoy :)

