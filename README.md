Innov-AI-tion — Agentic Healthcare & Fitness Assistant

This project is a prototype agentic AI system designed for the Innov-AI-tion challenge.
It acts like a personal wellness assistant that can plan, reason, adapt, and support users across fitness and lifestyle goals — without providing medical diagnosis.

The system demonstrates:

Goal-oriented behavior

Multi-step planning

Autonomous decision-making

Adaptation based on user feedback

Safe handling of health-related guidance

🧠 Problem

Most fitness apps only track data, but they don’t:

understand long-term goals

reason through constraints

adjust plans automatically

explain why they recommend something

Users lose motivation and consistency.

🎯 Solution

Our system behaves like an AI coach/agent:

1️⃣ User sets a goal (e.g., lose weight safely, build stamina)
2️⃣ Agent creates a personalized weekly plan
3️⃣ It explains the reasoning behind suggestions
4️⃣ It monitors progress or feedback
5️⃣ It updates the plan automatically when things change

It focuses on safe lifestyle guidance — not diagnosis.

🏗️ System Architecture (High-Level)

UI Layer – simple interface for interacting with the agent

Agent Core – planning + reasoning loop

Memory (user_memory.db) – remembers history and adapts

LLM / ML Logic – generates plans and explanations

Tools – (optional) reminders, logs, or future integrations

User → UI → Agent → Tools/Data → Memory → Adapted Plan

🚀 Features

✔ Personalized wellness planning
✔ Reasoning explanations
✔ Long-term objective tracking
✔ User memory + adaptation
✔ Safe guardrails (no medical diagnosis)

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/LakshayMaheshwari/Innovation_project.git
cd Innovation_project

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Create a .env file (required)

Create a file named .env in the project root:

OPENAI_API_KEY=YOUR_KEY_HERE
DATABASE_URL=sqlite:///user_memory.db


Keys must not be hard-coded — they are loaded securely from .env.

4️⃣ Run the app
python app/main.py


(or update this if your entry file is different)

🧪 Example Interaction

User:

I want to improve my fitness but I get tired easily.

Agent:

I created a gentle weekly plan with walking and stretching.
Because your fatigue is high, I reduced intensity and added rest days.
We will review progress every 7 days.

🔒 Ethics & Safety

No diagnosis or medical advice

Focus on habits, movement, and awareness

Encourages doctor consultation when needed

Transparent explanations of decisions

📌 Limitations & Future Work

🚧 Limited dataset
🚧 Prototype UI
🚧 Basic agent reasoning loop

Future improvements:

Wearable integration

Progress visualization

Multi-agent coordination

Smarter scheduling tools

📹 Demo Video

A short demo video is required by the challenge (uploaded separately).

📄 License

Open-source — aligns with challenge rules.
