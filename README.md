# Telecom Churn Prediction

This repository contains code and a report detailing the project for predicting customer churn in the telecom industry using machine learning techniques.

## Overview
Customer churn poses a significant challenge for telecom companies. Predicting which customers are likely to churn can enable companies to take proactive measures to retain them. 
This project utilizes machine learning algorithms to analyze historical data and forecast churn for telecom customers.

## Data Source
The dataset is taken from Kaggle, an open-sourced public datasets platform. </br>
www.kaggle.com/datasets/blastchar/telco-customer-churn

## Data Description
The dataset comprises 7043 records. There are 21 attributes in total and 1 target attribute “Churn”, which indicates where the customer is likely to stay or leave. Following are the attributes: -

<table>
  <tr>
    <th>Column</th>
    <th>Attribute</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Customer ID</td>
    <td>To identify each customer</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Gender</td>
    <td>Gender of the customer (male/female)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Senior Citizen</td>
    <td>If the customer is a senior citizen or not (1/0)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Partner</td>
    <td>If the customer has a partner or not (Yes/No)</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Dependents</td>
    <td>If the customer has dependents or not (Yes/No)</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Tenure</td>
    <td>Number of months the customer has stayed with the company</td>
  </tr>
  <tr>
    <td>7</td>
    <td>PhoneService</td>
    <td>If the customer has a phone service or not (Yes/No)</td>
  </tr>
  <tr>
    <td>8</td>
    <td>MultipleLines</td>
    <td>If the customer has multiple lines or not (Yes/No/No phone service)</td>
  </tr>
  <tr>
    <td>9</td>
    <td>InternetService</td>
    <td>Customer’s internet service provider (DSL/Fiber optic/No)</td>
  </tr>
  <tr>
    <td>10</td>
    <td>OnlineSecurity</td>
    <td>If the customer has online security or not (Yes/ No/No internet service)</td>
  </tr>
  <tr>
    <td>11</td>
    <td>OnlineBackup</td>
    <td>If the customer has online backup or not (Yes/ No/No internet service)</td>
  </tr>
  <tr>
    <td>12</td>
    <td>DeviceProtection</td>
    <td>If the customer has device protection or not (Yes/ No/No internet service)</td>
  </tr>
  <tr>
    <td>13</td>
    <td>TechSupport</td>
    <td>If the customer has Tech support or not (Yes/ No/No internet service)</td>
  </tr>
  <tr>
    <td>14</td>
    <td>StreamingTV</td>
    <td>Availability of streaming TV (Yes/ No/No internet service)</td>
  </tr>
  <tr>
    <td>15</td>
    <td>StreamingMovies</td>
    <td>Availability of streaming movies (Yes/ No/No internet service)</td>
  </tr>
  <tr>
    <td>16</td>
    <td>Contract</td>
    <td>Type of contract (month-to-month/ one year/ Two year)</td>
  </tr>
  <tr>
    <td>17</td>
    <td>PaperlessBilling</td>
    <td>If they have signed up for paperless billing option (yes/no)</td>
  </tr>
  <tr>
    <td>18</td>
    <td>PaymentMethod</td>
    <td>Mode of payment by the customer (electronic, bank transfer, mailed check, credit card)</td>
  </tr>
  <tr>
    <td>19</td>
    <td>MonthlyCharges</td>
    <td>Monthly bill rate</td>
  </tr>
  <tr>
    <td>20</td>
    <td>TotalCharges</td>
    <td>Total charges of the plan</td>
  </tr>
</table>



## Models
We experiment with several machine learning models, including:
<ul>
  <li>Logistic Regression</li>
  <li>Decision Trees</li>
  <li>Random Forest</li>
  <li>Gradient Boosting</li>
  <li>Neural Networks</li>
</ul></br>
These models are implemented using libraries such as scikit-learn
