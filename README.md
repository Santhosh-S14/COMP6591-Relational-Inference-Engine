# Implementation of relational inference engine
The paper "Using Relational Inference Engine to Answer Questions"
offers a rapid chatbot learning method that enables it to dynamically and
automatically learn new information to handle new conversation domains
more efficiently. The rAVA robot builds internal knowledge structures
while reading new texts, allowing the chatbot to make logical decisions
about the world’s facts. It acts as a companion to you after learning from
the texts and answers your questions accordingly. This method is tested
in the paper by reading additional texts and extracting family relationship
information from designated entities identified in the free text contents.
After reading these documents, rAVA can accurately react to numerous
questions posed by users, providing them with rapid and personalized
feedback evaluations. We will use the above work as a guide to construct
and research an inference engine that can answer questions. Prolog will
be used for maintaining and dealing with knowledge bases which also will
be included in the article. We shall also investigate all other languages
that can interact with Prolog and operate successfully with the knowledge
base. We will also investigate whether the program can learn from the
document that is given to it rather than manually developing a knowledge
base.
