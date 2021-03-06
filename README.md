# simultaneous cosparsity and low rank optimization: a demo for multi-structural compressed sensing
Classical compressive sensing only exploit the sparsity in one domain. A lot of biomedical signals have additional structures, such as multi-sparsity in different domains, piecewise smoothness, low rank matrix/ tensor, etc. We propose a framework to exploit all the available structure information. A new convex programming problem is generated with multiple convex structure-inducing constraints and the linear measurement fitting constraint. With additional a priori information for solving the underdetermined system, the signal recovery performance can be improved. In numerical experiments, we compare the proposed method with classical methods. Both simulated data and real-life biomedical data are used. Results show that the newly proposed method achieves better reconstruction accuracy performance in term of both L1 and L2 errors.

The codes for multi-channel EEG processing are provided in mc-eeg.zip, and the ones for single-channel EEG data are in sc-eeg.zip.

In others.zip, these functions might be needed in case you want to run the other methods compared in our paper too.

# reference:
1.	Yipeng Liu, Maarten De Vos, Sabine Van Huffel, “Compressed Sensing of Multi-Channel EEG Signals: The Simultaneous Cosparsity and Low Rank Optimization,” IEEE Transactions on Biomedical Engineering, vol. 62, no. 8, pp. 2055-2061, Aug. 2015.
2.	Yipeng Liu, Maarten De Vos, Ivan Gligorijevic, Vladimir Matic, Yuqian Li, Sabine Van Huffel, "Multi-Structural Signal Recovery for Biomedical Compressive Sensing,'' IEEE Transactions on Biomedical Engineering, vol. 60, no. 10, pp. . 2794 – 2805, Oct. 2013.

