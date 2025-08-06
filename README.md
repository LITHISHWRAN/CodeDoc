# CodeDoc AI – Personal Code Debugging Mentor

CodeDoc AI is an intelligent AI-powered debugging assistant designed to help developers identify, understand, and fix code errors with ease. It doesn’t just correct bugs—it teaches you why they happened and how to avoid them in the future.

Think of it as a **mentor in your IDE** that provides:

-  Bug diagnostics  
-  Optimized code suggestions  
-  Detailed explanations  
-  Learning feedback  

---

##  Core Features

-  **Paste Code** – Input buggy code from any major programming language  
-  **Debug It** – Get line-by-line error analysis  
-  **Fix Suggestions** – Optimized solutions with explanations  
-  **Learn Why** – Educational feedback to improve your skills  

---

##  How We Use AI Concepts in CodeDoc AI

### 🔹 Prompting  
We use carefully designed system and user prompts to guide the AI as a debugging mentor. Prompts include code, language context, and user intent for accurate and relevant responses.

### 🔹 Structured Output  
AI responses are returned in a clean JSON format with fields like `errors`, `optimized_code`, and `explanation`—making them easy to display in the UI or use in other tools.

### 🔹 Function Calling  
AI determines which internal function to call (e.g., `extract_errors`, `suggest_fix`, `explain_errors`) based on user intent. This modular approach improves maintainability and accuracy.

### 🔹 RAG (Retrieval-Augmented Generation)  
We use a vector database to retrieve real examples, documentation, and past cases relevant to the user's code. This context is added to the AI prompt to improve accuracy and explanations.

---

