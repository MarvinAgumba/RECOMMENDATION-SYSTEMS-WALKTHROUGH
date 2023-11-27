# RECOMMENDATION SYSTEMS

A **recommendation system** allows predicting the future preference list for a certain customer or user and recommends the top preference for this user. Examples include: which books a customer prefers to buy on Amazon, which Netflix movie or series a user watches next, etc. (**Personalized & Unpersonalized Recommendation Systems**)

When using algorithms, the two main types are content-based algorithms (recommending new content based on similar content), and collaborative filtering based (recommending new content based on similar types of users)

**Unpersonalized recommendation systems** have been happening since way before machine learning was ever in the public knowledge base. An example of an unpersonalized recommendation would be on YouTube which recommends the most viewed videos.

**Personalized Recommendation Systems:** has many different algorithms: (***Content-Based Recommenders*** - Main Idea: If you like an item, you will also like "similar" items. ***Collaborative Filtering Systems*** - Main Idea: If user A likes items 5, 6, 7, and 8 and user B likes items 5, 6, and 7, then it is highly likely that user B will also like item 8)

![image](https://github.com/MarvinAgumba/RECOMMENDATION-SYSTEMS-WALKTHROUGH/assets/122484885/7ec2ab65-f562-4c27-9700-3844a45c754c)

![image](https://github.com/MarvinAgumba/RECOMMENDATION-SYSTEMS-WALKTHROUGH/assets/122484885/3b77d2a8-01e1-4a82-8fe1-5bb254c720c6)

![image](https://github.com/MarvinAgumba/RECOMMENDATION-SYSTEMS-WALKTHROUGH/assets/122484885/ef7b4648-b5d8-417c-a7fa-c008af887274)

### Memory vs. Model-Based Collaborative Filtering Approaches
|                     Memory-Based                     |                   Model-Based                  |
|:----------------------------------------------------:|:----------------------------------------------:|
| complete input data is required                      | abstraction (model) that represents input data |
| does not scale well                                  | scales well                                    |
| pre-computation not possible                         | pre-computation possible                       |
| relies on similarity metrics between users and items | relies on matrix factorization                 |

Recommendation systems have a direct impact on profitability and customer satisfaction for most businesses today. With the nearly limitless options consumers have for products online, they need some guidance! (Applications: *`Help in suggesting the merchants/items which a customer might be interested in after buying a product in a marketplace; Estimate profit & loss of many competing items and make recommendations to the customer (e.g. buying and selling stocks); Based on the experience of the customer, recommend a customer-centric or product-centric offering; Enhance customer engagement by providing offers which can be highly appealing to the customer`*)

### Developing Recommendation Systems from Real-World Datasets
 - Books Review on Amazon MarketPlace
 - Movie Lens Dataset
 - Jester Dataset
 - 1M Movies Dataset
