# Vscode - key debugging & short-cuts

Author(s): Arturo Filio Villa

Status: [Draft]

Last Updated: 2/23/2023

## Suporting documents
_I'm using a node project to exemplify all these_
_setps required to setup and use the debugger for vscode_
_you can find example code in app.js_

## Index:
- Goals
- Setting up the debugger for backend

## Objective
This documentation page will serve to support new and current software engineers within
acivilate that will want to setup their Vscode environment for debugging both for backend development AND frontend development.

## Goals
Our goals that we will try to reach with this documentaion is to make sure that the dev team who makes use of this doc. page, has a better understanding on how to setup debuggin in addition to some additional keybindings for Vscode and thus, improve their developer experience.

## Setting up the debugger for backend
To setup your Vscode to debug your backend it's actually very simple. In vscode you have an icon that looks like the following:

(Figure 1)
<image src="./images/debug_logo2.png" height="90" width="100"/> 
<br/>

You click on it and you can possibly see the following:

(Figure 2)
<image src="./images/debug_menu.png"/>
<br/>

You want to click on the "create a launch.json file"

This file will be the configuration file for your debug and vscode will do all the creation for you. 
<strong>(see the configuration file inside the .vscode folder)</strong>

Once you have the launch.json file created and you are inside the "debug" side tab (refer to Figure 2), you will probably now see it blank and just see a play button.

(Figure 3)
<image src="./images/play_button.png">
<br/>

This button now will start your debugger but you first need to setup up your flags.

(Figure 4)
<image src="./images/flags.png">
<br/>
Notice the red dots on the left to the numbered lines. Those red dots are flags (you click there, on the left, to setup a flag if desired), that server as breaking points or points where you want your code to stop so you can analyze the data flow and you will see a debug menu to control the processes:

(Figure 5)
<image src="./images/debugger_buttons.png"/>
<br/>
With this you will be able to restart, go to next/previous process, jump over next process, or stop the debugger overall.

(Figure 6)
<image src="./images/next_button.png"/>
<br/>
This button is the responsible to take the process to the next one, once the debugger hits a breaking point.