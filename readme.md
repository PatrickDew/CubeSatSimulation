# CubeSat Simulation Project - Quaternion Alignment Functions

This repository contains MATLAB functions for calculating quaternion alignment between different reference and alignment vectors. The provided functions are intended for use in the CubeSat Simulation Project, particularly in simulations involving the Aerospace Blockset. The code replaces a sun-tracking block with a MATLAB function implementation, compatible with MATLAB R2024a.

# CubeSat Simulation Project - Quaternion Alignment Functions

This repository includes MATLAB functions for quaternion alignment calculations used in the CubeSat Simulation Project. These functions are designed to replace a sun-tracking block with a MATLAB function implementation, suitable for MATLAB R2024a.

## Functions Overview

### `mainQuaternionSystem`

**Purpose:** Computes the alignment quaternion between different reference and alignment vectors.

### `quaternionBetweenVectors`

**Purpose:** Calculates the quaternion representing the rotation from one vector to another.

### `orthogonalVector`

**Purpose:** Finds an orthogonal vector to the given vector.

### `checkParallel`

**Purpose:** Determines if two vectors are parallel, anti-parallel, or not parallel.

### `quatnorm`

**Purpose:** Normalizes a quaternion.

### `vectorProjection`

**Purpose:** Performs a cross product operation with two input vectors.

### `quaternionRotation`

**Purpose:** Rotates a vector by a given quaternion.

### `compare_logic`

**Purpose:** Compares the status of vector alignment between two pairs of vectors.

## Getting Started

**Clone the Repository:**
   ```bash
   git clone https://github.com/PatrickDew/CubeSatSimulation.git
   ```
## Notes
- Functions are designed for MATLAB R2024a.
- Ensure the Aerospace Blockset is installed and configured for these functions.