# AI_Lyrics

****Can we use Artificial Intelligence to generate Lyrics?****

Of course we can. Isn't that sounds Amazing!!!
So, let's get started and discuss this topic in detail in [this video](https://www.youtube.com/RiteshKumarMaurya).


****IDEA****

The idea is to build a model which is trained on a series of song lyrics and then use it to generate further lyrics with some input. 
For example, the model will take a small string from the user (Like: Happy Birthday to you) and then it will try to generate the lyrics from this line!
For this purpose, I'm using a Keras based RNN, i.e., Recurrent Neural Network with Long Short Term Memory(LSTM) for genrating lyrics which will differ in each case and will also memorize or learns from the past predictions.

****Coding the Network****

We are using Keras with Tensorflow as backened. Keras kets us to create and solve our problems in a object oriented way.
So, there are basically two dependencies for this repo, which can e installed in CMD by typing:

    pip install keras
    pip install tensorflow

That's it.
Now just run the following in CMD:
    
    python main.py
    
This will just print the lyrics with some default sentence in it.
If you want to give it your own sentence, then open the ****main.py**** program and in the last:
    
    Give your sentence in:
    sentence = "Your first line of lyric here"
    
 That's it.
 
 Please do ****STAR**** this Repo if you think it helped you.
