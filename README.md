# UI Layers Merger: Merging UI Layers via Visual Learning and Boundary Prior

Official Repo of “UI Layers Merger: Merging UI Layers via Visual Learning and Boundary Prior”

## UILM Dataset

UILM dataset is an annotated dataset containing high-fidelity fully designed UI screenshots and corresponding annotations with bounding boxes. It differs from other UI datasets because we obtain the UI screenshots and the view hierarchies by parsing the UI design drafts from modern design tools such as Sketch. By incorporating the boundary information of the layers into UI screenshots, we boost the detection performance of the merging area detector.

Since most of the UI design drafts in this work are provided by Alibaba Group and subject to the company's agreement, we only release part of the dataset here for model testing. Data is picked completely randomly. Note that Downloading and using the provided data is subject to the MIT license, if you need the full dataset, please contact the authors of the [paper][https://arxiv.org/].

In this repo, we release a total of 329 UI samples and 2 Sketch files. The UI samples consist of default images and images with boundary segmentation. The annotated Sketch files enable the user to reproduce the complete data processing pipeline and the annotated UI screenshots allow the user to test our model simply. It includes the following:
* 2 well-designed Sketch files
* 329 screenshots of high-fidelity UI design drafts

[Download_link](https://drive.google.com/file/d/13FjcYrc1YXGwO5w2c2WxnN8wIAZLtlCJ/view?usp=sharing)

