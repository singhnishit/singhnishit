---
title: "physicists on grokking"
date: "May 2026"
readTime: "2 min"
pinned: false
teaser: "got"
thumbnail: "public/assets/Screenshot 2026-05-10 at 6.02.20 AM.png"
---
List of papers mentioned : 
<a href="https://arxiv.org/abs/2303.11873">A Tale of Two Circuits: Grokking as Competition of Sparse and Dense Subnetworks</a>, Merill et al., 2023
<a href="https://arxiv.org/abs/2310.03789">Grokking as a First Order Phase Transition in Two Layer Networks</a>, Rubin et al., 2024
<a href="https://papers.nips.cc/paper_files/paper/2025/file/92f67b9047fa7a43d7506054b5f0ec6a-Paper-Conference.pdf"> Is Grokking a Computational Glass Relaxation? Zhang et al., NeurIPS 2025 </a>

A neologism is a new word, finding its way to the mainstream and being accepted as a new word in and of itself. Robots, utopias, agitprop[^2], are all examples of neologisms. The word "grok" came into existence because of science fiction[^1], and means "to understand intuitively or by empathy, to establish rapport with". Finding its way to scientific communities, the term "grokking" refers to the phenomenon where a neural network learns nothing for seeminlgy forever, and all of a sudden becomes all knowing. Skip to <a href="#nonphysicist">this</a> part if you already know about grokking.

A kid who is preparing for a multiplication test seemingly does well when you quiz them on questions like 13*7, or 17*9, but they flunk their test. You test them agian, they do well, but flunk again. They keep doing it for months, until one day they get a perfect score on the test. "What happened all of a sudden?" you ask, "I just memorised times tables up till 20, but they asked me questions from bigger numbers. I decided that I'd learn long multiplication yesterday." 

A neural network learns through loss. For a task, it takes an input, give you an output, and re-arranges itself according to _how wrong it is_. You train it by giving it a bunch of questions and then later revealing the answer, so that it could fix itself. What happens when it stops being wrong on your "test questions / test sets"? There is no loss (a measure of how wrong it was), and so the model doesn't correct itself. You then feed it newer questions it hasn't seen before, but it does terribly. If the goal is for the model to learn how to answer questions, we cannot keep showing it solutions to the answers, or we'd run out of questions. As fable goes, scientists left an experiment running when on vacation, and came back to see that it had "generalised", or was suddenly very accurate out of nowhere on unseen tasks. Nothing changed, except how long the model was trained for. This was termed as "grokking".


[^1]: [1] Robert A. Heinlein coined the term grok in his 1961 novel Stranger in a Strange Land as a Martian word that could not be defined in Earthling terms, but can be associated with various literal meanings such as "water", "to drink", "to relate", "life", or "to live", and that it had a much more profound figurative meaning that is difficult for terrestrial culture to understand because of the culture's assumption of a singular reality.[3]

According to the book, drinking water is a central focus on Mars, where it is scarce. Martians use the merging of their bodies with water as a simple example or symbol of how two entities can combine to create a new reality greater than the sum of its parts. The water becomes part of the drinker, and the drinker part of the water. Both grok each other. 

[^2]: [2] Agitprop is also a portmanteau of "agitation" and "propaganda", coined by the Russians.

