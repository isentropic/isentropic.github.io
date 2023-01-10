---
title:  "Learning goals for 2023"
date:   2023-01-10
---
2023 is already here, another year to learn something new in today's endless sea
of online resources. This blog-post will list some of my favorite findings
online and mini-learning projects that I want to finish or at least try out for
this year. 

## Neural Nets
Now that ChatGPT and language models closed out 2022 with much hype, there is
one resource that cannot be recommended more.  Andrej Karpathy's
[makemore](https://github.com/karpathy/makemore) is a fantastic learning
resource for language models.  His [youtube
channel](https://www.youtube.com/@AndrejKarpathy) is nothing short of the
greatest introduction to neural networks and how to train them. 

He starts off by going back to basics by first building his own auto-diff
[micrograd](https://github.com/karpathy/micrograd) framework.  Next he smoothly
transitions into using basic pytorch `tensor` objects while gradually building
complex layers from scratch.  He underlines the subtleties of training neural
nets throughout the series while delivering the content in bite-size pieces.
10/10. 

A cool learning project is to re-implement makemore in some other
[framework](http://lux.csail.mit.edu/stable/) using your favorite
[language](https://julialang.org/).

## Clojure
[Clojure](https://clojure.org/) is great language that is extraordinary:

1. It is a (lisp) -> Minimal yet infinitely extensible syntax.
2. It is functional -> Avoids state, makes concurrency easier.
3. Runs on JVM -> Production ready.
4. Transpiles to JavaScript via clojurescript -> Let's you write fullstack.
5. Consistently stays somewhere around top 5 in [most
   loved](https://survey.stackoverflow.co/2022/#technology-most-loved-dreaded-and-wanted)
   for a few years.

Clojure's functional lisp lets you start thinking differently about the code. It
is opposite to standard imperative non-lisp style in many ways.  There is no
need to oversell this more.

## Web dev
For people like me who never did webdev and cloud technologies, this is might
sound like an odd choice, but I want to feel what it is all about. There are
tons of frameworks and jargon around this topic and it might feel daunting to
start. With the goal being to know more than throwing a few fancy words here and
there, I should create a basic ledger/gallery/utility webapp hosted on the
cloud.

There a million step-by-step tutorials for pretty much all the major frameworks,
but my goal is to create something out-of-tutorial land. 


## Federated learning
[Federated learning](https://en.wikipedia.org/wiki/Federated_learning) is
an idea to train ML models with decentralized data. [Tensorflow
federated](https://www.tensorflow.org/federated) stands as one of the few
frameworks supporting this. Federated learning shows a lot of potential and it
is definitely on my radar.
