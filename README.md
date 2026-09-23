# GitHub Practice

**Article:** [GPT-6 Astra, Looped Transformers, and More](https://magazine.sebastianraschka.com/p/gpt-6-astra-looped-transformers-and)

The article mentions looped transformers, which I think takes the output from the transformer and feeds it back into the transformer for more refining. I think it would make sense that passing through more transformer layers would get better results. However, this would require more computation, which would need to be balanced. There is also a choice to reuse parameters or use new parameters for the additional transformer blocks. Reusing parameters would save memory, while not reusing parameters could lead to more specialization between transformer blocks.

It is also interesting to see how an LLM is capable of interacting with computers and perhaps robots, and isn't just used for outputting text.


## Comments from Mohiuddin Syed

 I like how you broke down looped transformers, along with the memory vs. specialization tradeoffs between reusing parameters and added new ones per block. The point of balancing the extra computation against better results shows the broader problem of AI, that more 'thinking' or passes are helpful for performance, but the compute cost doesn't become worth it. Interested to see how LLMs are going to used in the future as well instead of just using it for outputting text.