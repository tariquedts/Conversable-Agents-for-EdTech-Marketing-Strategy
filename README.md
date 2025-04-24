# 🤖 Conversable Agents for EdTech Marketing Strategy

This project demonstrates how to build **Conversable AI Agents** using the `autogen` library to simulate strategic marketing dialogues in the context of an **EdTech company** selling **Project Management courses**. The agents are configured to act as a **Chief Marketing Officer (CMO)** and a **Chief Executive Officer (CEO)**, debating between B2B and B2C marketing approaches.

---

## 🚀 Project Objectives

- Build intelligent agents using `autogen.ConversableAgent`
- Simulate strategic dialogue to explore B2B vs B2C marketing
- Generate actionable marketing strategies using GPT-powered agents
- Log conversation history and analyze cost, token usage, and summaries

---

## 🧱 Project Structure

### 📁 Key Components

- `ConversableAgent`: Framework used to simulate human-like AI roles
- **CMO Agent**: Focuses on B2B marketing strategy
- **CEO Agent**: Advocates for B2C marketing strategy
- **Hybrid Strategy Simulation**: Facilitates back-and-forth debate for alignment

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/tariquedts/conversable-edtech-agent.git
cd conversable-edtech-agent
```

### 2. Install Dependencies

```bash
pip install autogen openai python-dotenv
```

### 3. Add Your OpenAI API Key

Create a `.env` file in the root folder:

```env
OPENAI_API_KEY=openai.api_key = "sk*****************kA"
```

---

## 📌 Features

- ✅ GPT-powered agent responses
- ✅ Role-based dialogue simulation (CMO vs CEO)
- ✅ Cost and token tracking
- ✅ Strategic marketing recommendations for EdTech
- ✅ Support for prompt injection and customization
- ✅ Easy-to-modify agent behavior and configuration

---

## 📊 Example Use Case

Simulate a strategic discussion:

- 🎯 Prompt: “Suggest B2B marketing strategies for project management courses.”
- 💬 Output: Multi-turn dialogue proposing real-world tactics like webinars, partnerships, and ROI metrics
- 💼 Application: Internal decision-making or campaign planning

---

## 🧠 Sample Agent Config

```python
agent_mkt_str = ConversableAgent(
    name="Marketing_Strategist",
    system_message="You are an expert EdTech marketing strategist with experience in B2B and B2C growth.",
    llm_config={
        "config_list": [{"model": "gpt-4o-mini"}],
        "temperature": 0
    },
    code_execution_config=False,
    human_input_mode="NEVER"
)
```

---

## 📈 Sample Output

> “Here are solid B2B strategies for Project Management courses:  
> - Targeted content marketing with whitepapers  
> - Hosting introductory webinars  
> - Building long-term corporate partnerships...”

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

Built with 💡 using:
- [Autogen by Microsoft](https://github.com/microsoft/autogen)
- OpenAI GPT models
- Python Ecosystem: `dotenv`, `openai`, `IPython`

---

## 📬 Contact

For queries or collaborations:  
📧 tarique.dts@gmail.com  
🐙 GitHub: [your-username](https://github.com/tariquedts)

```

---

Would you like me to export this as a downloadable `.md` file, or help you structure the GitHub repo layout (folders, `main.py`, etc.)?