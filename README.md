# Project Febex Forex Digital Amplitude Chart Indicator

## Overview

This project explores the dynamics of the XAUUSD Forex pair during specific trading sessions by analyzing binary representations of daily session outcomes (Buy/Sell). It applies various computational and mathematical concepts to uncover patterns, relationships, and temporal dynamics. A key component is a Python tool that calculates and visualizes a "Digital Amplitude" based on these binary patterns, offering a unique perspective analogous to market phases like Accumulation, Manipulation, and Distribution (AMD).

This research is based on historical data collected by the Emmanuelkhisa and is intended for study and analysis purposes. It is not financial advice, and any application of these concepts in live trading should be done with extreme caution and thorough independent validation on diverse datasets.

## Repository Structure

* `README.md`: Project overview and instructions (this file).
* `Content/`: Contains the detailed research work.
    * `ResearchWork.md`: The comprehensive report detailing the methodology, analysis, insights, and conclusions.
* `Tools/`: Contains the Python tool and dependencies.
    * `febex_analyzer.py`: The Python script to input data, calculate amplitude, and generate the chart.
    * `requirements.txt`: Lists the necessary Python libraries.


## Getting Started

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Emmanuelkhisa/Febex-Forex-Digital-Amplitude
    cd Febex-Forex-Digital-Amplitude
    ```
2.  **Install Dependencies:** Ensure you have Python installed. Then, install the required libraries:
    ```bash
    pip install -r Tools/requirements.txt
    ```
3.  **Run the Tool:** Navigate to the `Tools/` directory and run the Python script:
    ```bash
    cd Tools
    python febex_analyzer.py
    ```
4.  **Input Data:** Use option `1` in the program to input your collected binary data for new trading days. The data will be stored in `forex_session_data.csv`.
5.  **View Chart:** Use option `2` to select a set of sessions and visualize the Febex Digital Amplitude chart.

## A TIP FOR YOU
->This Project uses Forex data with a binary number data sets.

->Switch your Chart to a higher time frame . 4H to be specific.

->Record each Candle stick; "'1' for Buy/Long bias, & '0' for Sell/Short bias (or a Doji)."

->In a day, you will end up with sets of Data e.g (101) Representing Long, Short, Long runs for E.g London, Lond-Newy overlap, NewYork sessions respectively.

->A csv file is generated automatically using the python file, which will hold your Datasets for graph creation.

->For accuracy, Update the csv file with more forex session data sets as guided when you run the Python file.

## Research Work

The detailed methodology, analysis, and insights are documented in the `Content/ResearchWork.md` file. This report explains the binary data encoding, the application of various computational concepts (probabilities, correlation, entropy, etc.), the derivation of the Digital Amplitude, and the interpretation of the chart in relation to potential market phases.

## Contributing / Further Research

Ideas for expanding this project or conducting further research include:

* Gathering more extensive historical data.
* Applying the analysis to different Forex pairs.
* Exploring alternative amplitude calculation rules or indicators derived from binary data.
* Implementing more advanced statistical tests or machine learning models for prediction based on the analyzed patterns.

Feel free to fork the repository and build upon this research.

## License

[MIT License]
