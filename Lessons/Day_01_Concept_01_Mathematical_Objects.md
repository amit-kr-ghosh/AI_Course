# Day 1 — Linear Algebra for Machine Learning
## Concept 1.1 — Mathematical Objects in AI/ML
**Date:** 2026-11-01  
**Status:** Introduced

### Why linear algebra matters
AI systems convert information into numerical representations and perform mathematical transformations on those representations. Linear algebra provides the language for organizing and transforming these values.

### Four fundamental objects
1. **Scalar:** A single numerical value; examples include a learning rate, loss value, individual weight or bias.
2. **Vector:** An ordered collection of components. A house represented by area, bedroom count and age can be encoded as [1200, 3, 8].
3. **Matrix:** A rectangular two-dimensional arrangement. A dataset is often represented with observations as rows and features as columns.
4. **Tensor:** A generalized multidimensional numerical structure. In common AI engineering language, tensors include image arrays, batches and sequence representations. Mathematically, scalars, vectors and matrices are tensors of orders 0, 1 and 2.

### Shape, dimensions and axes
For A = [[10, 20, 30], [40, 50, 60]]:
- Shape = (2, 3): two rows and three columns.
- Number of dimensions / axes = 2.
- Axis 0 indexes rows; axis 1 indexes columns.
- Total elements = 2 × 3 = 6.

A colour image can have shape (224, 224, 3), representing height, width and RGB channels. A batch of 32 such images can have shape (32, 224, 224, 3).

### Important terminology distinction
Array rank / ndim is the number of axes. Mathematical matrix rank is the number of linearly independent rows or columns. These are different meanings and must not be conflated.

### AI/ML connection
A dense neural layer is commonly expressed as Y = XW + b. Inputs, weights and outputs are organized as arrays/tensors, and matrix operations transform learned representations.

### Status and next checkpoint
This was a conceptual explanation only. No code was run, no practical was completed and no learner mastery was assessed.
**Next:** Vector components, coordinate interpretation, addition, subtraction, scalar multiplication and linear combinations.

### Reference
NumPy documentation: https://numpy.org/doc/stable/user/absolute_beginners.html
