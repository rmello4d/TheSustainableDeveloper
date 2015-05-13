# Don't be afraid

This chapter is for non-coders, so feel free to step to the next chapter if you are a developer. 

The goal is to understand the idea of coding and how we create a set of instructions to tell a story.   

First, developers need to know a computer language. Something like English or French ? Yes but not quiet. 

Computer languages are minimal. Think about a language with only 50 reserved words for example, which is the real case of a language called JAVA. 

Lets say we want the computer to simulate a 'running' person (John).  The problem is, the computer vocabulary does not have 'run' as a word. 

How Developers put John to run ? 

Lets assume that 'step' and 'speed' are words available in our computer's language. We get these 2 words and tell the computer the following instructions : 

```
step,
increase speed,
repeat           
```
*ps. repeat is a 'magical' word in the computer vocabulary. Once the computer see the word repeat, it will go back to the first step and run the batch of instructions again. Notice that, running the batch again means that we will end on another reapeat, creating a perpetual loop. *

As you probably noticed with tears, by now, John is dead. We told the computer to increase the speed in every repeat. John will start at 0 and increase his speed until he is a Ferrari, then a rocket, then...kaboom!

Since we are in a perpetual loop created by the repeat instruction, the speed will keep growing higher and higher. 

To get more real, we will go back and 'fix' the instructions to avoid this problem. Let's give 10 km/h as a speed limit for John: 

```
step,
if speed is less than 10 km/h, then increase speed  
repeat 
```

Wait a minute. What is that long instruction ? Computers have a great ability to compute and to be logical. Computer Languages exploit that by supplying us with a series of special words: 

'if', 'then', 'else', 'equal', 'less than', 'repeat' and etc. 

Knowing these words is almost mandatory to code.

Our new 'if' instruction is telling the computer to test if the speed is less than 10km/h. If so, then increase the speed.   

That will allow John to start at 0 and increase his speed until 10 km/h.  No more speed increases for John after that. 

Is John getting out of this alive ? Not quiet yet. We solve one problem, now he will not be a Ferrari. He is now running at 10 km/h, which is a good running speed. 

The problem now is that John will run forever. He is like Pheidippides in the Marathon Batle. Pheidippidis run from the battlefield of Marathon to Athens to announce that the Persians had been defeated. Then, kaboom! 
Can we fix again and for Godsake keep John alive ? Let's say John will run for 20 mins ? 

```
step,
if speed is less than 10 km/h, then increase speed 
repeat until time is equal 20 mins. 
stop
```

Now, John is smiling at you while he passes running by! 

He started at 0 by stepping and increasing his speed progressively until 10 km/h. After 20 mins running he will stop. 

This small alegory shows the basic principle of software development. We need to tell a story to a computer using a short language and a few 'magical' words.  

We may kill some Johns along the way to proof our story. After some tries, we hopefully get it right.  

The last and important detail. There are infinite ways to tell a story. The art of storytelling could turn a program into a poem,  a novel or a greek tragedy. Every Developer is different. 



> Curiosities :

Every computer language is different, like the English and French comparison. Having said that, a program written in one language could be hard to understand, if the developer does not know that language. 

Every computer language has a set of reserved words. Some have 50 others have 400 keywords. The number of words does not mean power, both languages are able to tell a story. 

Is there similar computer languages like Portuguese and Spanish ? Yes, languages like Perl and PHP are similar, you can jump from one to the other and quiet understand what they are saying. 




