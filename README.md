# Summative-Task-Trig
The program works by using the NumPy, and Matplotlib librareis in order to print the sin, cos, and tan graph in python
The program first defines the main function which is the gateway for the code
The program then prompts the user to select a trig ratio to grapg (sin, cos, or tan) if one of these options are not chosen it displays a message saying "equation not allowed only sin,cos,tan graphs"
The program then generates the graph by using the np.linspace code which makes the x axis in the range of -pi to pi with 500 points in sin and cos, 1000 for tan
The program then calculates the y axis value for the respective trig ratio
Then plots the graph using plt.plot(), showing the x and y axis
Then actually graphs the function allowing us to see it in the line plt.show()
