# herd-immunity [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/philip-mach/herd-immunity/master?filepath=notebooks/herdImmunity.ipynb)

Simple calculation of herd immunity vs. basic reproduction rate *R*<sub>0</sub> (assuming *E*=1, i.e., all who are exposed and recover are immune):

<img src="https://render.githubusercontent.com/render/math?math=P_{herd}=1-\frac{1}{R_0}">

Source:
Paul Fine, Ken Eames, and David L Heymann.  “Herd immunity”: a rough guide. *Clinical Infectious Diseases*, 52(7):911–916, 2011

You can also run my example of what would have happened to the United States had exponential growth continued from 20 March 2020; the code to graph doubling time in the US through March is included with that example.

To view or run the Python code, click on **launch binder**, which will open a Jupyter Notebook. This may take a while the first time you do it as the environment must be created. You can edit and rerun within the binder but it has quite a short time out after which you lose any changes.

Once in the binder, you can choose Open… from the File menu and launch “US worst case.ipynb” to find the other examples.

To get best results if you want to modify the code, download to your own machine:

`git clone https://github.com/philip-mach/herd-immunity.git`

For the command-line challenged, there are [Git apps](https://desktop.github.com) out there. You will also need a local intall of [Jupyter](https://jupyter.org).
