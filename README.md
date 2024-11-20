ya![Banner](https://github.com/arcesoftware/Fibonacci-Fast-Fourier-Transform/blob/main/Images/mesmerizing_visualization_plot.jpg)

# Fibonacci Fast Fourier Transform Visualization

This repository contains a Python script that generates Fibonacci numbers, selects a random subset of them, computes the Fast Fourier Transform (FFT) on the data, and visualizes the results through scatter plots. The visualizations include both the original data and its frequency domain representation.

## Overview

The code follows these steps:
1. **Generate Fibonacci Numbers**: Create a sequence of Fibonacci numbers up to a specified count.
2. **Random Selection**: Randomly select a subset of Fibonacci numbers.
3. **Apply FFT**: Perform a Fast Fourier Transform (FFT) on the randomly selected Fibonacci numbers to analyze their frequency components.
4. **Visualize Data**: Generate two scatter plots:
   - **Original Data**: Visualizes the selected Fibonacci numbers.
   - **FFT Data**: Visualizes the FFT results, displaying the real and imaginary components of the frequency domain.

## Requirements

The script requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`

You can install the required dependencies using pip:
```bash
pip install numpy pandas matplotlib scipy
```
## How to Run the Script

1. **Clone this repository to your local machine:**

    ```bash
    git clone https://github.com/your-username/fibonacci-fft-visualization.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd fibonacci-fft-visualization
    ```

3. **Run the script:**

    ```bash
    python fibonacci_fft_visualization.py
    ```

This will:
- Generate a sequence of Fibonacci numbers.
- Randomly select a subset of these numbers.
- Perform FFT on the data.
- Display two scatter plots:
    - One showing the original Fibonacci data.
    - One showing the FFT results (real vs imaginary components).

## Code Explanation

### Fibonacci Sequence Generator
The `fibonacci(n)` function generates the first `n` Fibonacci numbers. It starts with `[0, 1]` and each subsequent number is the sum of the two previous ones.

### FFT Computation
The FFT is computed using the `scipy.fft.fft` function, which transforms the data from the time domain to the frequency domain.

### Visualization
Two scatter plots are created:
- **Input Data Plot**: Shows the randomly selected Fibonacci numbers with colors representing the values and marker sizes proportional to the FFT magnitudes.
- **FFT Plot**: Shows the real vs. imaginary components of the FFT, with colors indicating the phase of each frequency component.

## Example Output

- **Scatter Plot 1**: Shows the original Fibonacci numbers, with the x-axis representing the index and the y-axis representing the value.  
  ![Scatter Plot 1](https://github.com/arcesoftware/Fibonacci-Fast-Fourier-Transform/blob/main/Images/FFT_Fibo.png)

- **Scatter Plot 2**: Displays the real vs. imaginary parts of the FFT, with colors representing the phase.  
  ![Scatter Plot 2](https://github.com/arcesoftware/Fibonacci-Fast-Fourier-Transform/blob/main/Images/FFT_Fibo0.png)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to fork this repository, open issues, and submit pull requests if you'd like to contribute to this project.

## Acknowledgments
- The Fibonacci sequence is a well-known mathematical sequence.
- FFT is a widely used algorithm in signal processing and data analysis.

---

### ARCE SOFTWARE 2024










