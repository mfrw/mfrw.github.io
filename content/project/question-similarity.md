+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Question Similarity (Quora Dataset)"

# Project summary to display on homepage.
summary = "Deep Learning"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "deep-learning/dl.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["deep-learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

We developed a model using deep learning and IR techniques to identify similarity of question. The dataset used for this project was the Quora-Question Similarity Dataset. We also trained the model on the MSRP, and the final accuarcy of our model was close to 80%. The current state of the art is at 85%. The approach we took is a vectorized the words, then fed it into a Bi-LSTM and trained the model on a GPU using tensorflow as backend. <p>
Advisor: Dr. Harshit & Dr. Sameep (IBM Research Labs)
