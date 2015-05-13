# Don't be afraid

This chapter is for non-coders, so feel free to step to the next if you are a developer. 

Here a simple analogy to understand how a developer mind works while coding. 

The basic principle is language. Developers need to know a computer language. You mean, like English or French ? Yes but not quiet. 

Computer languages are minimal. The brain of a computer understand just a small set of words.  

Lets say you want to make your computer to simulate a person 'running' (John).  The problem is, the computer vocabulary does not have 'run' as a word. 

How Developers put John to run ? 

Lets assume that 'step' and 'speed' are words available in the computer's brain. Great! Our brave Developer get these 2 words and tell the computer the following instructions : 

```
step,
step,
increase speed,
repeat 
```
*ps. repeat is a magical word in the computer vocabulary. Once the computer see the word repeat, it will go back to the first step and run the pile of instructions again. Notice that if we run the pile again, it will end on a reapeat, creating a perpetual loop. *

As you probably noticed with tears, by now, John is dead. Our Developer told the computer to increase the speed in every repeat. John will start at 0 and increase his speed until he is a... Ferrari, then a rocket, then...

Since we are in a perpetual loop, the speed will keep growing higher and higher. 

To get more real, our Developer will go back and 'fix' the instructions to avoid this problem. Let's give 10 km/h as a limit speed for John: 

```
step,
step,
if speed is less than 10 km/h, then increase speed  
repeat 
```

Wow. What is that long instruction ? Computers have a great hability to compute and to be logical. Computer Languages add a series of words to help us tell a story. We can have 'if', 'then', 'else', 'equal', 'less than', 'repeat' and etc. Knowing these words is almost mandatory to code. 

Lets go back to the fix. It is telling the computer to test if the speed is less than 10km/h. If so, then increase the speed.   

That will allow John to start at 0 and increase his speed until 10 km/h.  No more speed increases for John after that. 

Is John getting out of this alive ? Not quiet. Now he will not be a Ferrari but the repeat instruction will make John run forever. 

John is still a dead man like Pheidippides, sent from the battlefield of Marathon to Athens to announce that the Persians had been defeated in battle.

Can we fix again and for godsake keep John alive ? Let's say John will run for 20 mins ? 

```
step,
step,
increase speed only if speed is less than 10 km/h 
repeat until time is equal 20 mins. 
```

Now, John is smiling at you while he passes running by!

This small alegory shows the basic principle of software development. We need a language, a story and a computer. 

Then, we may kill John along the way to proof our story.  After some tries, you eventually get it right. John is happy. 


Few extra things to notice :

Every computer language is different. In that sense, they are like the English and French comparison. A JavaScript language Developer will barely understand a COBOL language Developer.  

Like in real life, is there any similar computer languages like Portuguese and Spanish ? Yes, languages like Perl and PHP are similar, you almost can jump from one to the other. 

The last and important detail is that, there are infinite ways to tell a story. The art of storytelling could turn a program into a poem,  a novel or a greek tragedy.  



