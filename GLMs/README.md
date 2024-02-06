# Generalized linear models
### [John Vastola](https://johnvastola.com) and [Kiah Hardcastle](https://www.kiahhardcastle.info/home)

In neuroscience, statistical models are essential for making sense of the complex link between neural activity and things in the world (e.g., animal behavior). Among the most useful statistical models are linear ones, because (i) they are simple, and (ii) they are interpretable. [Generalized linear models](https://en.wikipedia.org/wiki/Generalized_linear_model) (GLMs), not to be confused with [general linear models](https://en.wikipedia.org/wiki/General_linear_model), are a slight complexification of the idea of linear models, and are widely applied in neuroscience. In this session, our goal is to cover the basic theory and a simple application to real neural data. 

The coding exercise is based on a notebook originally by [Shih-Yi Tseng](https://github.com/sytseng). See [here](https://github.com/sytseng/GLM_Tensorflow_2) for an extremely helpful GLM repo she made that includes both high-quality code and GLM-related tutorials.


**Helpful tutorials**:

[2016 SFN tutorial on GLMs by Jesse Kaminsky and Jonathan Pillow](https://github.com/pillowlab/GLMspiketraintutorial_python)

[Neuromatch Academy GLM tutorial, part 1](https://compneuro.neuromatch.io/tutorials/W1D3_GeneralizedLinearModels/student/W1D3_Tutorial1.html)

[Neuromatch Academy GLM tutorial, part 2](https://compneuro.neuromatch.io/tutorials/W1D3_GeneralizedLinearModels/student/W1D3_Tutorial2.html)


**Relevant papers**:

[1972 Nelder and Wedderburn] [Generalized Linear Models](https://www.jstor.org/stable/2344614), statistics paper that first introduced GLMs

[2018 Zoltowski and Pillow] [Scaling the Poisson GLM to massive neural datasets through polynomial approximations](https://proceedings.neurips.cc/paper_files/paper/2018/hash/3fab5890d8113d0b5a4178201dc842ad-Abstract.html), recent-ish paper scaling GLM fitting to large data sets

[2017 Hardcastle et al.] [A Multiplexed, Heterogeneous, and Adaptive Code for Navigation in Medial Entorhinal Cortex](https://doi.org/10.1016/j.neuron.2017.03.025), application to data from medial entorhinal cortex

[2022 Tseng and Chettih et al.] [Shared and specialized coding across posterior cortical areas for dynamic navigation decisions](https://doi.org/10.1016/j.neuron.2022.05.012), application to data from posterior cortex