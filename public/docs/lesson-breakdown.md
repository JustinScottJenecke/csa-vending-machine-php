# PHP Vending Machine Walkthrough:

## 0 : <u>Setup:</u>
<ol>
    <li>Initial stage</li>
    <li>Fork repo and clone code locally</li>
</ol>

## 1 : <u>Superglobals:</u>
<ol>
    <li>GET</li>
        - Insert funds into machine
    <li>POST</li>
        - Create new item and add it to vending machine display <br>
        - Delete item when clicked on to simulate purchase 
    <li>SESSION</li>
        - Talk abbout the concept of state <br>
        - SESSION variable as datastore or state of app (items)
</ol>

## 2 : <u>Functions:</u>
<ol>
    <li>Abstract business logic into functions</li>
    <li>Abstract functions into include files</li>
    <li>Redirecting to and from process files</li>
</ol>


## 3 : <u>OOP - Basics:</u>
<ol>
    <li>Fundamentals of Classes (instance variables, methods, constructor)</li>
    <li>POJO class vs Model class</li>
    <li>Abstract all business logic to Vending Machine class</li>
    <li>Abstract all model data to Product Class</li>
</ol>

## 4 : <u>OOP - Fundamentals:</u>
<ol>
    <li>Pillars of OOP (Abstraction, Encapsulation, Inheritence, Polymorphism)</li>
    <li>Access Modifiers</li>
    <li>Getters & Setters</li>
    <li>Inheritence</li>
    <li>Static Methods</li>
    <li>Implement general class and specialization classes for different Products</li>
</ol>


## 5 : <u>File Systems:</u>
<ol>
    <li>Explain persistent storage, role of "Client - Server - Database" in a diagram format</li>
    <li>Explain CRUD design pattern</li>
    <li>Load and display Assoc Array of products into vending machine</li>
    <li>Remove item from state of file cached on Server and update the file </li>
    <li>Explain Assoc Array vs Standard Object vs Model Object</li>
    <li>Implement Serialize and de-Serialize functions in Class</li>
</ol>

## 6 : <u>Composer:</u>
<ol>
    <li>What is a dependency and why use a dependancy manager</li>
    <li>PHP Mailer</li>
</ol>