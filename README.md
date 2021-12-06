## **Design Patterns Used**

### 1) Iterator

Iterator lets us traverse elements of a collection without exposing its underlying representation (list, stack, tree, etc.). Take each category&#39;s item and map it to the item list.

### 2) Chain of Responsibility

Chain of Responsibility lets us pass requests along a chain of handlers. Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain. In our problem, we are reading the input file first, map each category&#39;s item to the item list, then check if the order quantity exceeds the individual item limit, then check if it exceeds the category limit, then generate order placement with a success or failure result. All these things process in a chain of Handlers. 
<br/>
<br/>

## **Class Diagram** 

![abhishek_project_class_diagram_simple](https://user-images.githubusercontent.com/25710427/144781094-dcafb68d-b6f8-4a20-9d80-59ad87c6bd9e.png) 
<br/>
<br/>


## **Screenshots** 


<br/>
<br/>


## **How to Build and Run**

We can "Edit configurations" while "Run"ning the code through CLI Arguments of our Application.

<img width="506" alt="1" src="https://user-images.githubusercontent.com/25710427/144780655-5a100d9c-7b1c-4d24-86a6-f4b48a627066.png">


Or, we can run the following command by replacing the name of input files

java -cp Abhishek-CMPE202.jar MainClass "Input1 - Sheet1.csv"
