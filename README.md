# BackDoor-py-Lib
A python Library that when the main function is imported - creates a Reverse Shell to an attacker

How to use:
1. set the attacker-server: [im testing on localhost - so im setting on a loopback]

  ![image](https://user-images.githubusercontent.com/89795917/134780233-182d8460-e8e2-4e29-9dc6-2c2f0a578921.png)

2. Set the Python-lib backdoor to connect to the server:

  ![image](https://user-images.githubusercontent.com/89795917/134780256-8ed5327e-2e23-4019-bcec-4c2c26edf1e3.png)

3. run the attacker-server - to start listening for connection:
  ![image](https://user-images.githubusercontent.com/89795917/134780284-d2c19f19-0dc6-4607-861d-fa92872b0440.png)

4. run the call_module - as if someone would have called the main function in the library you have created:
  ![image](https://user-images.githubusercontent.com/89795917/134780388-0c6fd1e6-1914-4cb4-9cf9-1ce563191597.png)

now you have a shell.
enjoy :)
