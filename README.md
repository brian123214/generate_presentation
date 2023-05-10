# generate_presentation

## Automatically generate powerpoint for english assignments (or any other assignment)

### 0. Before

Run ```pip install -r requirements.txt```
and get openai and stabilityai api keys


### 1. Input english assignment task:

Please read the assigned poem and create a presentation for the class. The presentation should take about 10-15 minutes and include the following: You must begin the presentation reading the poem aloud. Your slides must include but in no specific order: 1. an explanation of the title 2. identify an image and explain its significance to the poem 3. identify and explain three lines from the poem--image, meaning, 4.  provide biographical information about the author--current position, 5. engage the class with a question that they must answer in the written form- the question may be posed  6. include any images, videos, or sound that you think will enhance our 7. answer the question: Why did Billy Collins choose to include this poem in the collection?

### 2. Input background information (ex: poem)

I stopped to pick up the bagel\
rolling away in the wind,\
annoyed with myself\
for having dropped it\
as if it were a portent.\
Faster and faster it rolled,\
with me running after it\
bent low, gritting my teeth,\
and I found myself doubled over\
and rolling down the street\
head over heels, one complete somersault\
after another like a bagel\
and strangely happy with myself.\
\
—David Ignatow

### 3. Generate title and content plans
{'SLIDE 1: Title of Poem': ' Poem Title and author ',\
 'SLIDE 2: Meaning of Title': ' Explanation of the title and its significance ',\
...

### 4. Cool images
For generated content of each slide, extract a description of the most significant image and use that to generate an image

Significant image description: The bagel symbolizes a life of hard work and perseverance. David Ignatow's poem speaks of a bagel that was made by the baker's hands...

![image](https://user-images.githubusercontent.com/58054213/236599170-6cfe9d64-de49-482d-889f-0ab2c0b8dd75.png)

<img src="https://user-images.githubusercontent.com/58054213/236599445-3755acf7-cae3-4d66-9a5a-13976e000f3b.png" width="600">

Example slide
 
