## Runing jupyter notebook from remote shell

1. First Run ```jupyter notebook``` from project directory of remote server.
2. Notedown the port number .
3. Finally run the following commands from local meachine
    ```ssh -L 8888:localhost:<remote_port> <remote_user_name>@<remote_ip>```
4. Point the browser at ```localhost:8888```    
