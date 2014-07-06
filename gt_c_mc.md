group theory: convergent markov chains.



## Experiment:

A) have each state transition to 1 state, 100% probability

B) have each state transition to 3 states, split probability.

C) have each state transition to 3 states and noise, 30/30/30 10% noise (random other)

D) have the intelligence broach new states which can 
alter the probabilities for the next state or subsequent states.

## First Experiment

We have an extensible expectation matrix, and
a return ratio for the investment in the correct
guess.


## Cap on Stored Energy as incentive to forward plan
One has the option to place saved energy (stored energy from the multiplier) in future, we may introduce a handle
which caps or progressively taxes higher energy states.

basically we can start with a cap, which creates incentive for forward investment after a certain level (as this is permanently stored energy if it is correct).

(In life higher energy levels can make one volatile.)

## Details of first experiment/Spec

Monte Carlo exploration (like random flash cards for vocabulary), then creative reconstruction.

At first you have bins/states, option 1, option 2, and noise.  the number of non-noise options needs to incur some cost or energy (perhaps checking these takes time, and time takes energy), and creating an incentive to reduce the number of top possibilities.

At first we can maybe have 7 such states, and a noise category.  At first when a state is added, it has a high probability, so introduction to the topic is really important.  Rejecting probabilites one way to accomplish will be to decrease the probability of transitions to these states, which incurs energy/memory allocation/cost.

Reducing the chance of noise is also interesting, so this makes the result dependent on traning set.



## Spec Spec

7 bins 8 noise. when a new state is introduced in stage 1,
we have a simple collection of probability and a chance to filter out noise by weighting tried and true guesses to stay on board, and shucking the lower probabilities to the noise bin (if noise bin reaches a certain probability, then we increase the number of tracked states).

we can actually scale up from 1 possibility, and experiment with starting at 2 or 3, to reduce the overhead from having to expand the matrix due to inevitable noise from multiple probable outcomes.

algorithm for that, start out with if probability of noise is over 70% (resetting trials to being 20 long) then we expand the possibilities by 1.  If the probability of noise is lower than 10% then we may attempt to reduce the possibilities by 1.

There is also a balance between breadth and depth, and the effective use of energy for future plans.  Let us make a decision  (can test this later) not to explore implications of noise (can explore this later).  Limiting this to only the probable outcomes, then we will lose energy by doing more breath even if a small probability designates small piece of the pie.  We can weed out those bins which do not pay off after a certain amount of trials.


## high risk high reward modelling

Right now all possibilities are being treated as equal, but in reality some paths are more high stakes than others.

How to model this.. hmm, perhaps certain paths can lead to more depth with less breadth, we can model this by having tdifferent ambiguity for different states (3 paths + random vs 1 path + random, vs 1 path period).

This way you can save energy in the long run by betting probablistically disproportional amounts on these low probability outcomes.

This might become important as we introduce broaching, since one can potentially take part in reducing the alternate possibilities and planning very far ahead, by "betting" on broaches which will narrow the possibilities, and prepare routes as well towards ameliorating your broaches with the hiprobable results.


## Goal: convergence with global mastery.


The goal is not only to have all of the associations, but to match as closely as possible the global markov matrix.

### Rules for broaching, hanging state introduced

needs to be resolved, blocks the continuation of state until a route connects this state with the current transition.

How does it's transition probability's alter the next state?

it is a marriage of the broached word's probability with the interlocutor's next probability.

The other bin might have a large percentage, then the conversation can crash.

1) Broached word first associations alone to a connection to next topic (6 degrees).

2) Broached word with context associations, permutations of markov chains with the words in the topic, and finding a route/path between the broached word and the target state.  This is used typically for seeing if you're on the same thread.

3) Under a "Lens" might be including the "Lens" word/topic/Markov-Matrix as a first filter for the subsequent associations.

4) learning the rhythm (the operator/operator-combination) for transitioning states, is important as well for keeping on the same thread.
