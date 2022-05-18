Neural_Network
=
The artificial neural network predicting activation energies in hydrogen atom transfer based sp3 C-H activation.

Dataset availability
=
Density functional theory calculations (UωB97X-D) are used to establish the reaction system dataset of methoxyl, trichloroethoxyl, trifluoroethoxyl, tert-butoxyl and cumyloxyl radicals. Optimized cartesian coordinates are available in “cartesian coordinates of DFT-computed structures.zip”.

How to use the model
=
1. Creates and trains a neural network object :\
trainNN(nn, P, Y)\
Parameters:　nn (list) - Short notation of the neural network\
　　　　　　P - Input data set\
　　　　　　Y - Output data set

2. Use a trained neural network :\
NNOut(P, net)\
Parameters:　P - Input data set\
　　　　　　net - a neural network object

3. Save and load a neural network :\
saveNN(net, filename)\
loadNN(filename)\
Parameters:　net - a neural network object\
　　　　　　filename – full or relative path of a csv file to save the neural network

4. Evaluate Neural Network :\
  R(name, Y, y)\
  Parameters:　Y - Output data set\
  　　　　　　y - Neural network output

