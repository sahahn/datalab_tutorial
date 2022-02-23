---
title: Tutorial
---

## Basic Tutorial


We can add different content on seperate pages easily
[Link to base tutorial](./original_index.md)


We can also change how text looks with HTML
{: style="font-size: 85%; text-align: center;"}

## Basic Plot Example

Can plot based on a link to anywhere on web, so in first case, to static link on github (https://raw.githubusercontent.com/sahahn/datalab_tutorial/gh-pages/basic_plot.png)
![arbitrary link](https://raw.githubusercontent.com/sahahn/datalab_tutorial/gh-pages/basic_plot.png)

Otherwise, we can show the image with a relative link, but this means we need to save it in the docs folder (/basic_plot.png)
![rel link](./basic_plot.png)

## Plotly / Interactive Figure Example


We can add the figure using includes
{% include plotly.html %}

And / or if we add the html in the docs folder, we can link to it directly
[Link to its own page](./plotly.html)


## Map Example


{% include example_map_iframe.html %}
{: text-align: center;"}

