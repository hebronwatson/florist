# florist
Manages scripts so you can author, edit, run, and test them easily.

"Run, Florist, Run!"

You write code, then you run it. Everytime you run it, you have to write again to run the command that writes the code. When you change the code, you have to write more commands, and so on and so on. 

What if there was a framework for automating these many repetitive tasks so that they could be managed as you see fit, from batch tasks, to tasks triggered by state changes? And don't forget running apps!

Florist does many things, but they all fall under the same category: running software on one computer with maximum ease.

The goals of Florist are ass follows:
1. store your bash, zsh, and fish scripts on the path
2. track their status and compare it to the desired state
3. manage packages of scripts for easy updating
4. provide facilities for testing scripts by their output and side-effects (effect on system package management)
5. provide plugin interfaces for testing and other facilities.
