## Coding decoder only transformer from scratch using pytorch and lightning

Decoder only transformer have masked attention ie, for understanding relationships between tokens in parallel, we only look at preceding tokens, since the task is to predict the next token.
However, we have to provide the entire context to predict next token.
