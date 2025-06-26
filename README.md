# 🤖 Ethical AI for Insurance Pricing 

## 📌 Overview
This project explores the ethical use of Artificial Intelligence (AI) in insurance pricing, simulating how an insurer might develop and deploy a machine learning model to estimate medical insurance costs. We then perform a mock audit of the model to evaluate fairness, transparency, and accountability, using tools like SHAP and LIME within Orange. The project draws on real-world policy frameworks such as New York City’s AEDT Law and Colorado’s AI Insurance Pricing Regulation, aligning with broader AI ethics principles including fairness, explainability, and non-discrimination.

## 📂 Files in This Repository
📄 AI_Ethics_Insurance_Audit.pdf – The main paper detailing our modeling and audit workflow, ethical concerns, and policy context.

🧠 IPM_best_model.pkl – The best-performing insurance pricing model trained using XGBoost and saved for auditing.

🔧 Orange_Workflows/ – Screenshots and files of Orange workflows for both model development and auditing phases.

📜 README.md – Documentation and summary of the project. 

🛠️ Key Topics Covered
🏗️ AI in Insurance Pricing
Building models using XGBoost, Random Forest, and Deep Neural Networks.

Saving and deploying models with .pkl files for reuse and audit.

Real-world simulation of an insurer’s modeling pipeline.

⚖️ Fairness, Bias & Transparency
Fairness Auditing: Evaluating whether the model treats individuals equitably across attributes like gender, age, and health history.

SHAP & LIME: Interpretable ML techniques to explain global and individual predictions.

Dataset Bias Checks: Using visual tools in Orange for class imbalance and outlier detection.

Fairness Widgets: Assessing disparate impact and equal opportunity across subgroups.

📋 AI Ethics & Regulatory Alignment
Reflects AI ethics principles: transparency, fairness, accountability, and interpretability.

Considers regulations like:

New York AEDT Law – Emphasizing explainability and anti-discrimination in automated decision tools.

Colorado AI Insurance Pricing Regulation – Governing the use of AI in pricing models to ensure compliance and equity.

##💡 Why This Matters
As AI becomes more embedded in financial services, it’s essential to evaluate models not just for accuracy, but for fairness and transparency. Our project shows how low-code tools like Orange can empower both developers and auditors to understand and govern AI responsibly. By simulating both model creation and ethical auditing, we contribute to the conversation on how AI can be deployed ethically and transparently in industries like insurance.

