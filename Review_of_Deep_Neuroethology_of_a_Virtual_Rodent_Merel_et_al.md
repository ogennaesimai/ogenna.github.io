### Deep Neuroethology of A Virtual Rodent. Merel and Aldarondo et al. 
https://arxiv.org/abs/1911.09451 

## HW 4	CSE 6369-002 Special Topics Advanced Intelligent Systems Spring 2021  
## Due: February 26, 2021 11:59 pm
## Ogenna Esimai 

# Review of “Deep Neuroethology of A Virtual Rodent”
### Problem(s) To Be Solved
This paper by authors Merel and Aldarondo et al. tries to solve the problem - the knowledge of how neuroscience and deep learning impact the study of motor control lags behind the knowledge of how these fields impact the study of sensory and cognitive systems. Furthermore, it is also a problem that there are no works comprehensively modelling embodied control of an animal including how said animal uses its senses, body, and behaviors to solve tasks in a physical environment.
### What is the Solution to These Problems?
The paper provides a virtual model of a rodent which virtual model lends itself to the study of embodied motor systems. In more detail, the virtual rodent model although being virtual in the sense that it is a computational algorithm is also located in a physical environment where it solves tasks. It gets real, physical sensory inputs - visual and proprioceptive - through a camera mounted on its head. Yes. It has a head, although being virtual, because via software such as MuJoCo (Multi-Joint dynamics with Contact) (http://www.mujoco.org/index.html) which the authors use, the virtual rodent has a body.  
### Why is the Virtual Rodent Important?  
It provides an avenue where using deep learning, behaviors (think actions) of a rodent and their underlying motor foundations can be studied to solve the problems in above section “Problem(s) To Be Solved”. 
### Good Points
The paper has several good points. 

Firstly, it lays groundwork for further study of embodied control. 

Secondly, the paper combines several neural network frameworks effectively to achieve the purpose of the desired model. Specifically, these neural network frameworks include recurrent LSTM, residual network, and  multi-layer perceptron.
 
Thirdly, the paper goes beyond the architectures and results of the neural network model to explore the underlying workings of the model such as which features are encoded by which parts of the model. 
 
### Limitations
The paper is limited in that although attempt is made for the study accomplished by the virtual rodent model to be grounded, the physical environment in which the virtual rodent is located is still an artificial one and a limited subset of the real world environment. 
### Suggestions For Improvement
For improvement of the paper, I would broaden the reach of the environment to improve the groundedness of the work done by the paper. 
### References
Deep Neuroethology of A Virtual Rodent. Merel and Aldarondo et al. 
https://arxiv.org/abs/1911.09451 

MuJoCo. Advanced Physics Simulation. http://www.mujoco.org/index.html. Accessed February 26, 2021.

