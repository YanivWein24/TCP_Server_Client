## *Requirements :*
* Python 3.0 or above.
* Download the code or clone it to your local repository.
* (optionary) Assign your ipv4 address.
* (optionary) Assign your preferred PORT number.

### Assigning IPV4 Address And PORT Number:
By default, the server and the client are both set to `"localhost"` at port `5050`.   

To find Your own ipv4 adrress, open the command-line and type `ipcondig`.  
Now under "Wireless LAN adapter || Wi-Fi:" you can find:  
`IPv4 Address. . . . . . . . . . . : xxx.xxx.xxx.xxx`

To use your own ipv4 address and port number, locate the `"SERVER"` and `PORT` variables on both `TCP_Server.py` and `TCP_Client.py`:
```python
SERVER = "localhost"
PORT = 5050
```
Here you can insert your own address and port number

```diff
- SERVER = "localhost"
+ SERVER = "Your ipv4 address"

- PORT = 5050
+ PORT = your_port_number
```  
<br>
  
## Run On Mobile:  
This code can also get executed on mobile using Pydroid3!    
You can run both the server side and client side on your mobile device, and connect between different devices!  
To do so, copy the files to your mobile storage, and follow the instructions above ( using Pydroid3 editor ).

**If you wish to connect with multiple devices, make sure that all the devices are connected to the same network.**  
<br>
  
## *Screenshots :*
Server side - Listen for connection:  
<img src="https://user-images.githubusercontent.com/97472180/168477353-14a4f2ed-a2db-4af2-add4-b4605c3eeb27.png" alt="Listen" width="240" height="290"/>  
  
Server side - auto close when all connections are closed:  
<img src="https://user-images.githubusercontent.com/97472180/168477351-35c1b336-4165-41c4-a433-b8491dacee08.png" alt="Auto-close" width="315" height="100"/>  
  
Client side - menu:  
<img src="https://user-images.githubusercontent.com/97472180/168477346-544460c9-3b0d-4886-b6e8-d8f7716bcfb3.PNG" alt="client-menu" width="280" height="115"/>
  
Client side - echo response:  
<img src="https://user-images.githubusercontent.com/97472180/168477345-073a250f-5201-4f37-973a-3d16342e81eb.PNG" alt="Client-response" width="315" height="100"/>  

Client side - asking for time:  
<img src="https://user-images.githubusercontent.com/97472180/168477348-41d57855-6708-49fd-8369-45ef0f1ae8f4.PNG" alt="Client-time" width="320" height="45"/>

Server side - asking for time:  
<img src="https://user-images.githubusercontent.com/97472180/168477343-69556caa-ab36-4c3b-8145-531dbd842058.png" alt="Client-time" width="470"  height="45"/>


