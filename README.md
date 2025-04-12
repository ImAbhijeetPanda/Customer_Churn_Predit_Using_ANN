# Customer Churn Prediction Using ANN

This project uses Artificial Neural Networks (ANN) to predict customer churn. The model analyzes customer data such as age, balance, credit score, tenure, and other features to determine whether a customer is likely to leave the company.

## 🧑‍💻 Live Demo

🔗 [Click here to use the Streamlit App](https://customerchurnpredit.streamlit.app/)

## 📁 Repository Contents

- `app.py` – Streamlit app to interactively predict customer churn.
- `experiments.ipynb` – Notebook with data preprocessing, model training, and evaluation.
- `model.h5` – Trained Keras ANN model.
- `label_encoder_gender.pkl` – Encoder for gender.
- `onehot_encoder_geo.pkl` – Encoder for geography.
- `scaler.pkl` – Scaler used to normalize features.

## 🚀 Features

- Clean and interactive UI with real-time churn prediction.
- Visual cues for churn likelihood (green/red highlights).
- Encoders and scaler preloaded for consistent input processing.
- Deployed using Streamlit Cloud for instant access.

## 🧠 Model Details

- Architecture: Fully connected ANN with dense layers.
- Framework: TensorFlow / Keras.
- Trained on structured customer data with features like:
  - Geography
  - Gender
  - Age
  - Balance
  - Credit Score
  - Tenure
  - Number of Products
  - Has Credit Card
  - Is Active Member
  - Estimated Salary
 
  ## 📊 Experiment Insights

The `experiments.ipynb` notebook covers:

- Data cleaning & preprocessing  
- Label encoding & feature scaling  
- ANN architecture and training loop  
- Model evaluation (accuracy, loss)  
- Pickling encoders & model export for deployment


## 📦 Installation & Usage

### Clone the repository
```bash
git clone https://github.com/ImAbhijeetPanda/Customer_Churn_Predit_Using_ANN.git
cd Customer_Churn_Predit_Using_ANN
````


## 📄 License

This project is licensed under the MIT License.

---

Credits
This project is authored and maintained by **[Abhijeet Panda](https://github.com/ImAbhijeetPanda)**.

## Contact

For any questions or feedback, feel free to reach out:

- **Email**: [iamabhijeetpanda@gmail.com](mailto:iamabhijeetpanda@gmail.com)
- **LinkedIn**: [Abhijeet Panda](https://www.linkedin.com/in/imabhijeetpanda)
- **GitHub**: [ImAbhijeetPanda](https://github.com/ImAbhijeetPanda)

##🌟 Star this repo if you found it helpful!
Let me know if you want to add badges, a preview screenshot, or anything else.

