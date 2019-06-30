## Eliza chatbot

Authors : Merin Joy and Sai Nikitha

Date : September 19th 2018

This Eliza chatbot program acts as a psychotherapist that engages in conversation with the user. By making use of NLTK and regular expressions.


### Instructions to run :

* Step 1: Run the following code in command line or ipython notebook.
* Step 2: Type in English and start the conversation by providing your Name.
* Step 3: Continue the conversation by replying to the pre-defined statements.
* Step 4: End the conversation by typing quit.


### Example Conversation :


Talk to me by typing in English. Enter quit when you are done.

---
Hello. I am a Psychotherapist. Whom do I have the pleasure of speaking with?

>Hello.I am Merin

Hi  Merin. What brings you here?

>I need assistance

 Merin How important is assistance to you?
 
>It is very important to me

Please tell me more

>I feel depressed

Have you discussed your issues with someone?

>Yes

Why do you say yes?

>I have discussed it with my parents

Good family relations are extremely important.

>Are you a machine?

I might be a machine?, what do you think?

>i think you are a bot

When did you get that thought?

>While talking to you

And how does it sound to you?

>Its weird

Tell me about your closed ones?

>I am close to my family and friends

Are you happy with them?

>Yes

Please tell me more

>My parents are good individuals

How do you feel about them?

>Amazing!

Why do you say amazing?

>Because they are!

Are you sure?

>Yes

Please tell me more

>Okay its time to go! bye!

Sounds good

>quit

Your bill will be sent to your mail.


### Algorithm :

* Step 1: Start
* Step 2: Extract the input string.
* Step 3: Check if input string matches equals to quit
   * Step 3.1: Then return
* Step 4: Else
   * Step 4.1: Extracting the input string that matches the regular expression
   * Step 4.2: Calling function pairs with argument as input
   * Step 4.3: Start the conversation
* Step 5: End
