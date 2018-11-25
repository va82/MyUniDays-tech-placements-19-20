# MyUniDays-tech-placements-19-20

In the beginning, when customers are accessing the page, they are asked if they would like to shop or not.
According to their answer the program starts.

 --If the answer is yes they are requested to enter the item they want from a list A,B,C,D,E. If the item entered is right (uppercase), then they are asked if they would like to shop more. The answer is checked whether it is yes or no or something else. While the answer is yes, they must enter the item they want. An array is created including the items of the customers.
     -If the answer is no, then all the items that customers want to shop, are added in the basket. A relevant message shows all the items that customers selected. Moreover, a method to calculate the total price is called by passing through the array of the items.
     -Before starting the calculations, the array is sorted for a more convenient result. The count variable was set to be 0.
     
*Thereafter, the array is checked whether it contains the "A" item and if yes, it counts how many As there are. One item A costs 8.00 and it has no discount, so it multiplies the number of counts with the price of the item A.
*Then it checks if the array contains the "B" item and if so, it counts the number of Bs in the array. One item B costs 12.00 and there is a discount by getting 2 Bs, you pay 20.00. So, if the count is an even number, the price is equal to (count/2 * 20.00) otherwise the price is equal to (count/2 * 20) + 12.00. 
*After, the program checks if the array has the item "C".One item C costs 4.00 and if you buy 3 Cs, you pay 10.00. It counts how many times it's in the array and then calculates the price. If the count is a multiple of 3, then the price is (count/3)*10.00 , else, (count/3 * 10) + 4.00.
*Afterwards, it checks for the item "D". An item D costs 7.00 but if you buy 1 then you get another 1 for free. So, if the number of counts is even number, the price equals to (count/2*7.00), otherwise it equals to (count/2 * 7) + 7.00.
*At the end, it checks for any item "E". One item E costs 5.00 and if you get 3 pieces of E, you pay for the two. It counts again how many Es are in the array. If the count is divided by 3 and the remaining is 0 then the price is calculated by 2*(count/3 * 5) , else if the count is divided by 3 and the remaining is 1, then the price equals to (2*(count/3 * 5))+5.00. Otherwise the price is 2*((count/3 * 5) + 5.00). 

For each case the price is calculated at the end, and it is added to the total amount to pay. When the total price is calculated it checks whether it is less than 50. If yes, the delivery is 7.00 which is added to the total amount. Otherwise, the delivery is free. A relevant message pops up for the delivery charge and the total amount to be paid. 
 
--If the answer is no, there is a message pop-up to thank the customer for accessing the page.

--If the answer is something else from what it requested(yes/no), users are asked to enter the right answer.
