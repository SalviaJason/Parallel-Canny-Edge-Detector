# Parallel-Canny-Edge-Detector

## Install
    pip install -r requirements
## Usage
    # serial version by numpy
    python canny_edge_serial.py
    # parallel version by cupy package
    python canny_edge_cupy.py
## Further Information
* cupy version needs to warm up, because of compilation of cuda kernel function.
