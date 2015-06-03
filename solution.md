Solution
--------

The simplest explanation of the answer I've seen so far is this:

There are two options for the pair of coin flips: Alice and Bob flipped the same, or they flipped differently.
The winning strategy is for one of them to guess assuming they flipped the same, and the other to guess that
they flipped differently.

Let's assume Alice guesses they flip the same, and Bob guess they flip differently.
Now let's look at some truth tables:

         A    B
Flip:    H   [H]
Guess:  [H]   T

Alice flips a head, so she guess that Bob also flipped a head. Bob flips a head, and so guesses that Alice 
flipped a tail. Turns out Alice's guess is correct, as indicated with brackets. 

Let's look at the remaining truth tables:

         A    B   |    A    B   |    A    B
Flip:   [H]   T   |   [T]   H   |    T   [T]
Guess:   H   [H]  |    T   [T]  |   [T]   H
