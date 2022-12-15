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

## 3/5 - Build a decision tree.

Decision trees are a popular statistical modeling technique that finds hidden patterns in the data. Let's build one!

### Activity

1. ```Find``` the **Operators** panel on te left.
2. ```Open``` the folder **Modeling**, **Predictive**, and finally **Trees**.
3. ```Drag``` in the **Decision Tree** operator and drop it after **Retrieve Titanic Training**.

### Explanation

Good, we now have the operator in the process but we still need to connect the two operations and define what we want to see as output before we can run it.

## 4/5 - Connect & execute.

The **Decision Tree** operator will build a Decision Tree for us based on our Titanic Training data. We still need to connect these operators together to build a Process, though:

### Activity

1. ```Connect``` the output port ("out") of **Retrieve Titanic Training** with the input port ("tra" for "training") of the **Decision Tree**. You can click on the ports, or you can drag on them!
2. ```Connect```  the first output ("mod") of the **Decision Tree** with the result port ("res") on the right side of the of the **Process** panel.
3. ``Press`` the > **Run** button in the toolbar to execute the process.

### Explanation

Great job! Your process should now be complete and deliver a decision tree model, which explains to you what most of the survivors amd most of the victims had in common. Read more explanation on [operator ports]() and [decision trees]().

## 5/5 - Congratulations!

Great - you just have built your first machine learning model. This was not hard, was it? You now know how to load data, add a machine learning model to the process, and execute both steps.

### Explanation

From our resulting decision-tree, we can clearly see that survival was not coincidental at all. In fact, it tells us that as a female passenger, with a small fanmily, you were really lucky - at least if you were holding an expensive ticket!

These tutorials have only shown you the tip of the iceberg of what you can do with RapidMiner. To keep learning and become a RapidMiner Master, start the next tutorial. Welcome again to RapidMiner! 

# Next Tutorial

## 1/6 Importing Data into RapidMiner

Getting your data into RapidMiner is often the first task you will need to complete your analysis. In this tutorial, you will learn how to import files into the central storage of RapidMiner, called the Repository. We will continue to use use data describing the Titanic accident, but this time it will be imported from an Excel file. 

### Explanation

We will now go through the most important steps of building analytical processes starting with data import. In later tutorials, we will cover data preparation and modeling. We also will discuss some of the steps you saw so far in more detail.


More ...
