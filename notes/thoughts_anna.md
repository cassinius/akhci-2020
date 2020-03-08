Bernd Malle, [08.03.20 19:45]
I actually have a lot of potential work for students within my experimental / product pipeline => BUT most of it is interdependent and most of it is still in fragments, so it's a little hard to carve out a well-defined, succint work-packages suitable for students

Bernd Malle, [08.03.20 19:54]
Andreas , Anna What do you think of:

1) training embeddings for different categories of product datasets (maybe a bit boring...?)
2) Visualizing embeddings with different methods and examine their properties / explain how the model discriminates (as a pre-cursor to automated eX-AI
3) (similarity) graph construction out of embeddings & some pre-determined rule-sets (the idea here is to use the embedding as a link-prediction mechanism
4) sub-graph visualization - as a user searches for products & reacts to recommendations, the graph updates & becomes more personalized => the result could be cool graph animations over time
5) embedding personalization -> as users interact with recommendations, we generate signals for our underlying embeddings, using the human interaction like a streaming dataset for transfer learning on the pretrained embeddings (this is probably the coolest, however, I have hardly scratched the surface myself here, so maybe too early to do that?)

Bernd Malle, [08.03.20 19:56]
which 1 or 2 would you pick?

Anna Saranti, [08.03.20 20:17]
First things first: Reading of all the papers: AT LEAST: https://docs.dgl.ai/tutorials/models/index.html#graph-neural-networks-and-its-variants

Anna Saranti, [08.03.20 20:18]
In parallel trying the code examples, and some stress tests: How big/complex can the graphs get?

Anna Saranti, [08.03.20 20:19]
1) and 2) is mandatory, but I will go beyond that and viz what is *relevant* for any task, starting with classification

Anna Saranti, [08.03.20 20:20]
Topics 4 and 5 are not interesting to me at the moment - even better if you want to work on that topic, because there will be no overlap.

Anna Saranti, [08.03.20 20:22]
The main question for me is: Which parts/properties of the graph are *decisive* for the target ML task => Whatever that might be. It can be classification (f.e.: This graph is 80% symmetric), it can be link prediction and go through captioning.

Anna Saranti, [08.03.20 20:23]
The visualization, recommendation and personalization come after that in the pipeline - highly important, but not the core of my work.

Bernd Malle, [08.03.20 20:28]
Anna I meant which of these topics would make a good mini-project for the AK-HCI class in your opinion 😉

Anna Saranti, [08.03.20 20:29]
I thought you were talking specifically about GNNs

Anna Saranti, [08.03.20 20:30]
For the mini-projects I would keep it simple and DON'T give concrete tasks

Anna Saranti, [08.03.20 20:31]
A small group of students can pick [1.] An NN according to their interests. It can be a GAN, an LSTM, a CNN, whatever they like. And [2.] Apply one eXAI methods that they pick, from the list of Papers that Andreas has in the Website of the course

Anna Saranti, [08.03.20 20:32]
Apply it - be hands on - show the insights they've got, according to the domain of interest.

Anna Saranti, [08.03.20 20:33]
If they want to do eXAI they all should have some background in NNs, they should have built something in this area and they can use one method that sheds light to an aspect that they like, to produce results.
