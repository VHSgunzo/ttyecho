# TTYECHO
* Execute commands on other tty/pts

## To get started:
* **Download the latest revision**
```
git clone https://github.com/VHSgunzo/ttyecho.git
```
* **Switch to tool's directory**
```
cd ttyecho
```
* **Compile the code**
```
make ttyecho
```

## Usage
* **Get tty/pts**
```
ls /dev/pts/
             0  1  2
tty_id=1
```
* **Execute command**
```
sudo ./ttyecho -n /dev/pts/$tty_id "COMMAND"
```
