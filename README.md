# ILSVRC2012 Labels

`ILSVRC2012_validation_ground_truth.txt` contains class labels for the ImageNet val set (the one that usually gets downloaded).
It uses the mapping in `ILSVRC2012_mapping.txt`.

I use `imagenet_class_index.json` as image classes to interop with the robustness library (https://github.com/MadryLab/robustness).

`words.txt` contains mapping from wordnet IDs to text descriptions.

`wordnet.is_a.txt` encodes the wordnet hierarchy.
