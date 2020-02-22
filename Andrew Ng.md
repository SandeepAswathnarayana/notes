# Andrew Ng: AI Podcast with Lex Fridman (Feb 20, 2020):  
*Note: This is a rough draft and overview of the podcast which includes my key takeaways. For the ease of typing while simultaneously listening to the podcast, I have only included phrases and key points in the notes.*  

## Early days of developing Coursera and MOOCs:  
- Recorded videos for coursera between 10 PM and 3 AM most of the days  
- Good understanding of the foundations and basics to build a long-term career, try to consistently make decisions based on these principles  
- **Motivation behind Coursera:** Build a website where multiple people could be logged in to the computer at the same time, getting credit (from the computer) for individual work and for anything people do as a group.  
- "I'd love to see the owners of mom-and-pop stores with a very little code customize their TV display for their special this week"  
- **Reason behind Andrew Ng's love for whiteboard as a teaching tool:** math & equations, build up a complex concept one piece at a time, enhance understandability.  
- Andrew Ng, Peter B, Adam Cole, Morgan Quigley: worked on one of the pioneering Reinforcement Learning applications (autonomous helicopter).  
- Math Professor (anecdote): "I do what I do because it helps me to discover truth and beauty in the universe"  
- **Motivation for Unsupervised Learning:** In Geoffrey Hinton's words, there are 10^14 synaptic connections in human brain, human lifespan is about 10^9 seconds (30 years) --> we need to learn 10^14 bits in 10^9 seconds (assuming each synaptic connection has a 1-bit parameter). i.e., you need to learn at a rate of 10^5 bits per second through your entire life, which is impossible!  
- Conviction to pitch an idea at Google Brain (Sebastian Thrun): Adam Cole's graph with the Importance of Scaling the models way bigger than what's possible on the CPUs at Stanford  
- Which of these result in better performance - Larger Datasets or Better Architectures?: Both (depends on the problem)  
## deeplearning.ai:  
Motive: to know the differences between various optimization algos, what to do if the algo overfits, how to you tell if it's overfitting, when and when not to collect more data, learn how to debug ML algos (change the architecture, get more data, try different optimization algos, etc).  
## Unsupervised Learning: a beautiful idea!  
Idea or Motive: To generate infinite labeled data.  
Examples:  
(1) Self-supervised Learning: take lots of unlabeled images off the internet --> rotate each image by a random multiple of 90 degrees --> train a supervised NN to predict its original orientation --> now you can generate an infinite amount of labeled data. Conclusion: Taking unlabeled data and making up labeled datasets, training a large NN on these tasks. You can take the hidden layer representations and transfer it to different tasks very powerfully.  
(2) Word Embeddings: Take a sentence --> delete a word --> predict the missing word.  
(3) Jigsaw: Cut an image into 3x3 grids --> jumble the pieces --> have the NN predict which of the 9 factorial possible permutations the image came from. Companies working on this: OpenAI, Facebook, Google Brain, Deep Mind.  
## Career in Deep Learning:  
- Begin with Coursework, work on projects, read blogs posts, cultivate an habit of reading at least 2 research papers per week, start small with a hobby project which eventually leads to bigger accomplishments. *Consider watching Andrew Ng's [Stanford CS230 Lecture](https://www.youtube.com/watch?v=733m6qBH-jI) for advice on career and how to read a research paper.*  
- Should one consider pursuing a PhD? Yes. If someone aspires to be a Professor. But what's more pivotal in both academics and companies: the PEOPLE you are ineracting with on a daily basis. For job search and career advice, consider watching [Andrew Ng on Building a Career in Machine Learning](https://www.youtube.com/watch?v=4kiHsIaK9_w)  
## AI Fund:  
- Startups should be outcome driven and very customer obsessed.  
- Motivation behind AI Fund: build AI fund to systematically create new startups from scratch, go after the rich space of opportunities in AI to get the projects done.  
Startup Studio: Deals with issues in making ML algos work in real life and deploy them into production, how to validate, get the specialized domain knowledge, help with key decisions, provide with the support structure and optimal ecosystem.  
## Landing AI:  
- Help transform companies outside the software/internet sector: manufacturing, healthcare, agriculture, logistics & transportation, etc. where there are fewer people, more opportunities/problems to work on.  
- [AI Transformation Playbook](https://landing.ai/ai-transformation-playbook/): long-term journey that companies should take, but the first step is to start small. Doing so would instill faith in peers and other teams about your ideas. Andrew Ng and his teams' first few AI projects that started small: Google Speech Recognition System --> Google Maps --> Google Ads.  
## Concrete Challenges faced by Companies and How Landing AI is currently working on addressing them:  
- There's a huge difference between something that works on the Jupyter Notebook on your laptop vs something that runs in the prodcution deployment setting in a factory. Ex: Robustness and Generalization (difference in lighting). Solution: Domain adaptation, transfer learning. Conclusion: There's more work to be done.  
- Redesign tasks, planning for the change management, make sure the software you write is consistent with the new workflow, how to deal with the maintenance or DevOps or MLOps.  
## AGI:  
- AI Ethics, Problems to  be addressed today: Bias, Wealth Inequality (need to make sure the wealth is fairly shared), Education  
- Regrets: The process of discovery, we keep finding out things that seem so obvious in hindsight. But, it always takes so much longer in reality.  
- Moments of happiness, fulfillment: Nova Ng, his daughter; helping others achieve their dreams; make humanity more powerful as a whole.  
















