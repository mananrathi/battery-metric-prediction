# Battery Metric Prediction
This repository contains code and data for predicting key battery metrics, including Remaining Useful Life (RUL), State of Health (SOH), and State of Charge (SOC) for electric vertical take-off and landing (eVTOL) aircraft.

## Data-Set
- The dataset produced consists of a battery duty profile tailored for an electric vertical take-off and landing aircraft, employing a cell typical for such applications.
- The dataset encompasses 22 cells, comprising a total of 21,392 charge and discharge cycles.
- We used the data provided to model of key battery metrics such as Remaining Useful Life, State of Health, and State of Charge.

## Files

- `allFiles_wCycleNum.py`: Script for processing all files with cycle numbers.
- `allFiles_woCycleNum.py`: Script for processing all files without cycle numbers.
- `individualFile_wCycleNum_20.py`: Script for processing individual files with cycle numbers for 20 cycles.
- `individualFile_wCycleNum_50.py`: Script for processing individual files with cycle numbers for 50 cycles.
- `individualFile_woCycleNum_20.py`: Script for processing individual files without cycle numbers for 20 cycles.
- `individualFile_woCycleNum_50.py`: Script for processing individual files without cycle numbers for 50 cycles.

## Usage

1. **Clone Repository:**
    ```bash
    git clone https://github.com/mananrathi/battery-metric-prediction.git
    cd battery-metric-prediction
    ```

2. **Un-Zip Data-Set:**
    unzip the `Carnegie Melon Dataset.zip` file into the repository directory.

3. **Install Required Libraries:**
    create a virtual environment and install the dependencies listed in `requirements.txt`:
    ```bash
    python -m venv venv
    source venv/bin/activate  # on windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

4. **Run Scripts:**
    depending on your analysis needs, run the appropriate script. for example, to process all files with cycle numbers:
    ```bash
    python allFiles_wCycleNum.py
    ```

## Acknowledgments

- The dataset and initial project is carried out by Carnegie Melon University.

For any questions or contributions, feel free to open an issue or submit a pull request.
