# BackEnd

- Install Python3

```
sudo apt-get update

sudo apt-get install python3.8

```

- Install Redis

```
sudo apt install redis-server

sudo nano /etc/redis/redis.conf

# change "supervised no" to "supervised systemd" 
supervised systemd

sudo systemctl restart redis.service

sudo systemctl status redis

```

- Create virtual environment

```
python3 -m venv boTrading

cd boTrading/

source bin/activate

```

- Clone git respository 

```
git clone https://github.com/Cryptobetting/backend.git

cd backend\

```
- Install Requirements

```
pip install -r requirements.txt

```

- Run the code

```
python createJson.py

```

- Install Supervisor

```
pip install supervisor

supervisord -c supervisord.conf

```
