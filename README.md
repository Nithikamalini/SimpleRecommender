# SimpleRecommender
COMPANY: CODTECH IT SOLUTION

NAME: NITHIKAMALINI S                                            

INTERN ID: CT04DH1694

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

# TASK DESCRIPTION
SimpleRecommender is a Java-based recommendation engine designed to suggest products or content to users based on their preferences. It uses Apache Mahout, a powerful machine learning library, to implement collaborative filtering, a technique that identifies patterns in user behavior to generate personalized suggestions.

The application reads a dataset containing user-item ratings (e.g., how much a user liked a product) from a CSV file. Using Mahout’s FileDataModel, the system loads this data and analyzes user similarity through the Pearson Correlation method. A user-based recommender is then built using Mahout’s GenericUserBasedRecommender, which compares the active user to similar users (called a neighborhood) and recommends items that similar users liked but the current user hasn’t seen.

For example, if User A and User B have similar tastes, and User B liked a product that User A hasn’t tried yet, the system may recommend that product to User A.

The SimpleRecommender is modular, scalable, and can be extended to support item-based recommendations, real-time updates, or integration with web applications. It's an ideal solution for e-commerce platforms, streaming services, or content portals aiming to improve user engagement through smart, data-driven suggestions.
#OUTPUT 
<img width="876" height="246" alt="Image" src="https://github.com/user-attachments/assets/cfb7a8b1-2151-4ea4-875c-c7e7e0b0b0b3" />
