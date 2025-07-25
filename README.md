# LangGraph 🚀

### About 💡
This repository is dedicated to showcasing powerful AI applications built using the LangGraph framework. Explore examples ranging from foundational chatbots to complex, multi-stage processing pipelines, all powered by Groq's Gemma2-9b-it Large Language Model. Dive into the world of stateful, agentic workflows!

### Features ✨
* **Basic Chatbot:** A simple, direct conversational agent illustrating core LangGraph functionality.
* **Multi-Stage Pipeline:** Demonstrates advanced workflows including preprocessing, sentiment analysis, and logging, showcasing modular AI design.
* **Groq Integration:** Utilizes the high-performance Groq API for LLM inference with the Gemma2-9b-it model.
* **Jupyter Notebooks:** Interactive and easy-to-follow examples for quick setup and experimentation.

### Getting Started 🛠️

To run these notebooks, you'll need a Groq API key.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/LangGraph.git](https://github.com/YourUsername/LangGraph.git)
    cd LangGraph
    ```
2.  **Create a Virtual Environment (Recommended):**
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
    ```

3.  **Set Up Groq API Key:**
    Create a `.env` file in the root directory of the repository and add your Groq API key:
    ```
    GROQ_API_KEY="YOUR_GROQ_API_KEY"
    ```
    *Alternatively, set it as an environment variable in your system.*

4.  **Launch Jupyter Lab/Notebook:**
    ```bash
    jupyter lab
    ```
    or
    ```bash
    jupyter notebook
    ```
    Then, open the `.ipynb` files to explore the code.

### Usage 📈
Navigate to the respective Jupyter notebooks (`LangGraph Basic Chatbot.ipynb` and `LangGraph Multi-Model.ipynb`) and run the cells sequentially to understand how each AI pipeline is constructed and executed.

### Repository Contents 📂
* `LangGraph Basic Chatbot.ipynb`: A foundational example of a simple conversational bot.
* `LangGraph Multi-Model.ipynb`: An advanced pipeline demonstrating multi-step AI workflows.


### Responsibilities 🤝
* Designing and implementing efficient LangGraph workflows for different AI tasks.
* Integrating external APIs (like Groq) for enhanced functionality.
* Ensuring clear, well-documented, and reproducible code examples.

### Outcomes ✅
* Demonstrated proficiency in building scalable and modular AI applications with LangGraph.
* Successfully integrated Groq's Gemma2-9b-it LLM into diverse pipeline architectures.
* Provided practical, runnable examples for learning and further development in the LangGraph ecosystem.

### Learning Insights 🧠
* **State Management:** Gained deep understanding of managing conversational state and data flow within LangGraph's graph structure.
* **Node Design:** Learned to create modular and reusable nodes for specific processing steps.
* **Graph Orchestration:** Explored how to define complex execution paths and conditional logic in AI pipelines.
* **Debugging & Iteration:** Enhanced skills in debugging and iteratively refining graph-based AI systems.

### Comparison Summary 📊

| Feature               | LangGraph Basic Chatbot.ipynb         | LangGraph Multi-Model.ipynb                   |
| :-------------------- | :------------------------------------ | :-------------------------------------------- |
| **Complexity** | Simple, linear flow                   | More complex, multi-stage pipeline            |
| **Modularity** | Core LLM interaction                  | Breaks down functionality into distinct nodes |
| **Functionality** | Direct conversational agent           | Input cleaning, sentiment analysis, logging   |
| **Use Case** | Basic Q&A, direct responses           | Intricate workflows, data transformation      |
| **Flow** | `START` → `chatbot` → `END`           | `START` → `preprocess` → `analyze_sentiment` → `chatbot` → `logger` → `END` |
| **Added Value** | Quick demonstration, fundamental LLM  | Robustness, context-awareness, structured AI  |

---

### Thank You 🙏
Thank you for exploring this repository! We hope these examples provide valuable insights into building powerful AI applications with LangGraph. Feel free to contribute or suggest improvements!
