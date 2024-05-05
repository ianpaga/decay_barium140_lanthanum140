Monte Carlo simulation of the exponential decay of Ba-140 & La-140 
====

Description: The code computes the probability of decay as a function of time (years) for the Ba-140 (Mother) and La-140 (Daughter) isotopes. It computes the probability distribution functions (PDF)
and the cumulative distribution functions (CDF) of both isotopes as a function of time. With the code, we perform Monte Carlo simulations (MC) of the decay using 1 million events and record
the number of counts for the decay events of Ba-140 and La-140. 

To compare that the MC simulation gives correct results, we can compare with the experimentally known half-lifetimes of Ba140 = 12.8 days and La140 = 1.6781 days.
With these lifetimes, one can simply check the MC results and plot them on top of the analytical solutions exp(-lifetime * t) and see if it is a good match and quantify the error
between the analytical curve and the MC-predicted curve. 

See figures in /plots for explicit results. You can also run the Jupyter notebook Ba-140_La-140.ipynb yourself.

## Figures:

![decay_6](https://github.com/ianpaga/decay_barium140_lanthanum140/assets/57350668/ca7019d4-7798-4373-a9df-987ebe73be76)
![decay_5](https://github.com/ianpaga/decay_barium140_lanthanum140/assets/57350668/d02300e8-a918-4302-bfc2-1c40e91f8a44)
![decay_4](https://github.com/ianpaga/decay_barium140_lanthanum140/assets/57350668/26be608d-908c-4e73-8535-895703b652ad)
![decay_3](https://github.com/ianpaga/decay_barium140_lanthanum140/assets/57350668/357bef23-8207-4330-a354-a640c8d04661)
![decay_2](https://github.com/ianpaga/decay_barium140_lanthanum140/assets/57350668/3762c83d-8b0b-4c84-920f-22f2b4df27ed)
![decay](https://github.com/ianpaga/decay_barium140_lanthanum140/assets/57350668/3cb39e2f-2d90-4278-a446-a7fdf021b6f8)

## Requirements:
- Plotly
- Python, NumPy
- "uncertainties" python package (pip install uncertainties)

  Running this notebook code will generate plots in /plots.
