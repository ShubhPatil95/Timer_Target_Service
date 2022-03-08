# Timer_Target_Service
This page contains the information to create the service which will run the python script at specific time and then after it will get closed. This process reduces the CPU consumption.

### Step 1: Run below commands in terminal
```bash
sudo -s
cd /lib/systemd/system
nano Model.service
```
### Step 2: Create Model.service [Model.service](https://github.com/ShubhPatil95/Timer_Target_Service/blob/main/Model.service)

### Step 3: Create Model.target [Model.target](https://github.com/ShubhPatil95/Timer_Target_Service/blob/main/Model.target)

### Step 4: Create Model.timer [Model.timer](https://github.com/ShubhPatil95/Timer_Target_Service/blob/main/Model.timer)

### Step 5: Start the Model.timer and see if Model.service is activated
```bash
systemctl start Model.timer
systemctl status Model.service
```








