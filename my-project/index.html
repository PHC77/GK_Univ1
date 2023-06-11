import streamlit as st
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from scipy.signal import TransferFunction, lsim

def main():
    st.title("Streamlit App: System Response")

    # Transfer function coefficients
    num = [100]
    den = [1, 5, 6]

    # Define transfer function G(s)
    G = TransferFunction(num, den)

    # Time array
    t = np.linspace(0, 10, 500)

    # Create sinusoidal input
    u = np.sin(t)

    # Compute system response
    t, y, _ = lsim(G, u, t)

    # plotting
    fig, ax = plt.subplots(figsize=(10, 6))

    # Input signal plot
    ax.plot(t, u, label='Input (sinusoidal)', color='blue')

    # Output signal plot
    ax.plot(t, y, label='Output', color='red')

    ax.set_title('Input & Output Over Time')
    ax.set_xlabel('Time')
    ax.set_ylabel('Amplitude')
    ax.grid()
    ax.legend()

    # Display the plot using Streamlit
    st.pyplot(fig)

    # Define the system
    s1 = TransferFunction([100], [1, 5, 6])  # G(s) = 100/(s+2)(s+3)

    # Define the frequency range
    frequencies = np.logspace(-2, 2, 500)  # frequencies

    # Calculate frequency response
    w, mag, phase = s1.bode(frequencies)

    # Create Bode magnitude plot
    fig, (ax1, ax2) = plt.subplots(2, 1, figsize=(10, 6))
    ax1.semilogx(w, mag)  # Bode magnitude plot
    ax1.set_title('Bode plot of G(s) = 100/(s+2)(s+3)')
    ax1.set_ylabel('Magnitude [dB]')

    # Create Bode phase plot
    ax2.semilogx(w, phase)  # Bode phase plot
    ax2.set_ylabel('Phase [degrees]')
    ax2.set_xlabel('Frequency [Hz]')

    # Display the plot using Streamlit
    st.pyplot(fig)

if __name__ == '__main__':
    main()
