# nilearn_test
I'm doing a simple comparison between adults and children activation patterns from an arbitrary fMRI dataset.

Dataset taken from:
Hilary Richardson, Grace Lisandrelli, Alexa Riobueno-Naylor, and Rebecca Saxe. Development of the social brain from age three to twelve years. Nature communications, 9(1):1–12, 2018.

 This is what I'm doing:
1. Importing 10 adult and 10 child 4D images (multiple images per individual) from arbitrary dataset
2. Constructing a single mean image per individual
3. Constructing a single mean image for each group (adult vs child)
4. Diplaying the group means side-by-side
