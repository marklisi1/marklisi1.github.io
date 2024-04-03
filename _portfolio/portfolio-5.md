---
title: "Moonboard ML: Generative AI in...rock climbing?"
excerpt: "CNN to predict moonboard grades and a variational auto-encoder to generate a route given a grade! TensorFlow, Keras...bouldering"
collection: portfolio
---
If it wasn't obvious from the title, I love rock climbing! This project is a fun little stab at crossing it with my other favorite hobby: machine learning. A Moonboard makes climbs by selectings holds from a fixed 18x11 grid - by representing climbs as an 18x11 matrix of ones and zeroes, we can do some computation with them. Climbs are graded on a numerical scale, so it was natural to use those grades as labels. I created a convolutional neural network capable of predicting the grade of a climb within 1 grade with nearly 90% accuracy on limited training data.

This project is ongoing - I'm currently working on a variational auto-encoder capable of performing this process in reverse; that is, given a grade, generate a climb that resembles that grade.

[You can look at the code I used for this here!](https://github.com/marklisi1/moonboard-ml)

* Skills: Generative AI, model architecture, strong fingers
* Tools: TensorFlow, NumPy, Moonboard :) 
