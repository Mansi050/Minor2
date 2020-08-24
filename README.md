# Minor2
Our problem statement is reducing the noise in the speech. There are many existing techniques for this like wiener filtering, spectral subtraction method or minimizing the mean square error between the input and output, etc. to name the few but there are limitations in these techniques. They are hard to implement in circuits and also, these techniques do not consider the sound as a mode of communication, but just a signal. So, let us introduce a neural net in this equation to make a machine learn the difference between speech and noise. In recent years a non-linear model DNN (Deep Neural Net) is used as it has good generalization ability for different inputs. In this a large training dataset of speech and noise is converted to Spectrograph as it can provide a better insight into sound data. Now this spectrograph will be fed to DNN to learn. Ideally the resultant network should be generalised. This ideal situation will require a feed forward neural net as large as a human brain to generalize for all situations, so this project will go through many different approaches which tackle these situations by making that basic DNN a more intelligent and complex.
Our new Neural Net must optimize the following constraints:
1. Accuracy should be better than already existing models.
2. Time to test must be minimized.
3. Model must be smaller in size to reduce the time of loading it in memory.
