# tg_analyzer
### this script will do some processes on your telegram chat history!

first you should export a chat from telegram using telegram-desktop
then, copy .py file near html files(it doesnt need other files)

to run program you should install `beautifulsoup4` and `python3`
after installing, run by this : `python3 2person.py` or `python3 group.py`

wait program to load and process, it may take a while if messages are lot
you can specify name of sender in `group.py` in lines of code (sorry for little mess!)
here is construction for specify name in group (for `froup.py`)
look at this:
```py
  #if "f_name" in sender.lower() and "l_name" in sender.lower() :
  db[int(time[1:3])]+=1;
```
first line is commented!
change it like this :
```py
  if "ali" in sender.lower() and "alavi" in sender.lower() :
  db[int(time[1:3])]+=1;
```

this will find all ali alavi's messages in that group!
