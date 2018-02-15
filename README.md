# Inpy

This is a python module for pygame,

To use:

# 1. Install:

## Windows
`pip install inpy`

## Mac
`pip3 install inpy`

## Linux
`sudo pip install inpy`

# 2. To Use
### 1.Create a String:

inputTest = ""
  
### 2.Inside a loop use this template to get input:

[Variable] = inpy.inputField([Pygame Events], [Variable], [Special Characters (True / False)])

E.G:
inputTest = inpy.inputField(events, inputTest, True)

### 3.Render text with the text being the variable.

