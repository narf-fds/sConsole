# Smart Console: 
## *Take the control of your browser console log messages*

## What is it?
**Smart Console** is a **Javascript lib** to show ***console log*** messages in a colored an clearer way. 
Also, messages can be filtered showing only those that we desire at any given time.


## Features

+ Two groups of main messages.
+ Secondary info is colapsed. Expand a log to display more info.
+ Multiple colors in the same line (combined as you want)
+ Filter messages in 3 levels

## Instalation

## Basic Config

You need config the ***VERBOSE*** attribute. This attribute is used to know wich messages are going to display.

+ ***sConsole.VERBOSE = 0;*** => doesn't show any messages.
+ ***sConsole.VERBOSE = 1;*** => show all messages.



+ ***sConsole.VERBOSE = ["type1","type2"];*** => only will show messages with "type1" or "type2".
+ ***sConsole.VERBOSE = ["type1",
			{'type2':[
				{'comman1':1},
				{'command2':["ko","wrn","delete","inf"]},
			]}];*** => will show messages of "type1" or "type2" with command1 


## Hello World !!!!

It's easy

```
sConsole.log(["Hello World !!! "]);
```

## Hellow Colored World !!!

```
sConsole.log(["Hello World !!! "],undefined,["#FF6347"]);
```

## Messages

You can display messages in a line distributed in two groups. You can filter messages by the two first fields of the first group. For example

