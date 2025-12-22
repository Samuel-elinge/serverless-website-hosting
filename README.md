<img width="1280" height="562" alt="439882548-cb49ad40-aad7-4901-8fc1-4ae8beae4642" src="https://github.com/user-attachments/assets/dfaf2f58-cd8c-40a8-895d-eb8e65802d9b" />
<strong>Introduction</strong><br>
In this step-by-step guide, you’ll learn how to build a robust serverless AI chatbot powered by Amazon Bedrock’s Titan Text G1 – Express model. The tutorial walks you through integrating the model with AWS Lambda, exposing it securely through Amazon API Gateway with CORS configured, and deploying a clean, user-friendly HTML/JavaScript frontend using Amazon S3 static website hosting.

<strong>Overview</strong><br>

👉 Users interact with the chatbot through a static frontend hosted on Amazon S3 or AWS Amplify Hosting, or by calling the API directly.

👉 User messages are sent as secure HTTPS requests to Amazon API Gateway, which routes them to an AWS Lambda function.

👉 The Lambda function processes the request and, using an IAM role, securely invokes Amazon Bedrock’s Titan Text G1 – Express model to generate a response.

👉 The generated response is returned through AWS Lambda and Amazon API Gateway back to the user.

🛠 Tech Stack

• Amazon Bedrock (Titan Text G1 – Express)
• AWS Lambda
• Amazon API Gateway
• Amazon S3 (Static Website Hosting)
• JavaScript, HTML, and CSS

If you want, I can also turn this into a simple architecture diagram description, README.md section, or slide-friendly version.
