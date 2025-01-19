# CapstoneStep4
Identify research papers dealing with the same or similar problem as your Capstone project
Content based filtering:
https://developers.google.com/machine-learning/recommendation/content-based/summary
An article explaining the bennefits and disadvantages of content based filtering.  Some of the advantages are that the model doesn’t need data about other users and it is easily scaled to a large number of users. Also, the model can capture specific user interests and recommend niche items. Some of the disadvantages are that the model requires a lot of domain knowledge and hand-engineered features. Also, the model has a limited ability to expand on users' existing interests.

Collabrative filtering:
https://developers.google.com/machine-learning/recommendation/collaborative/summary
This is an article about the advantages and disadvantages of collaborative filtering. It discusses the benefits of not needing domain knowledge, serendipity, and having a great starting point. Also, it covers the drawbacks of not being able to handle fresh items and the difficulty of including side features. Important points are that collaborative filtering can help users discover new interests and does not require domain knowledge.

Recommendation engine challenges:
https://awadrahman.medium.com/5-challenges-in-building-recommender-systems-77acbc0948cb
This Medium article highlights the complexities involved in building effective recommender systems and provides insights into various techniques and strategies for overcoming these challenges.
  1. Cold Start Problem:  This occurs when new users or items are introduced to the system. Since there's no prior data on their preferences or interactions, it's       difficult to provide accurate recommendations. The article suggests using content-based filtering or hybrid approaches to mitigate this.

  2. Data Sparsity: In many real-world scenarios, user-item interaction data is sparse. Most users interact with only a small fraction of the available items,           making it hard to identify similarities and provide recommendations. Techniques like matrix factorization and dimensionality reduction are proposed to              address this.

  3. Synonymy:  Different words or phrases can refer to the same concept. Recommender systems might struggle to identify these synonyms, leading to less effective       recommendations. The article suggests using knowledge graphs and ontologies to capture semantic relationships between items.

  4. Privacy Concerns:  Collecting user data for personalized recommendations raises privacy concerns. Users might be hesitant to share their preferences due to         fear of data misuse. The article emphasizes the importance of data anonymization, differential privacy, and federated learning to address these concerns.

  5. Balancing Relevance and Diversity: Recommender systems need to strike a balance between recommending relevant items and offering diverse suggestions. Overly        focusing on relevance can lead to filter bubbles, while excessive diversity might result in irrelevant recommendations. The article suggests using techniques       like multi-armed bandits and reinforcement learning to explore this trade-off.

Exising board game recommenders:
https://medium.com/@hacware/hacware-engineer-takeover-a-board-game-recommendation-engine-5aed1bd1c10c
The article describes the author's journey in building a board game recommendation engine as their first project at Hacware. They utilize a dataset from BoardGameGeek, containing information about various board games and user ratings, and gives key insights into considerations when building a recommendation engine specifically for board games.  The author goes in to detail on data processing, Collabrative filtering, content based filtering, model evaluation, challenges, and results.  I want to particularily point out the challenges mentioned.  The article hints at challenges like dealing with the "cold start problem" (making recommendations for new users or new games with limited data) and ensuring diversity in recommendations (avoiding recommending only very similar games).

Also, I have made copies of other projects using the same BGG dataset into this repository and have played with the models. These models mostly consist of only using collaberative filtering.  My plan is to ellaborate on these examples, and also add a further layer with content-based filtering.
