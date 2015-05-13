# Don't be afraid

This chapter is for non-coders, so feel free to step to the next chapter if you are a developer. 

The goal is to understand the idea of coding and how we create a set of instructions to tell a story.   

First, developers need to know a computer language. Do I mean something like English or French ? Yes but not quiet. 

Computer languages are minimal. Think about 50 reserved words for example, which is the real case of a language called JAVA. 

Lets say we want to make our computer to simulate a person 'running' (John).  The problem is, the computer vocabulary does not have 'run' as a word. 

How Developers put John to run ? 

Lets assume that 'step' and 'speed' are words available in our computer's language. Great! We get these 2 words and tell the computer the following instructions : 

```
step,
increase speed,
repeat           
```
*ps. repeat is a magical word in the computer vocabulary. Once the computer see the word repeat, it will go back to the first step and run the pile of instructions again. Notice that, running the pile again means that we will end on another reapeat, creating a perpetual loop. *

As you probably noticed with tears, by now, John is dead. We told the computer to increase the speed in every repeat. John will start at 0 and increase his speed until he is a Ferrari, then a rocket, then...

Since we are in a perpetual loop, the speed will keep growing higher and higher. 

To get more real, we will go back and 'fix' the instructions to avoid this problem. Let's give 10 km/h as a speed limit for John: 

```
step,
if speed is less than 10 km/h, then increase speed  
repeat 
```

Wait a minute. What is that long instruction ? Computers have a great ability to compute and to be logical. Computer Languages exploit that by supplying us with a series of special words: 'if', 'then', 'else', 'equal', 'less than', 'repeat' and etc. Knowing these words is almost mandatory to code. 

Our new 'if' instruction is telling the computer to test if the speed is less than 10km/h. If so, then increase the speed.   

That will allow John to start at 0 and increase his speed until 10 km/h.  No more speed increases for John after that. 

Is John getting out of this alive ? Not quiet yet. We solve one problem, now he will not be a Ferrari. He is running at 10 km/h but the repeat instruction will make John run forever.  

John is still a dead man like Pheidippides, sent from the battlefield of Marathon to Athens to announce that the Persians had been defeated in battle.

Can we fix again and for godsake keep John alive ? Let's say John will run for 20 mins ? 

```
step,
increase speed only if speed is less than 10 km/h 
repeat until time is equal 20 mins. 
stop
```

Now, John is smiling at you while he passes running by! He started at 0, increased his speed until 10 km/h (running speed!), then after 20 mins he will stop. 

This small alegory shows the basic principle of software development. We need a language, a story and a computer. 

Then, we may kill some Johns along the way to proof our story with basic instructions.  After some tries, we eventually get it right.  

The last and important detail. There are infinite ways to tell a story. The art of storytelling could turn a program into a poem,  a novel or a greek tragedy. Every Developer is different. 



> Curiosities :

Every computer language is different. In that sense, they are like the English and French comparison. Some program written in the JavaScript language will barely be understood by a COBOL language Developer.  

Every computer language has a set of reserved words, or its vocabulary. Some have 50, others have 400 keywords. The number of words do not imply power in the same way you can tell French is not more powerful than English. They all tells a story. 

Is there any similar computer languages like Portuguese and Spanish ? Yes, languages like Perl and PHP are similar, you almost can jump from one to the other. 




