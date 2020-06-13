# ref-python-drone
Drone control by Python

## Dev Environment

### Phython (MAC)

Install HomeBrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Install Pythond3 with Brew
```
brew install python3
```

Check Phython
```
(albert) ~/_dev/_robot/python-drone/ref-python-drone $ python3
Python 3.7.7 (default, Mar 10 2020, 15:43:03) 
[Clang 11.0.0 (clang-1100.0.33.17)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> ^D
(albert) ~/_dev/_robot/python-drone/ref-python-drone $ 
```

(optional) Add path environment at your '~/.profile' file
```
export PATH=/usr/local/bin:/usr/local/sbin:$PATH
```
 * usually, Phython installtiona directory will be ```PATH="/Library/Frameworks/Python.framework/Versions/3.6/bin:${PATH}"```
 * Do not change PATH env if you can run ```python3``` cli on the terminal
 
 ### OpenCV
 
 install opencv 
 ```
 brew install opencv
 ```
