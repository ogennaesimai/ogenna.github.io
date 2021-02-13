### The Winograd schema challenge. Hector J. Levesque, Ernest Davis, and Leora Morgenstern
KR'12: Proceedings of the Thirteenth International Conference on Principles of Knowledge Representation and Reasoning, June 2012, Pages 552–561

## HW 3	CSE 6369-002 Special Topics Advanced Intelligent Systems Spring 2021  
## Due: February 12, 2021 11:59 pm
## Ogenna Esimai 

# Review of “The Winograd Schema Challenge”
### Problem To Be Solved
This paper by authors Levesque, Davis, and Morgenstern tries to solve the problem of limitations that it sees with the Turing Test by providing an alternative having advantages over the Turing Test. The paper gives as a limitation to the Turing Test, its reliance on deception given that the  machine trying to pass the test aims to deceive the interrogator into thinking that the machine is a human. The paper’s solution is the Winograd Schema (or WS) challenge.
### What is The Winograd Schema Challenge? 
It is a competition testing performance in answering questions each known as a Winograd Schema. Answering a Winograd Schema draws on the subject’s reasoning abilities and knowledge of the world. A Winograd Schema in turn is “a small reading comprehension test involving a single binary question.” 
### Why is The Winograd Schema Challenge important? 
It improves upon what the authors’ see as limitations of the Turing Test. It tests intelligence without relying on the subject being adept at deception. Furthermore, it is a variant of recognizing textual entailment (RTE) but at the same time, it does not depend on entailment explicitly. A problem with entailment is that it might be unclear to subjects what it means.
### Good Points
The paper has several good points. 

Firstly, it improves upon prior work in the field making contributions to advance the field. For example, Winograd Schema challenge (WSC) is a variant of recognizing textual entailment (RTE). It improves upon RTE in that it does not depend on an explicit notion of entailment. 

Secondly, the solution that the paper provides is stronger for including options in the questions. A part of intelligence is being able to choose between competing options and the WSC tests this aspect of intelligence indirectly.

Thirdly, the paper takes steps towards thoroughness by addressing potential problems with the provided solution. For example, in addition to stating that the authors’ goal in generating appropriate questions is for “normally-abled adults whose first language is English to find the answers obvious,” the paper goes further to address pitfalls of the answers being either 1) too obvious or 2) not obvious enough. In the former case, the pitfall is associated with “questions where the choice between the two parties can be made without considering the relationship between them expressed by the sentence”. Considering the following WS - The women stopped taking the pills because they were < >. Which individuals were < >? Answer 0: the women, Answer 1: the pills, special word: pregnant, alternate special word: carcinogenic. Since women can be pregnant and generally speaking cannot be carcinogenic and the pills can be carcinogenic and cannot be pregnant, there is an existing mutual exclusiveness of characteristics that can be used to give the correct answer without considering the context of the remaining parts of the question. The authors’ recommended solutions are to avoid this type of question or to use randomly chosen proper names of humans so that there is no chance of linking a name to the special word or alternate.

Fourthly, the paper takes steps towards robustness. The WSC is flexible in allowing for incremental progress and being able to be staged where different libraries can be obtained from the collection of questions to meet the demands of test takers having varying levels of background knowledge.
 
### Limitations
The paper is limited in the regard that as a test of intelligence, the WSC is not universal or general in the scope of the intelligence. Rather, it is primarily a test tied closely to linguistic and related intelligence. 
### Suggestions For Improvement
For improvement of the paper, I would explore the notion of being able to test non-linguistic intelligence using a linguistic method. Succeeding in this venture would increase the universality of Winograd Schema challenge as a test of intelligence.
### Reference
The Winograd schema challenge. Levesque et al. KR'12: Proceedings of the Thirteenth International Conference on Principles of Knowledge Representation and Reasoning, June 2012, pages 552–561.
