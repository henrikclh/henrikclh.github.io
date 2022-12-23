# Second try on [Stable diffusion](https://forums.fast.ai/t/lesson-9-part-2-preview/101336)

Continuing on the last try on stable diffusion, I was thinking 'how can I use it in a design process?".
Instead of typing prompts to generate images, a designer might more likely to start designing by sketches!

Therefore, I tried to simplify and tweak [Fast.ai version](https://colab.research.google.com/drive/1TFRk0U3BsefwpYlGSZfQmfXY3ZM2B34h?usp=sharing) for such purpose.


## Step 1. Upload own sketch (or image found online)
First, the initial image can be uploaded via:
(1) image link, which is handy if found images online
(2) simply upload an image onto Colab (on left hand side)

For example, I did a 30-second sketch (again, based on my [final year project](http://www.presidentsmedals.com/Entry-53841) )

![01](/images/20221220/20221220_01.png)

## Step 2. Add texts and adjust strength

Then I used the prompts "future sculpture, zaha hadid style".
After testings, I felt strength between 0.5 and 0.8 gave more controllable and 'understandable' results, therefore, I preset it tested both initially.
1st row: strength = 0.5
2nd row: strength = 0.8

![02](/images/20221220/20221220_02.png)
![03](/images/20221220/20221220_03.png)

## Step 3. Pick one and iterate with further texts

For example, I chose a pavilion-look image and further added stairs.

![04](/images/20221220/20221220_04.png)

(Prompts = "future building, zaha hadid style, with staircase")

![05](/images/20221220/20221220_05.png)

Just tried to pick a favourite one, somehow it both got the staircase location correctly, and added glass balustrade, which was weird but great.

![06](/images/20221220/20221220_06.png)

## Thoughts
Personally I think it makes more sense in this workflow because it feels more designerly using both **image and text** as inputs.
Instead of the original one, which felt like just 'Pinterest with more images'.

![overall](/images/20221220/20221220_overall.jpg)

Just for fun, I attempted to use a more sculptural-looking image and attempted to turn it into a building.
Chosen image:

![07](/images/20221220/20221220_07.png)


(Prompts: "future building, zaha hadid style, with staircase, blue sky".)

![08](/images/20221220/20221220_08.png)

Looks like can be better, but didn't want to put in further efforts before fine-tuning the model...

![09](/images/20221220/20221220_09.png)

## Further development

The first thing comes to mind is: ***FINE-TUNE*** the model.
Without it, designers were just playing with others' software without own design intention input into the Stable Diffusion model.

