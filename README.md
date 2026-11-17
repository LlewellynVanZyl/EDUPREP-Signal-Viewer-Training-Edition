# EDUPREP Signal Viewer – Training Edition

Welcome to the **EDUPREP Signal Viewer – Introductory Training Package**.

The EDUPREP Signal Viewer is an electronic signal analysis tool designed to assist with the examination, measurement and interpretation of electronic circuit simulation data.

### Download the Application

Download the latest version of the EDUPREP Signal Viewer from the Releases section.

### Package Contents

This introductory package includes:

- **EDUPREP Signal Viewer** application.
- **Sample Simulation Data** for analysis.
- **Candidate Assessment Brief** containing the training and assessment instructions.

### Training Exercise

The demonstration exercise introduces candidates to:

- Waveform analysis and interpretation.
- DC voltage measurements.
- AC voltage measurements.
- Frequency determination.
- Voltage gain calculations.

### Getting Started

1. Download and extract the repository.
2. Open the `Software` folder.
3. Run `EDUPREP_Signal_Viewer.exe`.
4. Load the supplied reference simulation data from the `Sample_Data` folder.
5. Follow the instructions in the Candidate Assessment Brief.
6. Use the schematic diagram provided in the assessment brief as a reference.

### Using the Function Window

The **Function Window** located at the top of the EDUPREP Signal Viewer allows you to perform measurements and mathematical evaluations on your loaded signals.

#### How to Use
1. Type your function expression into the Function window.
2. Click the **Add** button.
3. Click the **Plot Selected** button to display the results in the **Function Results window**.

#### Supported Functions & Examples

* **`ave()`** — Computes the average value (useful for finding the **DC offset**).
  * *Example:* `ave(V(in))` calculates the DC value of the node named `in`.
* **`min()`** — Identifies the minimum value of a signal.
  * *Example:* `min(V(in))` finds the lowest voltage value at node `in`.
* **`max()`** — Identifies the maximum value of a signal.
  * *Example:* `max(V(in))` finds the peak voltage value at node `in`.

### Welcome to EDUPREP!

*Developing practical skills through applied technical assessment.*
