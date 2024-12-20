# Inpainting Project

## Overview
This project is a comprehensive study and from-scratch implementation of the exemplar-based inpainting algorithm as described in the research paper:

> A. Criminisi, P. Perez, and K. Toyama, "Object removal by exemplar-based inpainting," IEEE CVPR, 2003.

The algorithm is designed to seamlessly remove unwanted objects from images by sampling patterns from surrounding regions. It combines techniques of texture synthesis and inpainting to achieve both structural coherence and textural realism.

## Features
- **Implementation of the Criminisi et al. Algorithm**: The project includes a detailed, from-scratch implementation of the exemplar-based inpainting algorithm.
- **Pattern Sampling and Texture Synthesis**: The algorithm leverages patterns from surrounding regions for accurate inpainting.
- **Structural and Textural Realism**: Ensures the output image maintains coherent structures and realistic textures.
- **Proposed Improvements**: Modifications were introduced to address identified limitations, enhancing the algorithm's accuracy and efficiency.
- **Rigorous Testing**: The method was rigorously tested to evaluate its performance and validate improvements.

## Limitations Identified
- Difficulty in handling highly structured textures.
- Challenges with complex edge propagation.
- Absence of a learning approach.

## Improvements
Targeted enhancements were proposed and implemented to overcome the above limitations. These improvements were validated through testing.

## Testing
The project includes a suite of tests to:
- Evaluate the algorithm's performance on various datasets.
- Validate the effectiveness of the proposed improvements.

## References
- A. Criminisi, P. Perez, and K. Toyama, "Object removal by exemplar-based inpainting," IEEE CVPR, 2003. ([Link to Paper](https://doi.org/10.1109/CVPR.2003.1211538))

## Acknowledgments
This project was inspired by the seminal work of Criminisi et al., whose research laid the foundation for exemplar-based inpainting methods.
