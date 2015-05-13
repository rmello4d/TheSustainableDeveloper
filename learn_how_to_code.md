# Don't be afraid

This chapter is for non-coders, so feel free to step to the next if you are a developer. 

Here a simple analogy to understand how a developer mind works while coding. 

The basic principle is language. Developers need to know a computer language. You mean, like English or French ? Not quiet. 

Computer languages are minimal. The brain of a computer understand just a few words. 

Lets say you want to make your computer to simulate a person (John) 'running'. The problem is, the computer vocabulary does not have 'run' as a word. 

How Developers put John to run ? 

A Developer knows that 'step' and 'speed' are words available in the computer's brain. Great! He tells the computer : 

```
step,
step,
increase speed,
repeat 
```
*ps. repeat is a magical word in the computer vocabulary. Once the computer see the word repeat, it will go back to the first step and run the pile of instructions again. Notice that if we run the pile again, it will end on a reapeat, creating a perpetual loop. *


As you probably noticed with tears, by now, John is dead. Our Developer told the computer to increase the speed in every repeat. Since we are in a perpetual loop, the speed will be higher and higher. Hypothetically John could be running at 300 km/h in the computer. 

To get more real, our Developer will go back and 'fix' the instructions to avoid the problem of the unlimited speed:

```
step,
step,
increase speed only if speed is less than 10 km/h 
repeat 
```

These instructions are not easy to grasp at first. It looked easy but now the instruction to increase speed turn to be a bit more complicated. 

This fix is telling the computer to increase the speed **only** if we are running at less than 10km/h. That will allow John to start at 0 and increase his speed until 10 km/h.  No more speed increases for John after that. 

Is John getting out of this alive ? Not quiet.  As you can see, the repeat instruction will make John run forever at 10km/h. John is still a dead man.

Lets fix again and say John will run for 20 mins.

```
step,
step,
increase speed only if speed is less than 10 km/h 
repeat until time is equal 20 mins. 
```

John is now smiling at you while he passees running by...

This small alegory shows the basic principle of software development. You need a language, a story and a computer. In other words, we use a reduced language to tell a story to a computer. 
