**Design Patterns Used**

1) Iterator

Iterator lets us traverse elements of a collection without exposing its underlying representation (list, stack, tree, etc.). Take each category&#39;s item and map it to the item list.

2) Chain of Responsibility

Chain of Responsibility lets us pass requests along a chain of handlers. Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain. In our problem, we are reading the input file first, map each category&#39;s item to the item list, then check if the order quantity exceeds the individual item limit, then check if it exceeds the category limit, then generate order placement with a success or failure result. All these things process in a chain of Handlers.

**Class Diagram**

\&lt;Simple Class Diagram Image\&gt;

**Screenshots**

\&lt;3 Images\&gt;

**How to Build and Run**

We can &#39;Edit configurations&#39; while &#39;Run&#39;ning the code through CLI Arguments of our Application.

\&lt;Image\&gt;

Or, we can run the following command by replacing the name of input files

java -cp Abhishek-CMPE202.jar MainClass &quot;Input1 - Sheet1.csv&quot;
