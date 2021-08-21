# Abstract 

Neural Networks can undoubtedly achieve great performance on a majority of tasks nowadays.
But along with that, there is a growing need for them to be able to explain their decisions. They
are famously called 'black boxes', which means it is extremely difficult to understand their outputs
and how they reached there. This paper aims to extend the works in [1] and explore different
interpretability techniques and understand their effectiveness, for the task of object detection. This
paper has used convolutional neural networks but these techniques can be tested for different tasks
and networks as well. This paper explored visualizing channel attributions, features, and activations
of neuron groups to understand more about what the network is learning. It was observed that
these techniques in combination with interactivity can make neural networks more explainable in
particular cases, not all. For a better understanding of this particular task, with Inception V1,
visualizing neurons with the highest activations and also neuron groups gives more information in
understanding what the neural network understands at each layer. For VGG-19, visualizing neuron
groups was the most effective.
[1] C. Olah, The building blocks of interpretability, Distill 3.3
