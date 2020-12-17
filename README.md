# scene-bot
Scene bot helps to generate movie scene dialogues... interactively!

Scenebot is the culmination of my first semester in the SIM department at Mass Art. It is a multi month project.
I began scenebot with more granular focus that when I completed the project, I now am turning my attention
to refining the relationship between data and art from a theoretical perspective. Hopefully this project marks
the beginning of a long exploration into the concept of "mechanisms that inspire." Viewing art through this 
functional lens allows for a more intuitive interface between "human-scale" concepts and those of big data.
In turn this environment will enable to application of large-scale insight to the personal creative practice,
promising to generally accelerate creative efforts across the arts.

For more on these conceptual topics please read my essay. "Scene Bot: Frontiers in the application of artificial 
intelligence as artistic medium" and please email me your thoughts: arcollins@massart.edu I'm super excited to elicit the
most diverse set of reactions to these ideas I can -- please don't hold back.

To play with Scene-bot all you have to do is head to the code folder and click scenebot.ipynb. This will bring you to a
"google colab" instance where you will be able to run the first two cells to set up your system, and the third cell will start
a conversation. You will need to put in valid google credentials to get access to the gsutil appplication. If you are
as concerned re privacy as I am don't worry as you will only be opening a private client that will privately connect
to my google bucket where I've stored the trained models (4 of them).

The downloads should take about ~5-8 min

Once you've gotten a sense for how Scenebot works remeber that it was built as a tool. Scenebot has greater depth of meaning than
will it will seem after only one or two interactions. This means that trying out 200 different scripts may actually provide
creative value. I imagine the tool as being a way to drift through a space -> somewhere between a random brain storm and a
structured brainstorm. Scenebot may provide you new ideas that allow you to incrementally edit ideas for scripts with enough 
interactinons.

Lastly, for creative application, it's helpful to get a general understanding of how this system works:
A language model tries to select the right class of words to respond to you based on a set of genres it was trained on.
Effectively the genre you input dictates the set of possible choices that will likely be made. Next as the conversation grows,
the model uses "left handed" context to generate the next response texts. So what you wrote previously will impact what comes next.
This is important to consider when trying to edit a line that occured early in the script, it might effect the remaineder of the lines.
If the last line is changed only then only that last line changes -> a human edit. If the second to last line changes, you can logically
steer the response: 1. Bill what are you eating -> 2. lollipop! NOT 1. Bill what are you eating -> baseball was invented in 1900

Have fun and remember not many people are exploring these sorts of tools its an untested space where theres a lot to be accomplished.
There are no right answers as to how to use this tool as of right now, explore!
