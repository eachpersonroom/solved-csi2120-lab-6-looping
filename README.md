Download Link: https://assignmentchef.com/product/solved-csi2120-lab-6-looping
<br>
Exercise 1. Looping

countDown(N)- repeat, writeln(N), N is N-1, N0, !.Test the above predicate with the query – countDown(5).. Explain what happens and why Find a solution to the problem that you have observed.

Exercise 2. Chemical ElementsGiven the following database of chemical elements and their symbols in the periodic table. For example

element(chlorine,’Cl’).element(helium,’He’).element(hydrogen,’H’).element(nitrogen,’N’).element(oxygen,’O’).Write an interactive Prolog program for the user to enter a symbol and the program prints the name of the corresponding chemical element. If the symbol is not in the database, the program should exit otherwise loop again. Example

Elements in the Periodic TableSymbol to look-up ‘O’.O is the symbol for oxygenSymbol to look-up ‘He’.He is the symbol for heliumSymbol to look-up ‘K’.Don’t know the symbol KExiting.Exercise 3 Cut-FailConsider the following database

canalOpen( saturday ).canalOpen( monday ).canalOpen( tuesday ).

raining( saturday ).

melting( saturday ).melting( sunday ).melting( monday ).Write a Prolog predicate to return true if it is advisable to go to winterlude. It should return true if the Canal is open, it is not raining and not melting You must use cut-fail in your solution and your predicate should work as follows

– winterlude(X).X = tuesday.Hint You will need to add an intermediate predicate to deal with negation.Exercise 4. List ProcessingWrite a Prolog predicate secondLast that finds the second last element of a list.

– secondLast(X,[7,abc,foo,x,9,12]).X = 9Exercise 5 and Quiz ListsPlease hand-in the answer to this question on Virtual Campus during your lab session but at the latest by Friday 600pm! Remember, your submission will only count if you have signed the lab attendance sheet.Write a predicate which processes a list of numbers by adding up every second number. The predicate is to work as shown below. (Note that you are not asked to check the input to be a valid list of numbers but can simply assume that your predicate always receive list of numbers).

– addSecond([1,3,5,4],S).S = 7.

– addSecond([1,3,5],S).S = 3.

– addSecond([1,3],S).S = 3.

– addSecond([1],S).S = 0.

– addSecond([1,3,5],3).true.