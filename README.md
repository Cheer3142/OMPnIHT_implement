# OMPnIHT_implement

## High-Speed Compressed Sensing Reconstruction on FPGA using OMP and AMP
By Lin Bai, Patrick Maechler, Michael Muehlberghuber, and Hubert Kaeslin Integrated Systems Laboratory, ETH Zurich, Switzerland

"_This assignment only covers the fundamental idea and is a component of the course Sparse Signal Processing and its Applications._"

This project demonstrates that while both OMP and IHT algorithms effectively reconstruct sparse signals from compressed measurements, they exhibit distinct trade-offs: OMP provides superior reconstruction accuracy through its least-squares optimization but at higher computational cost, making it suitable for precision-critical applications like medical imaging, whereas IHT offers faster execution through iterative thresholding with moderate accuracy compromises, favoring real-time systems like radar processing. The FPGA implementations highlight how OMP's resource-intensive approach yields exact spike recovery while IHT achieves lower accuracy with 27% faster performance, emphasizing that algorithm choice should balance precision needs against latency constraints in compressive sensing deployments. These results validate CS's practical potential when paired with hardware-aware algorithm optimization. 


### Installation
```
git clone https://github.com/Cheer3142/OMPnIHT_implement.git
cd OMPnIHT_implement
```

### Key Features
✔ Sub-Nyquist Sampling - Reconstructs signals from M≪N measurements using sparsity <br />
✔ Dual Algorithm Implementation - FPGA-optimized OMP (precision) and IHT (speed) architectures <br />
✔ Hard Thresholding - IHT's K-sparse enforcement vs OMP's exact LS solutions <br />


