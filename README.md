# hyperspy
[hyperspy.org](http://hyperspy.org/)
## to install hyperspy

```
$ conda config --add channels conda-forge
$ conda install hyperspy
```
  
in order to make the use of interactive utility, we need to 

```
%matplotlib qt4
```

at first in jupyter notebook, so what we further need is PyQt4 module. to install it,

```
conda install pyqt=4
```

### first glimpse of hyperspy

- [hyperspy-1-try.ipynb](https://github.com/Kouui/hyperspy/blob/master/hyperspy-1-try.ipynb)

### Signal1D Tools

- [hyperspy-2-Signal1D-Tools.ipynb](https://github.com/Kouui/hyperspy/blob/master/hyperspy-2-Signal1D-Tools.ipynb)

### Data Visualization

- [hyperspy-3-data-visualization.ipynb](https://github.com/Kouui/hyperspy/blob/master/hyperspy-3-data-visualization.ipynb)
### Machine learning

-[doc - machine learning](http://hyperspy.org/hyperspy-doc/current/user_guide/mva.html)
  - PCA
  - scree plot
  - denosing using PCA
  - robust PCA
  - Non-negative matrix factorization
  - Blind Source Separation
  - Visualizing results

### Model fitting

- [doc - model fitting](http://hyperspy.org/hyperspy-doc/current/user_guide/model.html)
  - 1D curve fitting and 2D image fitting
  - components of 1D model (**multi component fitting is also available!!**)
    - EELSCLEdge, VolumePlasmonDrude, PowerLaw, Offset, Exponential, ScalableFixedPattern, Gaussian, GaussianHF, Lorentzian, Voigt, Polynomial, Logistic, Bleasdale, Erf, SEE, Arctan, HeavisideStep
    - man-made model
  - features of curve fitting optimizer
    [table](http://hyperspy.org/hyperspy-doc/current/user_guide/model.html#id3)
  - [visualizing model](http://hyperspy.org/hyperspy-doc/current/user_guide/model.html#visualizing-the-model)
  - [fitting multidimensional dataset](http://hyperspy.org/hyperspy-doc/current/user_guide/model.html#fitting-multidimensional-datasets)
  - [Smart Adaptive Multi-dimensional Fitting (SAMFire)](http://hyperspy.org/hyperspy-doc/current/user_guide/model.html#smart-adaptive-multi-dimensional-fitting-samfire)
  
