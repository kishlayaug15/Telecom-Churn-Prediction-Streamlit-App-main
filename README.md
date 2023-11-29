
<div align='center'>
  

  <h1>Telecom Churn Prediction Streamlit App</h1>

  <p>
This is a Streamlit web application for predicting Telecom Churn. The app uses a trained machine learning model to predict whether a customer is likely to churn or not based on certain input features.
  </p>
  

<!-- Table of Contents -->

## :notebook_with_decorative_cover: Table of Contents

- [Dataset](#signal_strength-dataset)
- [Dependencies](#toolbox-dependecies)
- [Installation](#gear-installation)
- [Usage](#play_or_pause_button-usage)
- [Inputs](#construction-inputs)
- [Outputs](#rocket-outputs)
- [Deployment and Notebook](#triangular_flag_on_post-deployment-and-notebook)
- [License](#balance_scale-license)



## :signal_strength: Dataset

The trained dataset is originally from the IBM Sample Datasets. The objective is to predict behavior to retain customers by analyzing all relevant customer data and developing focused customer retention programs. The dataset can be found on [`Kaggle`](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It includes following information:

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

### Details
- Number of Rows: 7043 (Customers)
- Number of Columns: 21 (Features)
- Missing Attribute Values: Yes
- Class Distribution: (churn value Yes is interpreted as "customer churn")



## :toolbox: Dependecies
For Dependencies, see requirements.txt

## :gear: Installation

Clone the repository and install the required dependencies using the following commands:

```bash
git clone https://github.com/kishlayaug15/Telecom-Churn-Prediction-Streamlit-App-main.git
```

```bash
cd Telecom-Churn-Prediction-Streamlit-App
```

```bash
pip install -r requirements.txt
```

```bash
streamlit run app.py
or
python -m streamlit run app.py
```

## :play_or_pause_button: Usage

Open the app in your web browser. <br>
Enter the required information in the input fields.<br>
Click the 'Predict' button to generate the prediction.<br>



## :construction: Inputs
Click on the link and reboot the tool or run locally and enter following details:

* Tenure (months)
* Phone Service: 0 or 1
* Contract: 0 - Month-to-month, 1 - One year, 2 - Two year
* Paperless Billing: 0 or 1
* Payment Method: 0 - Bank transfer (automatic), 1 - Credit card (automatic), 2 - Electronic check, 3 - Mailed check
* Monthly Charges


## :rocket: Outputs
The app will display following messages:

* "The customer is likely to churn." or "The customer is unlikely to churn."
* "The probability of churn is: (X, Y)".



## :triangular_flag_on_post: Deployment and Notebook

This tool has been deployed using [`Streamlit`](https://streamlit.io/). Learn about streamlit deployment [`here`](https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app). Checkout the notebook repository [`here`](https://github.com/kishlayaug15/Telecom-Churn-Prediction-Streamlit-App-main) from where the pickle file has been imployed in the tool.



## :balance_scale: License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/kishlayaug15/Telecom-Churn-Prediction-Streamlit-App-main/blob/main/LICENSE) file for details.


Project Link: [https://github.com/kishlayaug15/Telecom-Churn-Prediction-Streamlit-App-main.git](https://github.com/kishlayaug15/Telecom-Churn-Prediction-Streamlit-App-main.git)
<hr />
<br />
<div align="center">Don't forget to leave a star ⭐️</div>
