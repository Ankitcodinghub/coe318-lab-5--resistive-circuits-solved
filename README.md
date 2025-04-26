# coe318-lab-5--resistive-circuits-solved
**TO GET THIS SOLUTION VISIT:** [COE318 Lab 5- Resistive Circuits Solved](https://www.ankitcodinghub.com/product/coe318-lab-5-resistive-circuits-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126714&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COE318 Lab 5- Resistive Circuits Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Objectives

● Implement a Node class.

● Implement a Circuit class.

● Implement a Resistor class.

● Do a tutorial on debugging.

Overview

In this lab, you will model an electric circuit composed of an arbitrary number of resistors. Each of the two ends of a resistor will be connected to a Node. Each Resistor will be added to a Circuit at the time the resistor is created (i.e. within the constructor.)

Introduction to IllegalArgumentException()

What can a programmer do when parameters passed to a constructor make no sense?

For example, in the Lab 3 Counter class, a modulus anything less than 2 would be senseless.

Construction of such “senseless” objects can be aborted in the constructor by throwing an Exception.

We will discuss Exceptions in much greater detail later in the course. For now all you need to know is that constructors should use if-statements to detect illegal parameters and, if detected, a new IllegalArgumentException() should be thrown.

This general technique is illustrated below where (for reasons that don’t matter) a constructor of an E object must be passed an integer that cannot be negative and s String that cannot be null.

public class E {

public E(int i,

String s) { if (i &lt;

0) {

throw new IllegalArgumentException(“i can’t be negative”);

} if(s == null) { throw new IllegalArgumentException(“s can’t be null”);

}

}

In the classes you will write in this lab it is up to you to determine if it is possible for senseless parameters to be given to the constructor. If so, you have to detect them and throw an IllegalArgumentException.

The Node Class

The Node class will consist of instance variables, a constructor and a toString() method.

Each node has a unique identifying number (a non-negative integer). The first Node created will have an id number of 0 (zero). The next one will have an id number of 1, the next an id number of 2, and so on. The toString()method should return the identifying number as a string.

Hint: in addition to an ordinary instance variable containing the identifying number of the Node, you will also need a static variable that indicates the identifying number of the next Node that is constructed.

The constructor takes no arguments.

Source Code

No source code template is given for this lab. You will have to write the code from scratch.

Step 1: Create a Netbeans Project and Node class

1. Create a Netbeans project called Circuit.

2. Create a Java file (class library type) called Node in package coe318.lab6

3. Determine your instance variables and implement the constructor.

4. Implement the toString() method.

Step 2: Implement the Resistor class

The Resistor class has a constructor with the following signature:

public Resistor(double resistance, Node node1, Node node2)

where resistance is the resistance in Ohms and the nodes node1 and node2 are the two Nodes the resistor is connected to. (Note that this means the Node objects have to be created before the Resistor.) Each Resistor should also have a unique identifying number. The first resistor should have the number 1, the second, number 2, etc.

Two methods are required:

● public Node [] getNodes() and ● public String toString().

The getNodes() method should return an array of Nodes where the first element is the first Node specified in the constructor and the second element is the second specified Node.

The toString() method should return a string with 4 components separated by spaces. The first component is the letter ‘R’ followed by the resistor’s id number; the second and third components specify the nodes it is connected to; the fourth component gives the resistance. For example, a 30Ω resistor whose id number is 5 connected between nodes 6 and 9 should have the string representation

R5 6 9 30.

1. Create a Java file (class library type) called Resistor.

2. Implement the constructor and getNodes and toString methods.

3. Consider the possibility of illegal arguments to the constructor, detect them and throw an exception if one is found.

Step 3: Implement the Circuit Class

The Circuit class has a special feature: it is a singleton, which means that there is only one Circuit object. This behavior is achieved with the following code:

private static Circuit instance =

null; public static Circuit getInstance() {

if (instance == null) { instance = new

Circuit();

} return instance; } private Circuit() {} //Yes, the constructor is PRIVATE!

In any other class, you can obtain the Circuit object with the code:

Circuit cir = Circuit.getInstance();

The methods required for Circuit are add(Resistor r) and toString(). The add method should add the resistor to the collection of resistors in the circuit (hint: use an ArrayList instance variable). For example, the Resistor constructor should add the newly constructed Resistor (this) to the Circuit instance.

The toString() method should return a string composed on the String representations of each resistor separated by newline characters.

Step 4: Recommended- learn how to use the debugger

Step 5: Submit your lab

Please zip up your NetBeans project containing all source files and submit to the respective assignment folder on D2L.
