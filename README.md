# Bootcamp-Server

## Want to use this project?
### Basics
1. Fork/Clone
2. Activate a virtual environment
```sh
$ python3 -m venv env
```
3. Install dependencies
```sh
pip install -r requirements.txt
```


### Run the Application

```sh
$ python manage.py runserver
```

Access the application at the address [http://localhost:5000/](http://localhost:5000/)

### Run the Application (Serve publicly on your network)
```sh
$ python manage.py runserver -h 0.0.0.0
```
Access the application at the address [http://0.0.0.0:5000/](http://localhost:5000/)
To allow other devices on your network to find the server, you must first find your public IP address.
To do so, run this shell command:
```sh
$ ifconfig | grep inet
```
It will output the following text:
![Save the IP address highlighted in red](https://i.imgur.com/8dnVha0.png)
Then tell the devices to go to: [http://<PUBLIC_IP_ADDRESS>:5000/](http://<PUBLIC_IP_ADDRESS>:5000)

