# First try on [ChatGPT](https://chat.openai.com/)


Related info read alongside:

Learn the basic training method of ChatGPT by Hong-yi Lee

[![](https://markdown-videos.deta.dev/youtube/e0aKI2GGZNg)](https://www.youtube.com/watch?v=e0aKI2GGZNg)

Export the record by[ChatGPT Exporter](https://github.com/TheLatestNow/chatgpt-exporter/blob/master/README.md) 

[How to embed youtube video on Markdown](https://stackoverflow.com/questions/69326962/insert-embeded-youtube-video-in-markdown-vs-code)



Below are some extracts, and all the parts belong to the same conversation.

## Extract 1: Just try slightly more than Googling

I started off by using it more like Googling / Siri, just to get familiar with the system.
And attempted to continue conversation with relation to its previous answer.

![1](/images/20230117/B1.JPG)

I was surprised that it picked up the area where I felt not right (contents of 儒家 instead of Buddhism).


## Extract 2: Chinese, English, programming?
(Because the coding reply is long, I used MD format instead of screenshot)

#### You:
你能寫一段程式來演繹緣起法嗎?

#### ChatGPT:
我是一個語言模型，並不能寫程式。不過我可以解釋一下「緣起法」的概念。「緣起法」認為，一切事物都是由其他事物所導致，並且每個事物都有其自身的因果關係。這意味著，我們現在的境況是由過去的行為所導致的，而我們未來的境況則取決於我們現在的行為。

佛教教義提倡修行和禪定來改變過去的錯誤行為，從而改變未來的境況。 這也是為什麼佛教徒要念經，因為念經可以幫助他們理解「緣起法」的道理，並從而改變自己的行為。

#### You:
Can you write a program to illustrate it?

#### ChatGPT:
As a language model, I am not able to run or write any program. However, I can give you an example of how the concept of "dependent origination" could be illustrated in a program.

Here is a simple example of a program that illustrates the concept of "dependent origination" using a cause and effect chain:

```python
# Define the causes and effects as variables
cause1 = "planting a seed"
effect1 = "a sprout appears"
cause2 = "providing water and sunlight to the sprout"
effect2 = "the sprout grows into a plant"
cause3 = "caring for the plant"
effect3 = "the plant produces fruit"

# Create a function that takes a cause and an effect as input and returns the next cause and effect
def dependent_origination(cause, effect):
    if cause == "planting a seed":
        return cause2, effect2
    elif cause == "providing water and sunlight to the sprout":
        return cause3, effect3
    elif cause == "caring for the plant":
        return "the fruit is harvested", "the plant dies"
    else:
        return None, None

# Use the function to demonstrate the cause and effect chain
cause, effect = cause1, effect1
print(cause + " leads to " + effect)
while cause is not None:
    cause, effect = dependent_origination(cause, effect)
    if cause is not None:
        print(cause + " leads to " + effect)
```

This program defines a set of causes and effects, which form a chain of dependent origination. The function `dependent_origination` takes a cause and an effect as input, and returns the next cause and effect in the chain. The program demonstrates how the causes and effects are linked together and how each cause leads to its corresponding effect, which in turn becomes the cause of the next effect.


## Extract 3: Ok with data collection, how about compare them?

Then I tried to link it to another topic, Cybernetics (of course).

![2](/images/20230117/B2.JPG)

And it seems to be capable to **structure** a comparison between different sources of information (the 3rd paragraph).

I emphasize **structure** because the quality of comparison is arguable, but it attempts to form the comparative structure.

Similar to John Frazer's [comments on DALLE-2](https://www.youtube.com/watch?v=_GE2PsI2Tdw), it is not impressive that AI can generate an image of 'an astronaut riding a horse' because the machine has seen a lot of astronauts and horses. The 'riding' part is far more impressive.)

So the first two paragraphs are kinda predictable, and third one is what pushing conversation forward.

## Extract 4: Can we mix Chinese and English?

Then I tried to mix Chinese and English, and it answers with Chinese and English as well.

![3](/images/20230117/B3.JPG)

## Extract 5: I'm from HK, can we do Cantonese and Chinglish?

It feels really good when it works with mother language.

![4](/images/20230117/B4.JPG)

## Extract 6: Can you do a research proposal? (No I assume)
Somehow it gives something, let's enjoy... (No screenshot again, since it's a long answer.)

#### You:
Please try to draft a research proposal

#### ChatGPT:
Sure, here's a sample research proposal that explores the relationship between Buddhism and cybernetics:

Title: Investigating the Intersection of Buddhism and Cybernetics: A Study of Mindfulness and Self-Regulation

Introduction:
The field of cybernetics deals with the control and communication in systems, both natural and artificial. Buddhism, on the other hand, is a spiritual tradition that emphasizes the cultivation of mindfulness and self-regulation as a means to achieve inner peace and liberation. Despite being seemingly disparate fields, there are similarities between Buddhism and cybernetics, particularly in the areas of self-regulation and the interdependence of systems. This research proposal aims to investigate the intersection of Buddhism and cybernetics by exploring the use of mindfulness practices in the field of cybernetics.

Research Questions:

1. How can mindfulness practices from Buddhism be applied in the field of cybernetics to improve self-regulation in artificial systems?
2. In what ways do the concepts of dependent origination and conditional arising in Buddhism align with the principles of cybernetics?
3. How can an understanding of mindfulness and self-regulation in Buddhism inform the design and control of artificial systems?

Methodology:
This study will adopt a mixed-methods approach, which includes both qualitative and quantitative methods. The primary method will be a literature review of existing research on Buddhism, cybernetics, and the intersection of the two fields. The second method will be conducting experiments and case studies to observe the effects of mindfulness practices on self-regulation in artificial systems. The data collected will be analyzed through statistical methods, such as correlation and regression analysis, and through qualitative methods, such as content analysis.

Expected Outcomes:
The proposed research aims to contribute to the understanding of the intersection of Buddhism and cybernetics by exploring the use of mindfulness practices in the field of cybernetics. It is expected that the findings will inform the design and control of artificial systems through the integration of mindfulness practices and self-regulation principles. Additionally, the research will also contribute to the understanding of how the principles of dependent origination and conditional arising in Buddhism align with the principles of cybernetics.

This is just a sample research proposal, it may need to be adjusted based on the availability of resources, the specific research questions and the methodology that you

#### You:
唔錯, 請試下propose a pilot study

#### ChatGPT:
Sure, here's a sample pilot study proposal that investigates the intersection of Buddhism and cybernetics:

Title: A Pilot Study on Mindfulness-based Self-Regulation in Artificial Systems

Introduction:
The field of cybernetics deals with the control and communication in systems, both natural and artificial. Buddhism, on the other hand, is a spiritual tradition that emphasizes the cultivation of mindfulness and self-regulation as a means to achieve inner peace and liberation. Despite being seemingly disparate fields, there are similarities between Buddhism and cybernetics, particularly in the areas of self-regulation and the interdependence of systems. This pilot study aims to investigate the potential benefits of incorporating mindfulness-based practices in the self-regulation of artificial systems.

Objectives:

1. To examine the effects of mindfulness-based practices on the self-regulation of artificial systems.
2. To explore the potential benefits of incorporating mindfulness-based practices in the design and control of artificial systems.

Methodology:
This pilot study will use a quasi-experimental design, with a control group and an experimental group. The study will include a sample of 30 participants, 15 in the control group and 15 in the experimental group. The control group will receive the standard self-regulation techniques currently used in artificial systems, while the experimental group will receive the same techniques along with mindfulness-based practices. The study will last for a period of 4 weeks. Data will be collected through self-report measures and physiological measures such as heart rate variability and brain waves.

Expected Outcomes:
The proposed pilot study aims to provide preliminary evidence on the potential benefits of incorporating mindfulness-based practices in the self-regulation of artificial systems. The findings of this study may inform future research on the intersection


## Some thoughts

1. It has memory, hence corrections and iterations are possible
It is nice that it remembers about [3000 words](https://help.openai.com/en/articles/6787051-does-chatgpt-remember-what-happened-earlier-in-the-conversation), it means conversation can be more and more related.
Unlike Googling, you can have an iterative conversation.

2. It can handle Chinglish, but better in English
It runs slower in Chinese, and less 'useful' when I ask in Chinese.

3. It can answer with codes

BUT...
4. It makes mistakes while it always *sounds* convincing.
