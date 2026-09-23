# GitHub Practice

**Article:** [GPT-6 Astra, Looped Transformers, and More](https://magazine.sebastianraschka.com/p/gpt-6-astra-looped-transformers-and)

The article mentions looped transformers, which I think takes the output from the transformer and feeds it back into the transformer for more refining. I think it would make sense that passing through more transformer layers would get better results. However, this would require more computation, which would need to be balanced. There is also a choice to reuse parameters or use new parameters for the additional transformer blocks. Reusing parameters would save memory, while not reusing parameters could lead to more specialization between transformer blocks.

It is also interesting to see how an LLM is capable of interacting with computers and perhaps robots, and isn't just used for outputting text.