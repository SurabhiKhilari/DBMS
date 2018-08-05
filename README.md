# DBMS
Database Management System: Tire Management System

What does the project do?
	The Project “Tire Shop Management” deals with the automation of Tyre business and services. This software will help salespersons in managing the various types of Records pertaining to his/her customer. The product will help the user to work in a highly effective and efficient environment. The salespersons have been recording the customer information in the past and even in the present through their personal manual efforts. And indeed, it consumes their considerable time and energy that could be utilized in the better productive activities. Apart from that, with increasing customer Strength, the task of managing information of each individual customer is indeed a cumbersome task. There is a lot of reason for the introduction of this project

The information retrieval is one of the foremost problems. It is very difficult to gather the overall performance reports of the customer. Large records-books have to be maintained where relevant and irrelevant information has to be stored which is very untidy and clumsy process Usualy, they lack efficiency. Less efficiency has a great impact on the productivity of any human being keeping the data up-to-date.

This software helps its user to manage sales in a systematic way and constant update of their stock time to time using Java and Mongodb.

Why is it useful?
Tyre requirements  and services are ever increasing in demand as urbanization is increasing. On an average there are two cars per family. Hence to manage these needs and satisfy customers there has been a recent rise in the number of tyre shops. Our mini-project “Tyre Shop Management” caters to the database needs that a tyre shop requires. The user can update,delete and view entries of their customers and type of tyres.
Our project has a big scope to do.

 We can:
1. Store how many products are sold.
2. Store products and their prices and with other information.
3. Store the informaton about Customers.
4. Can view a specific product and update it.
5. Change the Graphical User Interface of the system.
6.Can give specific remarks about the customers.

We can’t:
1. Calculate of the salaries of the employees.
2. Calculate the expanses on the product.

How can users get started with the project?
	Technologies used: 	1) Java
				2) MongoDB
				3) NetBeans
- Create a NoSQL database for the tire shop.
- Create the front end using NetBeans.
- All the front end forms’ fields should be then validated using Java.
- Using the appropriate jar files, connect NetBeans’ frontend to MongoDB.
Sources to get help?
1)	Text Validation:
Firstly import following package-
import java.util.regex.Matcher;
import java.util.regex.Pattern;
Double click on submit button and write following code-
{
String emailID = txtEmail.getText();
String emailRE = "^[_A-Za-z0-9-]+(\\.[_A-Za-z0-9-]+)*@[A-Za-z0-9-]+
(\\.[A-Za-z0-9-]+)*(\\.[A-Za-z]{2,})$" ;
Boolean flag = emailID.matches(emailRE);
if (flag)
System. out.println ("EMAIL VALID")
else
System. out.println("EMAIL INVALID")
}
Instead of System. out.println you can use JOptionPane for displaying error message.

----You can also refer following URL for understanding Regular Expression notations.
REFERENCE:
http://www.ocpsoft.org/opensource/guide-to-regular-expressions-in-java-part-1/#section-3

2)	http://howtodoinjava.com/apache-commons/create-pdf-files-in-java-itext-tutorial/
3)	Sai enterprises vdo
http://www.justdial.com/Pune/Sai-Enterprises-%3Cnear%3E-Near-Shiv-Sagar-Restaurant-Baner/020PXX20-XX20-130813144757-K2N5_BZDET#

4)	billing software-basics
http://malargroups.com/tyre-shop-invoice-softwaretyre-shop-billing-software/

http://www.mamsoftware.com/en/autopart-tyres

