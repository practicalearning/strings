# Strings
String Data Type

## What is a String?
String is textual data, for example name, paragraph, song, lyrics or etc... .

## How do you declare a string in Python?
To create a string, put the sequence of characters inside either single quotes, or double quotes up to you

### one line
```
name = 'salman'
```
```
song = "please wake up"
```

### multiple lines
```
paragraph = '''I am a person who is positive about every aspect of life. 
There are many things I like to do, to see, and to experience. 
I like to read, I like to write; I like to think, 
I like to dream; I like to talk, I like to listen. 
I like to see the sunrise in the morning, 
I like to see the moonlight at night'''
```

```
lyrics = """I can tell time by the moon
I can tell time by the sun
No matter how I mark
The hour's light and dark
I tell you your time's just begun
It is morning in your life
Day is breaking, oh so bright
You've barely made a start
Just one beat of my heart
Don't sleep away the morning light"""
```

## Finding how many characters are in string
To find how many characters are in our string we used len method
``` len("hi") # 2 ```
``` len(name) # 6 ```
``` len(song) # 14 ```
Note: The index in len start at 1 and the space is count

## Access strings characters individually
To access strings characters individually we used square brackets and pass the value of index [index], The index of string in python start at 0 which mean the index of first letter is 0
``` name[0] # s ```
``` song[7] # w ```

## Access a range of characters
To access a range of characters we used square brackets and pass two values the first one is value of start index and the second is value of end index and there is colon between they [start_index:end_index].
``` lyrics[12:19] # ime by ```
``` paragraph[6:11] #  pers```
Note: The end index is not included

If you do not pass the start index [:end_index] the start index will be 0 or If you do not pass the end index [start_index:] the end index will be equal to the length of your string.
``` lyrics[:9] # I can tel ```
``` paragraph[296:] # ight ```
Note: This part call slicing
