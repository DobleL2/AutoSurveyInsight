# AutoSurveyInsight

AutoSurveyInsight is a powerful tool designed to automate the analysis of survey data. With just an Excel file as input, AutoSurveyInsight generates comprehensive reports in PDF, PowerPoint, and Excel formats, saving you hours of manual work.

## Features

- **Automated Data Analysis**: Process survey data and generate insights without manual intervention.
- **Multiple Report Formats**: Generate reports in PDF, PowerPoint, and Excel formats.
- **Customizable Output**: Tailor the reports to meet your specific needs, including custom statistics and visualizations.
- **User-Friendly Interface**: Simple input process—just upload your Excel file and let AutoSurveyInsight do the rest.
- **Scalable**: Efficiently handles large datasets, making it suitable for small and large surveys alike.

## Installation

To get started with AutoSurveyInsight, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/AutoSurveyInsight.git
    ```
2. Navigate to the project directory:
    ```bash
    cd AutoSurveyInsight
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    python main.py
    ```

## Usage

1. Place your survey data Excel file in the `/data` folder.
2. Run the application using the command:
    ```bash
    python main.py
    ```
3. The output reports will be generated in the `/output` folder.

## Configuration

You can customize the output formats and report settings by modifying the `config.json` file in the root directory.

## Example

Here is a sample structure of the input Excel file:

| Category 1| Question 1 | Question 2 |
|---------- |----------|----------|
| Category Option | Answer 1 | Answer 1 |
| Category Option | Answer 2 | Answer 2 |
| ...      | ...      | ...      |

The generated report will include visualizations, summary statistics, and key insights based on the responses.

## Contributing

We welcome contributions to enhance AutoSurveyInsight! Please fork the repository and create a pull request with your improvements.

## License

See the `LICENSE` file for details.

## Contact

For any questions or suggestions, feel free to open an issue or reach out via [lelapo@outlook.es](mailto:lelapo@outlook.es).

---

**AutoSurveyInsight** – Simplifying survey analysis, one report at a time.
