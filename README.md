## *Requirements :*
* Python 3.0 or above.
* Download the code or clone it to your local repository.
* (optionary) Assign your ipv4 address on both `TCP_Server.py` and `TCP_Client.py`
* (optionary) Assign your preferred PORT number - default is 5050

### Assigning IPV4 Address And PORT Number:
By default, the server and the client are both set to `"localhost"` at port `5050`.       
to use your own ipv4 address and port number, locate the `"SERVER"` and `PORT` variables on both files:  
```python
SERVER = "localhost"
PORT = 5050
```
Here you can insert your own address

```diff
- SERVER = "localhost"
+ SERVER = "Your ipv4 address"

- PORT = 5050
+ PORT = your_port_number
```

## Run On Mobile:
This code can run be executed mobile using Pydroid3!    
You can run both the server side and client side on your mobile device, and connect between different devices!  
to do so, copy the files to your mobile storage, and follow the instructions above.

**If you wish to connect with multiple devices, make sure that all the devices are connected to the same network.**