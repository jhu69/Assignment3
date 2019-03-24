OS needed: linux.cs.mcgill.ca

Things to know about my program:
1) The backing store just gets created in the folder where you're running mykernel using gcc

2) If this doesn't work then change the backing store directory to where you want it created but the system("mkdir BackingStore") should create it in which ever folder you compiled using gcc so in this case it would be in the "Assignment3" folder 

3) Some how when after being compiled on linux, the mykernel has a segmentation fault sometimes reandomly during the program's execution but this does not happen on my MacOS X operating system. Like it never segmentation faults ever. I tried fixing this issue but have no idea why it keeps segmenting sometimes. 

4) mykernel runs with a last command quit so it quits out of the program for (mykernel < testfile.txt)

5) All versions of exec work and other commands work as well

6) Thanks for grading!! :) :)

