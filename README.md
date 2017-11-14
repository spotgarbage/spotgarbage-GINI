# spotgarbage-GINI
Garbage In Images (GINI) Dataset

Contents

1. garbage-queried-images.csv - List of images crawled using garbage related queries. Each image has the following attributes: image,query,label,startX,startY,endX,endY

Label and bounding box parameters both are empty if the image is not annotated at all.

2. non-garbage-queried-images.csv - List of images crawled using non-garbage related queries. Each images has following attributes: image, query.

3. garbage-queried-images-spotgarbage.csv - List of garbage queried images using in the SpotGarbage paper.

4. ambiguous-annotated-images.csv - List of garbage queried images ambiguously annotated by users.

The folders 'garbage-queried-images' and 'non-garbage-queried-images' which contain the dataset images arranged in folders corresponding to the search query used to crawl them.

The folder 'ambiguous-annotated-images' contain the images ambiguously annotated by users.

If using this dataset, please cite SpotGarbage project

G Mittal, K B Yagnik, M Garg, and N C Krishnan, Spot Garbage: Smartphone App to Detect Garbage Using Deep Learning, ACM International Joint Conference on Pervasive and Ubiquitous Computing, 940-945, 2016

