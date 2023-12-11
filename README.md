# Force Plate Jump Analysis Dashboard

This interactive dashboard provides insights into force plate jump data, allowing users to explore various metrics based on player ID.

## Prerequisites

- Python (version 3.6 or higher)
- Pip (Python package installer)

## Getting Started

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. **Install Dependencies:**

    ```bash
    pip install dash dash-core-components dash-html-components pandas plotly dash-table
    ```

3. **Download the Data:**

    Make sure you have the CSV file (`JumpData.csv`) containing the force plate jump data in the project directory.

4. **Run the Dashboard:**

    Execute the following command to start the dashboard:

    ```bash
    python your_app_filename.py
    ```

5. **Access the Dashboard:**

    Open your web browser and go to [http://127.0.0.1:8065/](http://127.0.0.1:8065/) to access the interactive dashboard.

## Usage

- **Select Player ID:**
    - Use the dropdown menu to select the desired player ID.
    - The graphs will dynamically update based on the selected player.

- **Graphs:**
    - The dashboard includes various graphs showing velocity at peak power, mean powers, force at peak power, asymmetric forces, and impulse asymmetries.
    - Explore different tabs to view different aspects of the player's performance.


