### Attention Is All You Need by Ashish Vaswani et al.


## HW 14	CSE 6369-002 Special Topics Advanced Intelligent Systems Spring 2021  
## Due: 4/23/2021 11:59 pm
## Ogenna Esimai 

# Review of “Attention Is All You Need”
### Problem To Be Solved
This paper by authors Ashish Vaswani et al. presented at NIPS 2017 tries to solve the problem of providing a simple model architecture for sequence transduction stating that the main ones at the time of writing of the paper were based on complex recurrent or convolutional neural networks that include an encoder and a decoder. 

The simple model architecture this paper proposes is based on attention mechanisms alone and does not contain recurrence. It is called the Transformer. The Transformer is “the first transduction model relying entirely on self-attention to compute representations of its input and output without using sequence-aligned RNNs or convolution.” It is also a foundation upon which the GPT, GPT-2, GPT-3 of recent publicity are built.

### Good Points
The paper has several good points. 

Firstly, the paper addresses several limitations of its own work. For example, it mentions a weakness of the Transformer in the form of a tradeoff between improvement in complexity of the number of operations required to relate signals from two arbitrary input or output positions which grows
in the distance between positions, from linearly or logarithmically for other mentioned models but is a constant number of operations for the Transformer. The weakness is a reduced effective resolution in the Transformer.

Secondly, it attempts to solve its own limitations. For instance, for the example of the weakness given immediately above, the paper implements Multi-Head Attention as a countermeasure. 

Thirdly, the paper provides work that it plans for the future. As an example, “To improve computational performance for tasks involving very long sequences, self-attention could be restricted to considering only a neighborhood of size r in the input sequence centered around the respective output position. This would increase the maximum path length to O(n/r). We plan to investigate this approach further in future work.”

### Limitations
Other than the limitations the paper mentions such as given above, and for another example, because the paper’s model lacked recurrence and convolution, it lacked a way “for the model to make use of the
order of the sequence” - as a result, the paper introduced “"positional encodings"”to the model; other than the limitations the paper mentions, no additional limitations came to my mind after reading the paper.

### Suggestions For Improvement
For improvement of the paper, for now I would encourage action upon the several points the paper mentions as areas for future work. 

### Reference
Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. 2017. Attention is all you need. In Proceedings of the 31st International Conference on Neural Information Processing Systems (NIPS'17). Curran Associates Inc., Red Hook, NY, USA, 6000–6010. https://papers.nips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf

