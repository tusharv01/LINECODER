# Line Coding Encoder and Decoder

## Overview

This project implements a Line Coding Encoder and Scrambler with a digital data generator. The assignment involves generating a random data sequence, encoding it using various line coding schemes (NRZ-L, NRZ-I, Manchester, Differential Manchester, AMI), and optionally scrambling it using B8ZS or HDB3. The code also identifies the longest palindromic sequence in the generated data.

## Line Encoder And Decoder GUI

This Line Encoder GUI is implemented using PySimpleGUI, Matplotlib, and NumPy. It provides a user-friendly interface for encoding and decoding various line encoding schemes.

### Features:

- Initialize random input data.
- Enter custom input data.
- Encode and decode data using various line encoding schemes.
- Display the encoded and decoded data.
- Plot graphs for input, encoded, and decoded data.

### Line Encoding Schemes:

1. Polar NRZ-L
2. Polar NRZ-I
3. Manchester
4. Polar RZ
5. AMI
6. Scrambling AMI B8ZS (Bipolar with 8 zero substitution)
7. Differential Manchester
8. Scrambling AMI HBD3 (High-Density Bipolar 3 Zeros)
9. PCM (Pulse Code Modulation)
10. Delta Modulation

### How to Use:

1. Launch the GUI.
2. Initialize random input or enter custom input.
3. Encode the data using a selected encoding scheme.
4. Optionally, decode the encoded data.
5. Visualize the input, encoded, and decoded data using the "Show Graph" button.

### Examples:

#### Initializing the Input:![Screenshot from 2023-11-15 14-09-40](https://github.com/tusharv01/LINECODER/assets/93588934/28b3f0b3-fb34-4fed-ab25-6f63a6f633fb)


#### Entering Custom Input:![Screenshot from 2023-11-15 14-09-51](https://github.com/tusharv01/LINECODER/assets/93588934/e771462e-bf0d-446f-acbb-d2a1d9d0c340)


#### Encoding and Decoding:![Screenshot from 2023-11-15 14-12-23](https://github.com/tusharv01/LINECODER/assets/93588934/ad59e8dc-3fb3-4951-969c-3ab921c6fe20)



## How to Run the Code

1. Ensure you have Python installed on your machine.
2. Clone the repository:

    ```bash
    git clone https://github.com/tusharv01/LINECODER.git
    ```

3. Navigate to the project directory:

    ```bash
    cd LINECODER
    ```

4. Run the main program:

    ```bash
    python LineEncoder.py
    ```

    or using the LineEncoder.ipynb file:

    ```bash
    jupyter notebook
    ```

    Navigate to the .ipynb file and run the cells.

5. Follow the on-screen prompts to input preferences for data generation, encoding, and scrambling.

## Assumptions
- All schemes are implemented using positive logic.
- Manchester encoding uses IEEE (802.3) convention.
- The format used is Manchester, and differential Manchester is G.E Thomas format
- It is assumed that the user will give binary data to the encoder.
  
## Connect with Me

- **LinkedIn:** [Tushar Verma](https://www.linkedin.com/in/tusharverma01/)
- **GitHub:** [tusharv01](https://github.com/tusharv01)

## Copyright

© 2023 Tushar Verma. All rights reserved.
