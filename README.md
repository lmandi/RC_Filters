# Passive RC Filters Study

## Project Overview

This project implements two passive RC filters and studies their behavior. Both the high-pass and low-pass filters use an **18 kOhm resistor** and a **10 nF capacitor**. The project demonstrates how each filter responds to two input sine wave signals with different frequencies (100 Hz and 1 kHz) and visualizes the results through MATLAB plots.

### Components

- **High-Pass Filter**: Allows signals with a frequency higher than the cutoff frequency to pass while attenuating lower frequencies.
- **Low-Pass Filter**: Allows signals with a frequency lower than the cutoff frequency to pass while attenuating higher frequencies.

### Signal Specifications

- **Input Frequencies**: 100 Hz and 1 kHz (but can be modified accordingly)
- **Signal Amplitude**: 5 Vpp (2.5 V amplitude)
- **Sampling Frequency**: 50 kHz

## Usage

1. **Requirements**: Ensure you have MATLAB installed with the Control System Toolbox.
2. **Open Live Script**: Open the `passive_filters.mlx` file in MATLAB.
3. **Run the Script**: Execute the script to generate the input signals, apply the filters, and visualize the results.

## License

This project is licensed under the MIT License.

## Results

### High-Pass Filter Output
![High-Pass Filter Output](images/high_pass_filter_output.png)

### Low-Pass Filter Output
![Low-Pass Filter Output](images/low_pass_filter_output.png)
