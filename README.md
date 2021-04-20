# sbi_tutorial
Tutorial on how to craft your summary statistics for simulator-based inference.

## What you can lean here
In the added notebook `tutorial.ipynb` you find two simple examples that illustrate the importance of crafting your summary statistics when you use simulator-based inference (sbi). This notebook is not intended to give you a one 'size fits all' approach. In fact it argues against this: it argues for the modelling analyst to carefully construct their summary statistics in order to (i) further help the analyst understand his observed data, (ii) help him discover exactly what he wants the model to recover from the observation and (iii) dramatically help the inference framework itself.
<br>
<br>
In the end you are encouraged, with what you've learnt, to further improve on the 2nd example: tuning the parameters of a passive Hodgkin-Huxley model in order to match the observation.
<br>
<br>
## What you need
Everything is just Python code. It's all just one notebook. All the models are even run in Python itself. The only requirement you need is a basic understanding of simulator-based inference [sbi](https://www.mackelab.org/sbi/) and [install](https://www.mackelab.org/sbi/install/) it.

