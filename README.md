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
### Outputs

Order Success for Input-1
<img width="818" alt="O1" src="https://user-images.githubusercontent.com/25710427/144792168-60296133-dadf-4a6b-a4ac-150bcdc4993e.png"><br/>

Failed Order for Input-2 
<img width="824" alt="O2" src="https://user-images.githubusercontent.com/25710427/144792181-449c7df2-a128-43a1-837f-be78dfaaef1e.png"><br/>

Order Success for Input-3
<img width="817" alt="O3" src="https://user-images.githubusercontent.com/25710427/144792191-e8cae91b-df0b-4f18-a412-639c9ad979c5.png"><br/><br/>



### Intermediate



<br/>
<br/>


## **How to Build and Run**

We can "Edit configurations" while "Run"ning the code through CLI Arguments of our Application.
<br/>

Or, we can run give the file name through terminal input as following command by replacing the name of input files

#### java -cp .\abishekProject.jar MainClass "Input1 - Sheet1.csv"
#### java -cp .\abishekProject.jar MainClass "Input2 - Sheet1.csv"
#### java -cp .\abishekProject.jar MainClass "Input3 - Sheet1.csv"

