# RNN-Based-Molecule-generation
Generate molecular formulas for de novo-drug discovery.

  - Bayesian models like graphical models.
  - Recurrent models (for sequence generation like texte).
  - Variational auto encoders.
  - Generative adversarial models.
  - Flow and diffusion models.
In the hands-on we will start by trainning a character based RNN to generate smile molecules

We want to feed smile representations of molecules to an RNN. The basic idea is we will train it to predict the next smile token of a molecule given the previous one.

For instance for the following molecule "CC(=O)NC1=CC=C(O)C=C1" will may give to the model

X = "CC(=O)N" y = C

and ask the RNN to learn to predict y given X
