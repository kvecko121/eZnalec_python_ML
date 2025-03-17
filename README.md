HOW TO USE:

There is myApt.json file already filled out, you can try the model with this one -> skip to step 10. 

If you want to try a model with another apt. continue on these next steps:

1. For LAYOUT pick only one: [1+1, 1+kk, 2+1, 2+kk, 3+1, 3+kk, 4+1, 4+kk, 5+1, 5+kk, 6-a-vice, atypicky]

2. For LOCATION write your location in lowercase and with normal characters (in eZnalec.ipynb you can search for all possible locations using ctrl+f and type "locations") e.g. zizkov, nusle, dejvice

3. For SIZE write the size or area of your apt. in m2

4. For PRICE PER M2  write 0 if you do not know (it will be calculated for you), or write a specific number if you are sure. (0 is recommended)

5. For ENERGY LEVEL A=1, B=2, C=3, D=4, E=5, F=6, G=7

6. For FLOOR enter the floor on which is your apt. located

7. For CONDITION write one of these: [Ve velmi dobrem stavu, V dobrem stavu, Ve spatnem stavu, Ve vystavbe, Projekt, Novostavba, K demolici, Pred rekonstrukci, Po rekonstrukci, V rekonstrukci]

8. For the rest of the FEATURES enter 1 if your apt. has this feature, or 0 if not.

9. Press Ctrl+S to save the file

10. RUN all the cells in eZnalec.ipynb, it needs to be run all only once, for trying out a new apartment repeat steps 1-9 and then RUN the cells in the last section "Test out the model with your apartment"

11. Scroll down, you will see the prices for m2 in your area and your layout. Below is the PREDICTED PRICE of your apt.

12. Scroll down to see the analysis, which compares avg. prices per m2 in different layouts and yours. Below is a graph where you can see the most important features of your area.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This is the second part of my machine learning project. 
I am using my own data scraped from a real estate website (2025).
And I am working with Linear Regression, probably I will try out and use L1, L2 (Lasso, Ridge) noamrlizations.
This project will predict (estimate) price of your apartment and provide you with valuable insights according to your district and situation.
For now, the location is limited to Prague.
Stay tuned!

- Samo
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
