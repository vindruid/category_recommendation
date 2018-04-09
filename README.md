# Novel Way to e-Commerce Item Categorization by Item Name
Make a model to know category of item from the name

The explaination is from [here](https://medium.com/@hervindphilipe/novel-way-to-e-commerce-item-categorization-by-item-name-270d13b20e37)

Step: 
1. Calculate the probability of category when a word is known { P(category|word) } from data.
2. When predicting, sum the probability over all the words in item name.
3. Find the category who has the biggest value. 

