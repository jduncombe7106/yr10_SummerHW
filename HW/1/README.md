#Exam Questions <img src="../../Resources/exam.png" width=50px alt="Tick Sheet">

##Instructions
Edit this document and answer the questions in the sections surrounded by ```.

There are **24** marks available and are awarded grades as follows:

|Score|Grade|
|-----|-----|
|<3|U|
|5+|G|
|7+|F|
|9+|E|
|11+|D|
|13+|C|
|15+|B|
|17+|A|
|19+|A*|


##Data Representation

###1 - Why do we represent data using binary when using computers *(1 mark)*

```
it is simple and easy to read
```
###2 - How would we represent the number 147 in binary? *(1 mark)*
```
10010011
```
###3 - Can you convert the hexadecimal number **b5** to denary, there is a mark for you working. *(2 marks)*
```
b=14 +4 = 1110 0100
```
###4 - Here is a function written is **pseudocode**.
```
FUNCTION validUser (users , user)
    FOR x <-1 to LEN(users)
        IF users[x] = user
			RETURN True
		ENDIF
	ENDFOR
	RETURN False
ENDFUNCTION
```

(a) What type of data is **users**? **(1 mark)**
```
answer here
```

(b) What type of data is returned by this function? **(1 mark)**
```
answer here
```

##Errors
###6 - This program is supposed to find the mean of a list of numbers and print it out for the user:
```
line1:		tot <- 0
line2:		nums <- [1,6,4,2,5,3]
line3:		FOR x <- to LEN(nums)
line4:			tot <- nums[x]
line5:		ENDFOR
line6:		mean <- tot
line7:		OUTPT mean
```

(a) On which line is there a **syntax** error? **(1 mark)**
```
7
```

(b) What is meant by a **syntax** error? **(1 mark)**
```
where the code does not make sense to the computer
```

(c) Identify a logical error in the program and suggest how this might be fixed. **(2 marks)**
```
answer here
```

(d) Describe and give an example of the 3rd kind of programming error. **(2 marks)**
```
run time error
```

##Algortithms
###7 - Write an **algorithm** that if given a list of numbers could find the largest. Try to use [pseudocode](http://filestore2.aqa.org.uk/subjects/AQA-GCSE-COMPSCI-W-TRB-PSEU.PDF).
```
answer here
```

##Networking
###8 - Research the following methods (*topologies*) for connecting devices to a network. In each case give a description and at least 1 advantage and 1 disadvantage.

**Bus Topology (6 marks)**
```
Describe:A bus topology is a type of network setup where each computer and network device is connected to a single cable or backbone.

Advantages:easy to set up and is  cheap

Disadvantages: There is a limit on central cable length and number of nodes that can be connected
```

**Ring Topology (6 marks)**
```
Describe:In Ring Topology, all the nodes are connected to each-other in such a way that they make a closed loop. Each workstation is connected to two other components on either side, and it communicates with these two adjacent neighbors. 

Advantages:Each computer has equal access to resources,  Additional components do not affect the performance of network.

Disadvantages:If one workstation or port goes down, the entire network gets affected, Network is highly dependent on the wire which connects different components.
```

**Star Topology (6 marks)**
```
Describe:In Star topology, all the components of network are connected to the central device called “hub” which may be a hub, a router or a switch. Unlike Bus topology, where nodes were connected to central cable, all the workstations are connected to central device with a point-to-point connection.

Advantages:Centralized management helps in monitoring the network.

Disadvantages: Too much dependency on central device has its own drawbacks. If it fails whole network goes down.
```
