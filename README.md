# CarEvaluator
This project evaluates different features of car on the basis of selling price.This analysis is used to provide car dealerships recommendations on how to fine tune their inventory for maximizing profit

### Methodology
---------------
Data was derived from Kaggle.After cleaning and preparing, data was analyzed using various regression techniques. ElasticNet CV was used to determine best hyperparameters from a sample of data. These were used as optimal parameter for running Ridge, Lasso and ElasticNet. GridSearchCV was also done to determine best alpha for Ridge regression. 
Out of these models Ridge regression was found to be most optimal for this analysis depending on root mean square error.Based on regression co-efficients, below result was found.

### Result
_______
1. Customers are willing to pay higher price for certain types of cars.Types like pickup truck,convertible, coupe, truck, off-road cars and other types like sports cars can be priced higher in  the inventory. Having cars like SUVs and Hatchbacks so bring in moderate revenue. Having mini-vans, wagon and sedan in inventory could hurt revenue as these are being sold at loss.
2.Front wheel drive significantly drops the price of a car. This could be cause of instability of these cars in icy or rainy conditions It would be better to have more rwd and awd in the inventory.Also customers prefer to know the specific drive type of the car when buying, missing this information can negatively affect the price.
3. Cars with orange and yellow colors being unique, can be priced higher.This could true in the sports car category. Other colors that customers prefer are white,black,silver and red. Green, gray and brown are not favored by customers, so these should be rmoved from the inventory.
4. State also has an effect on the price, likely cars from certain states can be priced higher than others. States like West Virgina, Montana, Washinton show a higher value than states like Connecticut, Michigan and New Jersey.
5. Cars in better condition and that are newer are also preferred by customers, although these have a lower effect.

