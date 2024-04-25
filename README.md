# Summative-Task-Trig
The program works by using the NumPy, and Matplotlib librareis in order to print the sin, cos, and tan graph in python
The program first defines the main function which is the gateway for the code
The program then prompts the user to select a trig ratio to grapg (sin, cos, or tan) if one of these options are not chosen it displays a message saying "equation not allowed only sin,cos,tan graphs"
The program then generates the graph by using the np.linspace code which makes the x axis in the range of -pi to pi with 500 points in sin and cos, 1000 for tan
The program then calculates the y axis value for the respective trig ratio
Then plots the graph using plt.plot(), showing the x and y axis
Then actually graphs the function allowing us to see it in the line plt.show()

#https://pythonforundergradengineers.com/plotting-sin-cos-with-matplotlib.html used this website to make sure that the trig functions plot in the intervals of pi, but in my case the range will go up 5*pi in order to see the graph better this was used for all sin and cos
https://stackoverflow.com/questions/54505852/how-to-plot-tanx-with-pyplot-and-numpy learned that using the np.linspace would not work with this because it deafaults to 50 elements in the given data set, this results in the graph elements being very widely spaced, instead used code that used both np.linspace in pi interavals with the plt.ylim line to limit the y axis to only 10, allowing for the proper printing of the graph of tan
https://stackoverflow.com/questions/42837910/omit-joining-lines-in-matplotlib-plot-e-g-y-tanx used this to get this line of code, otherwise the graph was printing with lines in between each tan interval  
