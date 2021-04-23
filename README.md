# Contact_Network
The contact network will give an idea about the contacts taking place in a public transport. Each passenger is taken as a node and the contact between them is taken as an edge connecting them.
We have considered a train route from Kharagpur to Howrah ( WB, India ), wherein we have got the list of passengers boarding and de-boarding at each station from the train simulation model and then developed a contact network consisting of the details of two persons with whom the contacts are taking place. In the entire train, i code traced around 8 lakh contacts, which will be helping us in tracing the spread of infection.

#Contact_Tracing
The main objective is to trace the spread of infection, which is done using the contact tracing code. It utilises the contact network along with a seed infected of 10 peoples and calculating the effective infection percentage at each station, which finally gives us the net infected peoples at each station deboarding the train or is still within the train. 
