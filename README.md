# Jennifer Russell's Data Science Portfolio

This is a public portfolio of my data science work. Most of my work has specialized in Natural Language
Processing, so the projects in this repo will mostly reflect that. I also have experience in data
visualization, and included such a project to reflect the high degree of importance I feel about having 
solid data storytelling skills and how much of the value in our work as Data Scientists is not only from 
the models we can build but also how we can create an impact through the presentation of our work. 

### Project 1: LLM Classification

This is an academic project where the task at hand was deteting the emotion of a sentence, which could belong to one of 6 categories (anger, fear, joy, love, sadness, and surprise). With a partner, we created 2 models, both a Recurrent Neural Network (RNN) and a Feedforward Neural Network (FFNN). Then we ran a deep analysis comparing the two approaches. 


### Project 2: LLM Question Answering 

This is another academic project that I worked on individually, with the goal of developing a model capable of doing reading comprehension, based off of the SQuAD dataset, which contains questions and answers from wiki. In the first part of the project, I create a RNN from scratch, justifying everystep from how I created the vector embeddings, the model layers I used, to the attention model I decided to add. I decided to take a 3 pronged aproach, creating models for where the answer started, where the answer ended, and if the word was included in the answer. I controlled the loss function to ensure that the model wouldn't face an extrapolating degree of consequence on one model if predicted that a word wasn't in an answer. In the second part of the project, I demonstrate my ability to use the HuggingFace Transformers & Datasets libraries to leverage pretrained models as a potential solution. I conclude with a full analysis of the results of both models. 


### Project 3: Topic Modeling of Underlying Patient Conditions

This was an exploratory project I completed, where the goal was to see if it was possible to predict the underlying patient conditions based off of the medical reports taken at the time of visitation. Since no labeled data was provided, I went with a topic modeling approach. We had two key pieces of information in the medical reports: patient history and chief complaints. The medical history was a long paragraph about the background of the patients medical issues and the chief complaint was the reason for the patient visit.Given this information, I tried to model the feasibility of detecting underlying conditions with Natural Language Processing strategies and analyzied the success of my performance. 


### Data Visualization & Storytelling 

This was an academic project I completed with 2 other peers, where our task was to tell a story using data. We choose to present information on the changing migratory patterns of birds across North America due to climate change. The project consisted of a mixture of research into our chosen topic, the creation of interactive visualizations using the D3 library, and creating a compelling story for our audience. Please find all code for the website in the 'static' forder and the documentation of our design journey in the 'Final Deliverable - Design Rationale' pdf. Unfortunately, Heroku, the platform we hosted the website on, no longer supports free projects. Please either run project locally or refer to the 'website.png' to get a feel for the project, understanding that there will be no interactive capability on the png.

I appreciate you taking the time to look through my work. I am passionate about the powerful impact I believe Natural Language Processing will have in the future. Please feel free to reach out to me at 
jjrussell10@gmail.com if you have any questions, comments, or suggestions. 

Thanks,
Jennifers
