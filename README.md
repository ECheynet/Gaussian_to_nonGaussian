# Gaussian_to_nonGaussian

[![View Non-Gaussian process generation on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://se.mathworks.com/matlabcentral/fileexchange/52193-non-gaussian-process-generation)
<a href="https://www.buymeacoffee.com/echeynet" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 25px !important;width: 120px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

A non-Gaussian distribution is generated from a Gaussian-distributed white noise


## Summary

The method used in these files is based on the Moment Based Hermite Transformation Model (MBHTM) and uses a cubic transformation to transform a Gaussian process into a non-Gaussian one. It is described in [1]. However, I mainly rely on [2] for the implementation of the code. A target skewness and a target kurtosis are used to introduce non-Gaussianity. However, the transformation only works for a limited range of skewness and kurtosis. See [2] for more details.

## Content
Two files are included

- MBHTM.m which is the main function to generare the non-Gaussian process

- Documentation.mlx which is the example file

## References

[1] Gurley, K. R., Tognarelli, M. A., & Kareem, A. (1997). Analysis and simulation tools for wind engineering. Probabilistic Engineering Mechanics, 12(1), 9-31.

[2] Denoël, V. (2005). Application des méthodes d'analyse stochastique à l’étude des effets du vent sur les structures du génie civil. Unpublished doctoral thesis, University of Liège. (in French, p. 229)
