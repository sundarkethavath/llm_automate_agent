# llm_automate_agent
 LLM-based Automation Agent
An intelligent automation agent that leverages Large Language Models (LLMs) to automate various tasks efficiently. It supports secure file handling, multi-tasking, and API-based execution for a seamless automation experience.

## Key Features
✅ Task Parsing: Utilizes GPT-4o-Mini for accurate task understanding.
✅ Secure File Operations: Ensures safe processing of sensitive data.
✅ Multi-Task Support: Handles multiple operations simultaneously.
✅ API-Based Execution: Integrates with APIs for enhanced functionality.

## System Requirements
Ensure you have the following installed before proceeding:

1. Docker – Required for containerization.
2. AI Proxy Token – Needed for LLM functionality.
3. Getting Started
Follow these steps to install and run the LLM-based Automation Agent on your system.

### 1. Clone the Repository
- bash
- Copy
- Edit
```sh
git clone https://github.com/sundarkethavath/llm_automate_agent.git
```
```
cd my-llm
```
### 2. Install Dependencies
-bash
-Copy
-Edit
```
pip install -r requirements.txt
```
### 3. Set Up Environment Variables
 1.Create a .env file and add your AI Proxy Token:

- bash
- Copy
- Edit
  ```
  echo "AIPROXY_TOKEN=your_token_here" > .env
  ```
Note: Replace your_token_here with your actual AI Proxy Token.

### 4. Run Locally
- bash
- Copy
- Edit
```
python run.py
```
## Running with Docker
To deploy using Docker, follow these steps:

### 1. Build the Docker Image
- bash
- Copy
- Edit
docker build -t llm .
### 2. Run the Docker Container
- bash
- Copy
- Edit
```
docker run --env-file .env -p 8000:8000 llm
```
This exposes the application on port 8000.

📌 Usage
Once the agent is running, it can:

Process and execute large language-based tasks.
Perform secure file operations.
Integrate with various APIs for task execution.
Full API documentation will be available soon.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributing
Contributions are welcome! Follow these steps to contribute:

Fork the repository on GitHub.
### 1.Create a new branch:
- bash
- Copy
- Edit
```
git checkout -b feature-branch
```
### 2.Make your changes and commit them:
- bash
- Copy
- Edit
```
git commit -m "Added new feature"
```
### 3.Push to GitHub:
- bash
- Copy
- Edit
```
git push origin feature-branch
```
Submit a Pull Request for review.
