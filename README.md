# Cohere Vegetable Classifier

I love embedders, and I heard Cohere has the best.

In this notebook, I played around with the Cohere large embedder to see if I could classify vegetables using unsupervised clustering with the embeddings.

The results were interesting, with the clustering algorithm recognizing 6 distinct veggie classes, that correlated mostly to how humans may classify them.
They are

0: Legumes

1: Herbs and spices

2: Leafy greens and brassicas 

3: Squashes + fruit

4: Peppers

5: Root vegetables
![image](https://user-images.githubusercontent.com/60330250/191150052-54ff32d5-c547-4140-9905-2c26352b0464.png)
![image](https://user-images.githubusercontent.com/60330250/191150063-ad359158-15e5-4e0d-ab3d-c9735a88cb9d.png)

Moral of the story, it seems legumes occupy quite a distinct dimensional space compared to other vegetables, legumes are unique and cool!
