### World Models


## HW 13	CSE 6369-002 Special Topics Advanced Intelligent Systems Spring 2021  
## Due: 4/16/2021 11:59 pm
## Ogenna Esimai 

# Review of “World Models”
### Problem To Be Solved
This paper by authors David Ha and Jürgen Schmidhuber tries to solve the problem of distilling several key concepts from a series of papers 1990–2015 on combinations of RNN-based world models and
controllers (Schmidhuber, 1990a;b; 1991a; 1990c; 2015a). It also discusses other related works that
“share similar ideas of learning a world model and training an agent using this model.” 

### Good Points
The paper has several good points. 

Firstly, in addition to the above discussion of world models, the paper presents its own world model. 

Secondly, the paper addresses several limitations of its own work.

Thirdly, following closely on the immediately preceding point, the paper provides suggestions on how at least one limitation is overcome.

### Limitations
Firstly, the paper is limited in that it is highly focused on work done or supervised by the last author. As a result, approaches to the topic are somewhat narrowed in this regard.

Secondly, the paper is limited in the regard that the input for its agent while based on the human cognitive system is restricted to a visual sensory component and a memory component.

Thirdly, the paper is limited in how well the world model approximates the actual environment. The paper notes that “our world model will be exploitable by the controller, even if in the actual environment such exploits do not exist.”

Fourthly, the paper is limited in that the agent itself has the ability to deceive the model. The paper notes that “The weakness of this approach of learning a policy inside a learned dynamics model is that
our agent can easily find an adversarial policy that can fool our dynamics model – it’ll find a policy that looks good under our dynamics model, but will fail in the actual environment, usually because it visits states where the model is wrong because they are away from the training distribution.” The paper uses a workaround to address this limitation: “To make it more difficult for our C model to exploit deficiencies of the M model, we chose to use the MDN-RNN as the dynamics model, … – we can simply adjust the temperature parameter τ to control the amount of randomness in the M model, hence controlling the tradeoff between realism and exploitability.”

### Suggestions For Improvement
Firstly, for improvement of the paper, I would add another/other viewpoint(s), preferably, having a differing/differing stance(s) from that of the last author of this paper. 

Secondly, I would explore extending the input for the agent to include, for example, an auditory sensory component and/or a tactile sensory component. 

Thirdly (addresses the third and fourth limitations above), regarding the problem to make it more difficult for the C model to exploit deficiencies of the M model, I would consider the possibility of using a different architecture altogether other than the C and M models.

### Reference
World Models. David Ha and Jürgen Schmidhuber. https://worldmodels.github.io/

