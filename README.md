# Enumerations (enum) and Composition - C#

#### This exercise is based on the <a href="https://www.udemy.com/course/programacao-orientada-a-objetos-csharp/?couponCode=MT260714G2">"C# COMPLETO Programação Orientada a Objetos + Projetos"</a> course.

### <ins>Work with Enum</ins>

#### What is an enumeration or enum? A: It is a special type used to literally specify a set of related constants.

### <ins>Exercise01</ins>

#### Read the data of an employee with N contracts (N provided by the user). Then, ask the user to enter a month and display the employee's salary for that month, as shown in the example.

#### Example:

Enter department's name: <strong>Design</strong><br>
Enter worker data:<br>
Name: <strong>Alex</strong><br>
Level (Junior/MidLevel/Senior): <strong>MidLevel</strong><br>
Base salary: <strong>1200.00</strong><br>
How many contracts to this worker? <strong>3</strong><br>
Enter #1 contract data:<br>
Date (DD/MM/YYYY): <strong>20/08/2018</strong><br>
Value per hour: <strong>50.00</strong><br>
Duration (hours): <strong>20</strong><br>
Enter #2 contract data:<br>
Date (DD/MM/YYYY): <strong>13/06/2018</strong><br>
Value per hour: <strong>30.00</strong><br>
Duration (hours): <strong>18</strong><br>
Enter #3 contract data:<br>
Date (DD/MM/YYYY): <strong>25/08/2018</strong><br>
Value per hour: <strong>80.00</strong><br>
Duration (hours): <strong>10</strong><br>

Enter month and year to calculate income (MM/YYYY): <strong>08/2018</strong><br>
Name: Alex<br>
Department: Design<br>
Income for 08/2018: 3000.00

### <ins>Exercise02</ins>

#### Manually instantiate the objects shown below and display them in the terminal, as demonstrated in the example.

#### UML:

<img src="Images\UML Exercise02.png" alt= "UML Exercise02">

#### Example:

```
Traveling to New Zeland
12 Likes - 21/06/2018 13:05:44
I'm going to visit this wonderful country!
Comments:
Have a nice trip!
Wow that's awesome!

Good night guys
5 Likes - 28/07/2018 23:14:19
See you tomorrow
Comments:
Good night
May the Force be with you
```

### <ins>Exercise03</ins>

#### Read the data for an order containing N items (N provided by the user). Then, display a summary of the order as shown in the example. Note: the order timestamp must be the system time: DateTime.Now.

#### UML:
<img src="Images\UML Exercise03.png" alt="UML Exercise03">

#### Example:

Enter cliente data:<br>
Name: <strong>Alex Green</strong><br>
Email: <strong>alex@gmail.com</strong><br>
Birth date (DD/MM/YYYY): <strong>15/03/1985</strong><br>
Enter order data:<br>
Status: <strong>Processing</strong><br>
How many items to this order? <strong>2</strong><br>
Enter #1 item data:<br>
Product name: <strong>TV</strong><br>
Product price: <strong>1000.00</strong><br>
Quantity: <strong>1</strong><br>
Enter #2 item data:<br>
Product name: <strong>Mouse</strong><br>
Product price: <strong>40.00</strong><br>
Quantity: <strong>2</strong><br>

ORDER SUMMARY:<br>
Order moment: 20/04/2018 11:25:09<br>
Order status: Processing<br>
Client: Alex Green (15/03/1985) - alex@gmail.com<br>
Order items:<br>
TV, $1000.00, Quantity: 1, Subtotal: $1000.00<br>
Mouse, $40.00, Quantity: 2, Subtotal: $80.00<br>
Total price: $1080.00