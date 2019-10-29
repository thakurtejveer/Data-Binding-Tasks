#Scenario 1

In this scenario, create a component, say component1. A user should be able to enter text in the
.html template file of the component. The component should print out the user text to console.
Create the component in a scenario1 folder of your project. All files of the component should be
inside the scenario1 folder.

PS- Taking input in form, using tempelate reference variable, entered value is getting printed on console.


#Scenario 2


In this scenario, create a component, say component1. A user should be able to enter text in the
.html template file of the component. The template should display the text as the user types.
Create the task in a scenario2 folder of your project. All files of the component should be inside the
scenario2 folder.


PS- Taking input in form, using tempelate reference variable, entered value is getting printed on view. 
	1- by creating click event
	2- by printing live (using two way binding)


#Scenario 3

In this scenario, create two components, say component1 and component2. Component1 is a
parent of component2.
A user should be able to enter text in the .html template file of component1. The template of
component2 should display the text.
Create the task in a scenario3 folder of your project. All files of the components should be inside the
scenario3 folder.

PS- Taking input in form in .html template of component1 and component2 is displaying the value.
	We are doing component interaction here, parent to child.


#Scenario 4

In this scenario, create two components, say component1 and component2. Component1 is a
parent of component2.
A user should be able to enter text in the .html template file of component2. The template of
component1 should display the text.
Create the task in a scenario4 folder of your project. All files of the components should be inside the
scenario4 folder.


PS- Taking input in form in .html template of component2 and component1 is displaying the value.
	1-We are doing component interaction here, Child to parent.
	2-Task done by using Event Emitting.



#Scenario 5


In this scenario, create three components, say component1, component2, and component3.
Component1 is a parent of component2, and component2 is a parent of component3.

A user should be able to enter text in the .html template file of component3. The template of
component1 (grandparent) should display the text.
Create the task in a scenario5 folder of your project. All files of the components should be inside the
scenario5 folder.

PS- 	Taking input in component3.
	Using template reference variable and Event emitting, component2 is cathing the emitted event and re emitting it which is later cathed by component 1.
And component 1 later on displaying it.



#Scenario 6



In this scenario, create three components, say component1, component2, and component3.
Component1 is a parent of both component2 and component3.
A user should be able to enter text in the .html template file of component1. The template of
component3 (sibling) should display the text.
Create the task in a scenario6 folder of your project. All files of the components should be inside the
scenario6 folder.



PS-	1-.html tempate of Component1 is taking input in form.
	2- Tempelate reference variable is used.
	3- component2 and componet3 are siblings and child of component1.
	4- Input is being displayed by component3 and Simple "Hey" text is displayed from  		   component2 to verify that it is the child of component1.




















