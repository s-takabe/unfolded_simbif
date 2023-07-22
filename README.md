# Deep Unfolded Simulated Bifurcation for Massive MIMO Signal Detection

Reference: S. Takabe "Deep Unfolded Simulated Bifurcation for Massive MIMO Signal Detection," arXiv:2306.16264, 2023.

* SB_MIMO.ipynb
  Three SB-based detectors (without training) are implemented;
    ML-SB: SB minimizing naive squred loss function
    G-SB: MMSE-guided SB presented by previous study (W.Zhang and Y-L. Zheng, arXiv:2210.14660, 2022)
    LM-SB: SB minimizing modified squred loss function with LMMSE-like matrix 
  
* DU_LM_SB_MIMO.ipynb
  Deep-unfolded LM-SB for training some internal parameters is implemented.
  The condition differs from the paper for reducing its execution time.
  It takes about 5 mins. for training and evaluation on Colab. 
