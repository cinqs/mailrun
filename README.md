# mailrun

I am starting with this project with around 27K mails imported from my gmail inbox.

This email address is used mainly for receiving verification code, e-publications, and for registering sites.

So from the beginning, I assume this repo contains these 3 topics:

1. e-publications
2. registering confirmation mails
3. some spam mails
4. personals
5. ...

----

### my plan
1. using a simple LDA-like method to roughly classify all those mails. importantly, label them.
2. remove some privacy
3. sample from the labels and verify the accuracy
4. generate training data-set for supervised-learning code.
5. training a doc2vec model
6. think something more and try something more
