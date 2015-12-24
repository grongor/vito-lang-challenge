VitoLang challenge
==================

The goal of this challenge is to make your own game in your own language - VitoLang!

The game's name is "Guess developer" and is based on the famous game "Guess animal".
Your task is to make a program which will ask a user several questions about the developer
which the user is thinking about and to which the user can reply with simple yes/no answers.
When the program is sure which developer the user is thinking about then it will print out
his/her name. If the program is not sure and is out of questions it should make a
guess - pick random suiting answer. After that it should ask the user if it's answer is
correct. The user will again reply with yes/no answer. If the program succeded in guessing
the developers name it should print out a success message. Othwerwise it should somehow
apologize and ask user to help it out - it should ask the user to enter another question
and it's correct answer. The program will store that question to it's database and use it
next time to guess the developer more precisely.

You must complete that task in your own language - VitoLang! You can find all about it
there: https://github.com/grongor/vito-lang

The entire interface, questions etc are up to your imagination. Please check "Guess animal
example if you are still not sure about the task.

Good luck and have fun! :-)

"Guess animal" example
----------------------

```
vit.novak $ chci guess-animal.nohy

Hey, vit.novak, wanna play a game?

Think about an animal and I will tell you what
animal you are thinking about.

Are you ready?
> Yes

Does the animal fly?
> No

Does the animal live in water?
> No

Is it a home animal?
> Yes

The animal you were thinking about is a cat.
Is that correct?
> No

Jeeeez ... well, maybe next time I will do better.
What was the animal you were thinking about?
> dog

Ok, I should've seen that comming.
Can you type in a question that would help me distinguish between cat and dog next time?
> Does it often chase it's own tail?

Nice one ... and the answer is?
> Yes

Okey, I will remember that. Thank you ;-)

vit.novak $
vit.novak $ chci guess-animal.nohy

Hey, vit.novak, wanna play a game?

Think about an animal and I will tell you what
animal you are thinking about.

Are you ready?
> Yes

Does the animal fly?
> No

Does the animal live in water?
> No

Is it a home animal?
> Yes

Does it often chase it's own tail?
> Yes

The animal you were thinking about is a dog.
Is that correct?
> Yes

*\*epic music playing\** Of course it is :-)
```

