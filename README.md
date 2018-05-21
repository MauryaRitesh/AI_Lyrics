# AI_Lyrics

****Can we use Artificial Intelligence to generate Lyrics?****

Of course we can. Isn't that sounds Amazing!!!
So, let's get started and discuss this topic in detail in [this video](https://www.youtube.com/RiteshKumarMaurya).

****Computer Requirements****
Your PC or Laptop must have GPU(Graphics Processing Unit) and the minimum RAM should be 8GB, 16GB or more would be fine.
My laptop has 8GBs of RAM and no GPU except a dedicated Intel Graphics Card. That's why it crashed and I had to reboot it on the first run.
The Training process would take a lot of time. So, keep patience!

****IDEA****

The idea is to build a model which is trained on a series of song lyrics and then use it to generate further lyrics with some input. 
For example, the model will take a small string from the user (Like: Happy Birthday to you) and then it will try to generate the lyrics from this line!
For this purpose, I'm using a Keras based RNN, i.e., Recurrent Neural Network with Long Short Term Memory(LSTM) for genrating lyrics which will differ in each case and will also memorize or learns from the past predictions.

****Coding the Network****

We are using Keras with Tensorflow as backened. Keras lets us to create and solve our problems in an object oriented way.
So, there are basically two dependencies for this repo, which can be installed in CMD by typing:

    pip install keras
    pip install tensorflow

We are done to proceed further!
Now just run the following in CMD:
    
    python main.py
    
This will just print the lyrics with some default sentence in it.
If you want to give it your own sentence, then open the ****main.py**** program and in the last:
    
    Give your sentence in:
    sentence = "Your first line of lyric here"
    
 That's it.
 
 Please do ****STAR**** this Repo if you think it helped you.
