# arm-model
Arm model for biomechanical simulation - works with [OpenSim](https://opensim.stanford.edu/) 4.

DAS stands for Dynamic Arm Simulator: contains model of the shoulder girdle, elbow, wrist and hand. We use this .osim version of the model for moment arm and muscle length pre-processing, for editing model structure and for visualising the results of simulations carried out elsewhere.

This model can be used for visualising muscle lengths and moment arms in OpenSim where you have recorded kinematic data, but *cannot* be used for dynamic simulations inside OpenSim because the scapula model is not set up for that.

Please cite Chadwick, E. K., D. Blana, R. F. Kirsch, and A. J. van den Bogert (July 2014). Real-time simulation of three-dimensional shoulder girdle and arm dynamics. IEEE Transactions on Biomedical Engineering 61 (7), 1947– 1956. if you make use of this.
