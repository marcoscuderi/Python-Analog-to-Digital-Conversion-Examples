# Analog-to-Digital-Conversion-Examples

These are a series of notebook that I have developed to explain in my course the concept of digitalization of a continous analog signal.   
The first notabook L08 is about sampling frequency, aliasing, Nyquist theorem and sample and hold.  
The second notebook is about signal quantization with an hypothetical encoder. 
Feel free to contact me for questions.  


The notebook use Jupyter Widgets to allow the user to interact with the plot. 
If you haven't done yet, here are the instructions to install what you need to run these notabooks.  

First step is to add the widget finctionality to your Anaconda package manager.  

1. Install nodejs, e.g. **conda install nodejs**.  
2. Install ipympl, e.g. **conda install ipympl**.  

3. Install extensions:  
Run the bold commands in the anaconda prompt and follow instructions if necessary.  
**jupyter labextension install @jupyter-widgets/jupyterlab-manager**  
**jupyter labextension install jupyter-matplotlib**  
Enable widgets: **jupyter nbextension enable --py widgetsnbextension**.  

Restart JupyterLab.  
Decorate with **%matplotlib widget**.  

If you find any problems please try to resolve yourself and don't give up. This is the only way to learn !!  
Some useful resources can be found at:  
- https://ipywidgets.readthedocs.io/en/latest/user_install.html  
- https://stackoverflow.com/questions/49542417/how-to-get-ipywidgets-working-in-jupyter-lab  
- https://stackoverflow.com/questions/50149562/jupyterlab-interactive-plot  
and if you don't find the answer here, internet is a beautiful place to find answers.
