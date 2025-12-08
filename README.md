# 💰 Finance Tracker App (Built with AWS)

This is a **simple finance tracking web app** built entirely on AWS using a **CI/CD pipeline with AWS Amplify**, **API Gateway**, **DynamoDB**, and **Lambda** by Akash bartwal E22CSEU0297
Aryan Raina E22CSEU0291


## 📊 Features
- Users can **add expenses** and **update budgets**
- Data is sent through **API Gateway** to **DynamoDB**
  - Expenses and Budgets are stored in separate tables
- A **Lambda function** (triggered via Lambda Function URL) pulls budget + expense data, analyzes it, and returns results to the frontend
- Results include:
  - Budget vs. Actual
  - Top 5 most bought items
  - Projected spending for the month
  - Alerts for overspending
- All changes to the app trigger **automatic deployments via AWS Amplify** from the GitHub repo.
## Demo Link
https://finance-tracker-using-aws.vercel.app/


## 🧰 AWS Services Used
- [x] AWS Amplify (CI/CD Deployment)
- [x] API Gateway (Routing & integration)
- [x] DynamoDB (NoSQL storage for expenses and budgets)
- [x] AWS Lambda (Data processing & analysis)
- [x] Lambda Function URL (Directly called from frontend)
- [x] CloudWatch (Optional monitoring/logging)

## 📂 Project Structure

├── frontend/ │ └── Amplify React App (deployed from GitHub) ├── lambda/ │ └── Data retrieval and processing function ├── api-gateway/ │ └── Routes to different DynamoDB tables ├── dynamodb/ │ └── Tables: expenses, budget



#AWS #Serverless #CloudApp #FinanceTracker #CI_CD #Lambda #DynamoDB #APIgateway #AWSAmplify #CloudProjects
