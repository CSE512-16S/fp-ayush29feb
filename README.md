Statistical Graphics Support For Vega-Lite
===============

## Team Members

1. Ayush Saraf (ayush29feb)

## Breakdown

I worked alone on this project along with guidance of Kanit Han Wongsuphasawat and Dominik Moritz the author of vega-lite. 

## Project

In this paper we present an extended grammar for primitive mark types like rule, bar and area to support ranged marks in vega-lite [1], a high-level grammar that enables rapid specification of interactive data visualizations. This extended grammar for primitive marks along with layering [1] in vega- lite then allows for representation of various statistical graphics like error bars, box and whisker plots, confidence intervals, difference charts, bullet graphs, candlestick plots and various other frequently used statistical graphics that are used in a various fields of study like computer science, statistics, financial risk analysis, perceptual psychology, semiotics and many others. we also present a new concept of composite marks in vega-lite to reduce redundancy of the specification grammar for most commonly used statistical graphics like error bars or traditional box and whisker plots. This helps in keeping the vega-lite specification maintain its concise nature.

Note: Currently Layering of Composite Marks in implemented. Its Dependent of the layer.ts which I haven't modifed yet.

[Poster](https://github.com/CSE512-16S/fp-ayush29feb/raw/gh-pages/final/poster-ayush29feb.pdf),
[Final Paper](https://github.com/CSE512-16S/fp-ayush29feb/raw/gh-pages/final/paper-ayush29feb.pdf)
[Code](https://github.com/vega/vega-lite/tree/ayush/stat-demo)
## Running Instructions

[Try it online](http://www.ayush.xyz/vega-editor-demo/?mode=vega-lite&spec=boxplot)