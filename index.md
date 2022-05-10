# Musika! 
# Fast Infinite Waveform Music Generation

**Abstract**
Music generation in the waveform domain is a computationally intensive task, considering the inherent high dimensionality of audio data. State-of-the-art music generation systems require large amounts of data to be trained on, massive computational resources for training, and extremely slow times for the generation process. These characteristics represent an important obstacle for real-world usage of powerful music generation tools. In this work we introduce Musika, a music generation system that is able to be trained on attainable amounts of data using a single consumer GPU, and that allows for much faster than real-time generation of music of arbitrary length, on both GPU and CPU. We achieve this by first training one or more autoencoders in a hierarchical fashion to reconstruct full spectrograms, aiding the reconstruction process with an adversarial objective. A Generative Adversarial Network is finally used to generate the resulting compressed invertible representations of a particular music domain. A latent coordinate system is introduced to achieve infinite-length music generation, while a global context vector allows the generated music piece to remain stylistically coherent through time. We perform quantitative evaluations to assess the quality of the generated samples and show how the system can be used for real-world applications. We release the source code and the weights of the pretrained autoencoders, such that a GAN can be trained on a new music domain with a single GPU in a matter of hours.


<!-- ## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/anonymous2732/anonymous2732.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/anonymous2732/anonymous2732.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
 -->
