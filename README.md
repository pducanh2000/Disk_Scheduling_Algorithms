## disk-scheduling-algorithms
#python

## Usage

* Calculator disk scheduling: SSTF, SCAN, FCFS, C_SCAN, LOOK, C_LOOK,
* Charting

# Image
![Image of CanhhnaC](/images/1.jpg)
![Image of CanhhnaC](/images/2.jpg)
![Image of CanhhnaC](/images/3.jpg)

## :gear: Setup your own

```bash
# requirement:
 Python 3.7

# Clone repo
 $ git clone https://github.com/pducanh2000/Disk_Scheduling_Algorithms.git
 
 $ cd Disk_Scheduling_Algorithms
 
# Create a virtualenv (Optional but recommended)
 $ python3 -m venv venv
 
# Activate the virtualenv
 $ source venv/bin/activate  (Linux)
 & venv/Script/Activate.ps1 (Windows)

# Install all dependencies
 $ pip install -r requirements.txt
```


## :warning: When error AttributeError: module 'time' has no attribute 'clock': ( >=python 3.8)
  - Go to: /venv/lib/site-packages/pyqtgraph
  - In file: ptime.py
  - Change systime.clock() to systime.perf_counter()
  

