# Budgety
<strong>A simple budget app made using HTML5, CSS3 &amp; JavaScript. The app can be used [here](https://ravi8972.github.io/Budget-checker/).</strong>

### How to use Budgety
- Plus sign (+) signifies "Income" & the Minus sign (-) signifies "Expense"
- After choosing +/- (*i.e., income/expense*), add the description. 
  - Example description for income is "Salary" 
  - Example description for expense is "Rent", "Bills", etc
- After adding the description, you can add the value (has to be more than 0) and then press Enter &#9166; to add the entry into the respective list
- To delete an existing item in either the income/expense list, simply hover over the item in the respective list and press &#8855;



### What did I learn?
Some of the concepts I've garnered/understood while working on this project are the following:
- Familiarized myself with Module Pattern, Encapsulation & Separation of Concerns
  - Module Pattern enforces the idea of "A System/App is a combination of many Parts/Modules"
  - Using Immediately Invoked Function Expressions (IIFEs), we are able to achieve Encapsulation and also data privacy
  - Module Pattern also encourages Separation of Concerns, where one Controller for a certain module only handles the work/functionality related to that particular module only
- JavaScript Concepts:
  - Enforcement of core concepts of the language like IIFEs & Closures
  - Usage of general functions like <code>map()</code>, <code>splice()</code>, <code>forEach()</code>, etc, along with the usage of string manipulation functions like <code>strip()</code>, <code>substr()</code>, <code>replace()</code>, <code>matches()</code>, etc
  - Usage of Function Constructors to create objects. Using the <code>prototype</code> property to add methods to the predefined constructors.
  - DOM Access & Manipulation:
    - A thorough understanding of Event Bubbling, Target Element & Event Delegation
    - Understanding of certain events like <code>keypress</code>, <code>change</code>, <code>click</code>, etc
    - Understanding the usage of certain methods like <code>innerAdjacentHTML()</code>, <code>removeChild()</code>, <code>querySelectorAll()</code>, etc
    - Understanding of <code>parentNode</code> property
    - What a <code>NodeList</code> is and how to traverse it
  - The <code>Date()</code> Constructor and its uses
