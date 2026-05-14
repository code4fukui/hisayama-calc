# hisayama-calc

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web-based calculator for estimating the 10-year risk of cardiovascular disease based on the Hisayama Study score.

## Demo

[https://code4fukui.github.io/hisayama-calc/](https://code4fukui.github.io/hisayama-calc/)

## Screenshot

The user interface consists of a simple form to input health metrics. The results section below the form automatically displays a total risk score and the corresponding risk percentages for different age groups.


![Screenshot of hisayama-calc interface showing input fields for gender, blood pressure, etc., and color-coded risk results below.](https://user-images.githubusercontent.com/5935342/220490729-39908480-77a8-4222-9572-8703055728a5.png)


## Features

- **Risk Factor Inputs**: Calculates risk based on six key health metrics:
  - Gender (Male/Female)
  - Systolic Blood Pressure (mmHg)
  - Glucose Metabolism Abnormality (Present/None)
  - Serum LDL-C (mg/dL)
  - Serum HDL-C (mg/dL)
  - Smoking Status (Smoker/Non-smoker)
- **Point-Based Scoring**: Converts inputs into a cumulative point score, which is then used to determine risk percentages from a lookup table.
- **Age-Specific Results**: Displays the 10-year cardiovascular disease risk as a percentage for four distinct age ranges: 40-49, 50-59, 60-69, and 70-79.
- **Color-Coded Risk Levels**: Automatically highlights the results to indicate risk severity:
  - **Low Risk**: Light blue background
  - **Medium Risk**: Light yellow background
  - **High Risk**: Light red background

## Usage

1.  Open the [demo application](https://code4fukui.github.io/hisayama-calc/) in your web browser.
2.  Fill in the form with the required health data using the radio buttons and number fields.
3.  The risk score and percentages will update automatically as you enter the data.

## Attribution

This project is created and maintained by [Code for FUKUI](http://code4fukui.github.io/).

## License

MIT License - see [LICENSE](LICENSE).