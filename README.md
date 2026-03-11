# Blog Writing Agent

An AI-powered multi-agent system that automatically researches, plans, and writes high-quality blog articles.
The project uses a structured agent workflow to generate well-organized blog content along with supporting images and references.

---

## Project Overview

The Blog Writing Agent is designed to automate the process of blog creation using artificial intelligence.
Instead of manually researching, structuring, and writing a blog post, the system uses a multi-agent architecture to perform these tasks automatically.

The system analyzes the given topic, decides whether external research is required, collects relevant information, generates a structured outline, writes each section of the blog, and finally merges all sections into a complete article.
Additionally, the system can generate images for the blog to improve readability and visual appeal.

This project demonstrates how modern AI frameworks can be combined to build intelligent autonomous agents capable of performing complex writing tasks.

---

## Key Features

* Automated blog generation from a single topic
* Multi-agent workflow using graph-based architecture
* Automatic research using web search APIs
* Structured blog planning and section generation
* Automatic image generation for blog posts
* Markdown output for easy publishing
* Streamlit-based interactive user interface

---

## System Architecture

The project uses a multi-agent workflow with the following components:

1. **Router Agent**
   Determines whether the topic requires external research.

2. **Research Agent**
   Collects relevant information from web sources if research is required.

3. **Orchestrator Agent**
   Creates a structured outline and task plan for the blog.

4. **Worker Agents**
   Each worker generates a specific section of the blog based on the plan.

5. **Reducer Agent**
   Combines all sections and integrates images into the final blog.

This architecture allows the system to produce organized and high-quality blog content automatically.

---

## Technologies Used

* Python
* LangGraph
* LangChain
* OpenAI API
* Tavily Search API
* Streamlit
* Pydantic

---

## Project Structure

```
blog-writing-agent
│
├── bwa_backend.py
├── bwa_frontend.py
├── images/
├── notebooks (.ipynb)
├── generated blog files (.md)
├── .gitignore
└── README.md
```

---

## Installation

Clone the repository:

```
git clone https://github.com/yourusername/blog-writing-agent.git
cd blog-writing-agent
```

Install dependencies:

```
pip install -r requirements.txt
```

Create a `.env` file and add your API keys:

```
OPENAI_API_KEY=your_openai_key
TAVILY_API_KEY=your_tavily_key
```

---

## Running the Project

Start the Streamlit interface:

```
streamlit run bwa_frontend.py
```

Then open the provided local URL in your browser.

---

## Example Output

The system generates:

* Fully structured blog articles
* Markdown files ready for publishing
* Supporting AI-generated images

These outputs can be found in the project directory after running the agent.

---

## Applications

* Content creation and blogging
* Technical documentation generation
* Educational content generation
* AI-assisted writing tools
* Automated knowledge summarization

---

## Future Improvements

* Support for multiple languages
* Integration with blogging platforms
* Improved citation and research verification
* Enhanced UI for blog editing
* Support for additional image styles

---

## Author

Sachin Adhikari

---

## License

This project is created for educational and research purposes.
