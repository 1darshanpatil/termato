# termato
termato is a Python-based pomodoro timer. Boost productivity with customizable work and break intervals, a progress bar, and notifications. Open-source, for better time management.




# Pomodoro Timer Help
-------------------

## Usage

python pomodoro.py [OPTIONS]

## Options

- **-w=<work_time>**: Set the duration of each work interval in minutes. Default: 25 minutes.
- **-b=<break_time>**: Set the duration of each regular break in minutes. Default: 5 minutes.
- **-r=<rounds>**: Set the total number of completed pomodoro intervals (work round + break). Default: 4.
- **-h**: Display this help message.

## Example


python pomodoro.py -w=30 -b=10 -r=3

This will start a pomodoro timer with a work interval of 30 minutes, a break of 10 minutes, and 3 completed rounds.

## Note

- The script will use default values if any option is not provided.
- Only `-w`, `-b`, `-r` options are recognized. All other parameters will be ignored.
- Press Ctrl+C during the timer to stop the script.


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/1darshanpatil/termato
   cd termato
   ``````

```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
``````


```
$pip install -r requirements.txt
```

How to execute without and with parameters for windows OS
```
python.exe pomodoro.py
python.exe pomodoro.py -w=25 -b=5 -r=4
```
For Linux and MacOS
```
./pomodoro.py
./pomodoro.py -w=25 -b=5 -r=4
```
