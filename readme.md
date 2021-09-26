**Link:** https://machinelearningmastery.com/how-to-develop-a-generative-adversarial-network-for-an-mnist-handwritten-digits-from-scratch-in-keras/

I have done this project with help of above article.

* There are 100 epochs to train the model
* The model consists of two models, one is Discriminator Model and other one is Generator Model.
* The Generator Model generates image4 and the Discrminatir Model discrinates whether it is real or fake.
* Once the discriminator model is unable to discriminate any more properly(50%), we can say that our generator model is generating very good image.

Explanation of the codes are commented inside notebook.

There are 25 images inside **generated_images** directory, which has been generated with our model.