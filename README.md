# zomato_analysis

Abstract :
This project analyzes restaurant data from Zomato to uncover trends and insights that can inform business decisions. The dataset includes information about restaurant types, online ordering and table booking availability, ratings, votes, and approximate costs for two people.

Data Cleaning:
The rate column was cleaned to remove non-numeric values (like "NEW" or "-") and convert ratings into numeric values by removing the "/5".
output:
                    name online_order book_table  rate  votes  \
0                  Jalsa          Yes        Yes   4.1    775   
1         Spice Elephant          Yes         No   4.1    787   
2        San Churro Cafe          Yes         No   3.8    918   
3  Addhuri Udupi Bhojana           No         No   3.7     88   
4          Grand Village           No         No   3.8    166   

   approx_cost(for two people) listed_in(type)  
0                          800          Buffet  
1                          800          Buffet  
2                          800          Buffet  
3                          300          Buffet  
4                          600          Buffet  


Distribution of Restaurant Types:
The listed_in(type) column was analyzed to determine the most common types of restaurants.
A count plot visualizes the frequency of different restaurant types.
![distribution](https://github.com/user-attachments/assets/92f698a2-15eb-4a19-ac54-8fd06cb42cb0)

Impact of Online Orders on Ratings:
Restaurants were grouped by their online order availability (online_order column).
The average rating for restaurants offering online orders vs. those that don’t was calculated and plotted.
![online](https://github.com/user-attachments/assets/733e41b4-12cb-41f7-8071-f9a88c1cfaf4)


Votes Distribution:
A histogram was created to show the spread of the votes column, reflecting how engaged customers are with restaurants.
![votes](https://github.com/user-attachments/assets/137591d8-88ce-43b2-af0b-fe0707a29043)
