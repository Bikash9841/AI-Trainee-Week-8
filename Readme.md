# RNN for Language Translation

## Task Performed:

1. Made the tokenizer custom trained on our dataset.
2. Use RNN Encoder-Decoder Architecture for Language Translation Task.
3. Tried Various Techniques such as batch size 1(no padding), with padding, with `sos and eos` token.
4. Also, Tried to introduce dynamic `max_length` by breaking the decoding loop for each token when 75% of the token in a batch is pad token.
