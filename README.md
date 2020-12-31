# scene-bot
SceneBot helps to generate movie scene dialogues... interactively!

First, if you have trouble running this colab please let me know: arcollins@massart.edu. 
I'll try to respond within a few hours.

A direct link to a colab demo can be found here:
https://colab.research.google.com/drive/19el9B8TDrc-mlTbBT6mlO_sAyW6AIcUE?usp=sharing

SceneBot is the culmination of my first semester in the SIM department (Studio for Interrelated Media) at Mass Art. It is a multi-month project. I began SceneBot with a more granular focus, which evolved into recognizing a need to address a number of challenges regarding the interface between art production and data science. I now plan to turn my attention to refining the relationship between data and art from a theoretical perspective. Hopefully, this project marks the beginning of a long exploration into the concept of "mechanisms that inspire." Viewing art through this functional lens allows for a more intuitive interface between "human-scale" concepts and those of big data. In turn, this environment will enable application of large-scale insight to the personal creative practice, promising to generally accelerate creative efforts across the arts.
For more on these conceptual topics, please read my essay -- "Scene Bot Frontiers_ in the application of artificial intelligence as artistic medium" -- and email me your thoughts at arcollins@massart.edu. I'm excited to elicit the most diverse set of reactions to these ideas I can -- please don't hold back. It's a little complex, but I hope that it communicates the broad areas of data science that strike me as promising for artists. Sharing domain knowledge has emerged as an important obstacle to the adoption of AI tech. Again, if there's any confusion, I'd be excited to discuss the paper further. I think all the ideas discussed are deeply relevant to art practice beyond the computational.
To play with SceneBot all you have to do is click this link: https://colab.research.google.com/drive/19el9B8TDrc-mlTbBT6mlO_sAyW6AIcUE?usp=sharing. This will bring you to a "google colab" instance where you will be able to run the first two cells to set up your system, and the third cell will start a conversation. You will need to put in valid google credentials to get access to the gsutil application. If you are as concerned about privacy as I am, don't worry as you will only be opening a private client that will privately connect to my google bucket where I've stored the trained models (4 of them).
The downloads should take about ~5-8 minutes. 
Once you have a sense for how SceneBot works, remember that it was built as a tool. SceneBot has greater depth of meaning than might be apparent if you limit yourself to only 1 or two conversations. This means that trying out 200 different scripts may actually provide creative value that will not occur in 1 or 2. Additionally, 1 to two uses of any new tool is unlikely to produce quality work. I recommend exploring how you  can uniquely leverage SceneBot’s capacities as a tool for inspiration (scheduling of brainstorming interventions or generating artificial prompts to write from). I imagine the tool as being a way to drift through a creative space -> somewhere between a random brainstorm and a structured brainstorm. SceneBot may provide you new ideas that, with enough interactions, allow you to incrementally edit scripts.
Lastly, for creative application, it's helpful to understand how this system works. A language model tries to select the right class of words to respond to you based on a set of genres on which it was trained. Effectively, the genre you input dictates the set of possible choices that will likely be made given possible choices that could be naively selected. Next, as the conversation grows, the model uses "left handed" context to generate the next responses. So, what you wrote previously will impact what comes next. This is important to consider when trying to edit a line that occurred early in the script; doing so might effect the remaining lines. If the last line is changed, then only that last line changes -> a human edit. If the second to last line changes, you can logically steer the response: 1. Bill what are you eating -> 2. lollipop! NOT 1. Bill what are you eating -> baseball was invented in 1900. The model can be thought of as a liar who replicates the patterns of words it has picked up from some training data. Allow it to lie along the lines that you want to hear by coaxing it into likely dialogues… what is likely might surprise you.
Have fun, and remember that not many people are exploring these sorts of tools. It is an untested space where there's a lot to be accomplished. There are no right answers as to how to use this tool as of right now. Explore!


