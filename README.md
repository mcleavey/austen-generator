# austen-generator
Pytorch language model to generate Jane Austen paragraphs
Requires the fastai library: https://github.com/fastai/fastai

Generates text of arbitrary length, after training on several Jane Austen novels.  Word embeddings are trained solely from the novels. 
Sample output:

    "Dearest believe it."
    “I have no doubt, I suppose, that you should have a right to see the house. I am not so fond as I do; 
but I am sure you would be very glad to see you.” 
     “I should like to see the house in a moment. I thought you would not be able.”
     She then went to the window, and, after a short pause of silence and reflection on the subject. The 
subject was soon followed, and Fanny was then in the room, when she had been able to speak, and to say, “oh,
yes, that I should have done for you,” was Fanny's answer.
    “It is not a man who would not think so, for it is not very likely, I suppose?” 
    “Yes, I am sure I shall not have a doubt of it; but I do not think I shall have the pleasure of seeing you.”
    
    ...is a good-natured, good-humoured young man, and a great deal more to the purpose than the rest. 
    I have been thinking of him, but he has not been so much pleased with his character, as 
    to be a man of good sense. I am not sorry for the idea. I am not sorry to see you again. I am
    sure he has been so much more attached to me, and that I have no doubt of the very circumstance
    that is ever to be made of. I have had the pleasure of receiving a letter from me. I have had
    no doubt that I should not have been in my life. I have been very kind and very kind in the world
    to have you so much in love with you. You have been a very good kind of woman, but as I am not
    in the least fatigued by the world. I am sure you have been so much more attached to her, and
    that I can hardly help thinking it all. I am not afraid that the whole party are in town, and
    that we are all very much in the habit. We have been very much in town; and I have no reason for
    writing, and that I am very glad you will be able in the same time to see you...
