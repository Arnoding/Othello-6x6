# Othello-6x6

  Soft library
  ----
      * how to install pytorch:
          *  pip3 install torch==1.3.1+cpu torchvision==0.4.2+cpu -f https://download.pytorch.org/whl/torch_stable.html
      * how to install matplotlib:
          *  python -m pip install -U pip setuptools
  
  how to operate
  ----
      * run model.py to train the AI with Training_Set,in the end of training,model.py will automatic generate the plot of loss and games
      * after training, run Othello.py to play a game
      * choose 1 to add a AI and choose 0 for a play,you can enter '1 1' to let AI play against AI, or enter '1 0' to play with AI 
      * in the end to a game, a number will be displayed at the bottom like '812','2294' etc. this number is the sum of nodes have been checked during tree search.
  others attention
  ----
      * For different board sizes, some of our code names are same but the contents are different. In order not to cause confusion, we have put the codes for different board sizes in different repositories. Here is only the code summary of the 6x6 board. The parameter used is learning rate = 0.005
      * thank you 
        all best 
        Ding 
