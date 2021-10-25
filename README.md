# Answer Net

#### Project name: Answer Net  

#### Project Prototype: [Figma Prototype Link](https://www.figma.com/file/2eAyuWywbGuqY8colPyMXB/AnswerNet?node-id=0%3A1)
  
#### Team members: Ian Wilkins <ian.wilkins@colorado.edu>  
  
#### Elevator pitch:  
Answer Net is a knowledge sharing network that allows users with similar information source and topic preferences to answer each other's questions. A user can only answer another users question if they have the same preferred source for the topic of the question, and access to the network requires participation in both asking and answering questions.  
  
#### Target user group:  
Target users are individuals currently using other question answering (QA) services like quora/google knowledge graph/stack exchange/yahoo answers, and individuals who rely heavily on friends for obtaining new information.  

More specifically, there are 3 types of users:  
1. Individuals already accustomed to, and participants in explicit QA services. Explicit QA services are sites specifically and explicitly intended for QA activities, not forums or boards where QA is a subset of the activities. Users of these sites are targeted because Answer Net provides a similar structure, but limits answers to those coming from individuals with similar source preferences. As an example, different critics are hired by different sources, and questions like “What is the best deal during Denver restaurant week?” is best answered by a critic that more closely reflects the user’s tastes. For a more pointed example, consider political questions, how many users would trust an answer from an individual citing Fox or CNN (the answer may change based on political orientation). Thus, connecting the user to other users with similar source preferences limits answers to those that are most likely to be relevant to the user.  
   
2. Individuals accustomed to, and participants in implicit QA services. Implicit QA services are sites that are not limited to QA activities, but include QA activities as a major purpose of the site. Many subreddit communities are examples of implicit QA sites. Answer Net is more constrained than many subreddits in scope (limiting the scope to answering questions instead of posting testimonials), but the community aspect is similar. A major benefit of online communities is the construction of a repertoire that allows other users to decide how to interpret a response. Much of this repertoire is generated from opinions explicitly posted, and references to the opinions of others. Answer Net simulates much of this through tracking what sources are references for given topics, and how satisfactory previously supplied answers are.  
   
3. Individuals who use social networking as a news and answer consumption media. Individuals who rely on the opinions of peers for news and QA tasks are likely to benefit from Answer Net, under the principle of “birds of a feather flock together”; people are surrounded by individuals with similar values, and therefore receive answers from individuals with similar sourcing preferences. Answer Net simplifies this process, and expands the network of answering parties beyond immediate friends.  
   
#### How this project meets the theme:  
This project analyzes each user’s topics of interest and their preferred sources for each topic.  
  
#### Interaction design challenges:  
1. How can we avoid echo chambers and epistemic bubbles, while still ensuring individuals are answered by other users with similar source preferences? This is a major challenge because many topics are highly polarized, and source preferences may help to strengthen the polarization. One goal of the user studies for this project is to test how much the source preference system polarizes answers.  
 
2. How can we score answers without discouraging the participation of the answering party? If an answer is scored poorly, we don’t want to discourage future participation, but we also don’t want to connect users to repeatedly poor answers.  
   
3. How can we motivate participation? This project revolves around the idea that users want access to the network, and are willing to participate in answering questions in order to have their own questions answered. It is therefore in the user’s best interest to be as complete as possible when listing topics of interest and sources. A smaller and less complete list will result in fewer connection to answer questions, and therefore fewer opportunities to improve the QA balance for asking questions. Imagine a new user has a QA balance of 0. Answering a question is +1, asking a question is -1. A balance of at least 1 is required to ask a question, so a new user must answer before they ask. Will this system actually motivate and incentivize participation?  
   
4. How general should topics and sources be? As an example, “The Witcher” may be too broad of a topic if the user is only interested in the second season of the live action series by Netflix (as opposed to the games). SOme amount of focus group and AB testing is needed to determine what kinds of generalization the user wants from Answer Net.  
