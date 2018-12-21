## Abstract

This paper addresses the challenge of dense pixel correspondence estimation between two images. This problem is closely related to optical flow estimation task where ConvNets (CNNs) have recently achieved significant progress. While optical flow methods produce very accurate results for the small pixel translation and limited appearance variation scenarios, they hardly deal with the strong geometric transformations that we consider in this work. In this paper, we propose a coarse-to-fine CNN-based framework that can leverage the advantages of optical flow approaches and extend them to the case of large transformations providing dense and subpixel accurate estimates. It is trained on synthetic transformations and demonstrates very good performance to unseen, realistic, data. Further, we apply our method to the problem of relative camera pose estimation and demonstrate that the model outperforms existing dense approaches.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AaltoVision/dgc-net-site/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
