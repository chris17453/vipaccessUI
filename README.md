# vipaccessUI
A python-tkinter frontend for the python module python-vipaccess2. Which itself is a customized fork of a fork of a fork. At its core it is a TOPF implimentation. The same as the symanmtec VIP Access Token.


## Install
```
pip install --user vipaccessUI
```

## Step 1 - Create a Token
- There are multiple types of token types, your company may only allow a certain type.
- The most common types are  (VSMT,VSST,SYMZ)
- More info about types->  https://support.symantec.com/en_US/article.TECH239895.html 
```
vipaccess provision -t VSMT
```
- This will give you something like
```
VSMT12345678
```

## Setp 2 - Register the token
- The keys are NOT valid unless the provisioned token is registered successfully
- Ask your IT department, HR, or security if you do not know where to register the provisoned token


## Step 3 - Run
- From the gnome menu it will appear as vipaccessUI, the icon is a key
- From the terminal type "vipaccessUI"


## USE
- Click the 6 digit token copy it to the clipboard


##  TODO:
- create windows and mac install


## Demo
![Demo](https://raw.githubusercontent.com/chris17453/vipaccessUI/master/data/demo.gif)

