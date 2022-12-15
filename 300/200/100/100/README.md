# 100 - Guided Tour

## 1/5 - Welcome to RapidMiner.

RapidMiner Studio has a lot of features to offer. In the next few minutes, you will learn how you can use RapidMiner Studio to perform basic data science techniques, such as: accessing data, transforming data, and building statistical models. We will use data describing the Titanic passengers.

### Explanation

Each tutorial is broken into several steps to teach you the basics of RapidMiner Studio. Each step lists specific actions to perform, plus an explanation of why those actions matter. Notice the dotted-line preview in the **Process** Panel; this shows you the process you will be building in that tutorial.

## 2/5 - Retrieve data.

Let's start by retrieving some data about the Titanic passengers.

### Activity

1. ```Find``` the **Repository** panel on the left of the screen.
2. ```Open``` the folders **Samples** and then **data**.
3. ```Drag``` the **Titanic Training** dataset and ```drop``` it in the **Process** panel in the middle of the screen.

### Explanation

Good job! You have just added your first operator to RapidMiner Studio, namely the **Retrieve** Operator. Operators perform actions: in this case, it retrieves data from the **Repository**. Now let's see what you can do with it!

## 3/5 - Building your first process.

As a RapidMiner analyst, you create processes by adding and connecting operators. Operators are connected together via their Ports:

### Activity

1. Connect the output port ("out") of **Retrieve Titanic Training** with the result port ("res") on the right side of the **Process** panel.
2. Make the connection either by ```dragging a line``` between the ports, or by first ```clicking``` on one port and then the other port.

### Explanation

Excellent! You have built your first process in RapidMiner Studio. We can now look at the output of the Retrieve operator. Whenever you want to see the output of an operator, make sure it is connected to the 'res' port.

## 4/5 - Running processes.

After we have connected the elements of our process, we can hit the 'Run' button to view the output.

### Activity

1. ```Click``` > **Run** ```(top left)``` to execute the process.

### Explanation

Nice! You have run your first process in RapidMiner Studio. When you click "Run", the operators in your process will perform their actions. RapidMiner executes the process and shows the data connected to the result port. In the center of the **Results** view, you can see our raw data about the Titanic passengers such as their age. On the **Statistics** tab we get a statistics summary, which provides useful information; for example, 349 passengers survived the Titanic accident. If you get different results, please make sure you dragged in the correct dataset: **Titanic Training**.

## 5/5 - Congratulations - Halfway there!

Well done - you just mastered your first tutorial! To quickly review:

- Operators perform individual actions.
- You can connect operators to gether to build a Process.
- To see the output of an operator, connect it to the 'res' port.
- Running the process performs all operators and automatically shows the results.

### Explanation

To become a true master move on to the next tutorial below.

# Next Tutorial

## 1/5 - Let's do some data science.

In the last tutorial, we loaded a dataset and ran a process. We found out that 349 passengers survived the Titanic accident. Let's build a Process to see if those survivors have something in common or not.

## 2/5 - Retrieve the Titanic Training data.

Load the Titanic Training data.

### Activity

1. ```Drag``` the **Titanic Training** data from the **Samples** repository into the **Process** panel.

### Explanation

You have defined the first operation of your process. Now we will learn how easy it is to build a machine learning model on this data.

More ...
