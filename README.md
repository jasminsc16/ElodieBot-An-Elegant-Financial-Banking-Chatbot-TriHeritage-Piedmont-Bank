# ElodieBot-An-Elegant-Financial-Banking-Chatbot-TriHeritage-Piedmont-Bank

Executive Summary
We developed an agentic chatbot assistant (ElodieBot) to assist with providing basic-to-intermediate financial knowledge and information about the services of the fictional TriHeritage Piedmont Bank. (based off services offered by Atlantic Union Bank, an American regional bank headquartered in Richmond, Virginia https://www.atlanticunionbank.com/.) (This project has no affiliation with Atlantic Union Bank and all demo applications are fictional and for demonstrational purposes only.) The chatbot was built using LangGraph and the Gemini API. We also created a Gradio app demo (special thanks to Anshuj for the research & development of this).
 
When conceptualizing ElodieBot, I wanted to develop it in a way not meant/suggested to be a replacement of financial advisors. Instead, ElodieBot serves as space for returning/potential customers to ask their initial financial questions without fear of embarrassment or shame. In my personal experience, learning about finance can seem like a never-ending maze, but yet, you are also worried about wasting people’s time with “stupid” questions. Financial literacy is increasingly important, but there can still be both personal hesitation and social barriers in the way of getting started. ElodieBot serves as a helpful starting companion and a place for individuals to gather their thoughts. Users can then feel better prepared for meeting with a financial advisor through discussions with the chatbot.
 
Use Case/Problem
A (fictional) bank, TriHeritage Piedmont Bank, is eager for innovation. It is a traditional, regional bank located in Maryland, Virginia, and North Carolina. Renowned for its refined, but down-to-earth services, head leadership has heard a lot about chatbots lately and is looking to launch a test of a brand-new chatbot that can help potential and returning customers with general financial knowledge and information about the bank's services. Our team has signed a contract to develop the initial versions of the chatbot. We are instructed to keep the chatbot in line with what the bank is known for: trust and respect with a touch of Southern elegance.
 
GenAI Capabilities Used
Capability 1 : Grounding - This project is using grounding/augmentation data. "Data coming from either external APIs (like Google Search) or internal APIs and data sources. This data permits the Financial Model (FM) to produce answers for a specific context, keeping responses current, relavant without retraining the entire FM. This type of data also supports reducing hallucinations" (Nawalgaria, Larios, Secchi, Styer, Aniftos, Petragallo, & Kartakis, 2025).
 
Capability 2 : Agents - This project is using an agent. "A Generative AI agent can be defined as an application that attempts to achieve a goal by observing the world and acting upon it using the tools that it has at its disposal. Agents are autonomous and can act independently of human intervention, especially when provided with proper goals or objectives they are meant to achieve. Agents can also be proactive in their approach to reaching their goals. Even in the absence of explicit instruction sets from a human, an agent can reason about what it should do next to achieve its ultimate goal" (Wiesinger, Marlow, & Vuskovic, 2025).
 
Capability 3 : Function Calling - This project is using function calling. "Functions work very similarly in the world of agents, but we can replace the software developer with a model. A model can take a set of known functions and decide when to use each Function and what arguments the Function needs based on its specification" (Wiesinger, Marlow, & Vuskovic, 2025).
 
Workflow Process
-          	Brainstorming general project ideas as a team and landing on a finance-themed chatbot
-          	Determining that for chatbot development, the “Day 3 - Building an agent with LangGraph” notebook created by MarkMcD/Mark McDonald would be a strong reference
-          	Developed initial system instructions
-          	Brainstorming ideas for what a “live menu” would like for a financial chatbot
-          	Further provided details for initial system instructions to give the chatbot personality
-          	Decided on a name for the chatbot (“Elodie”) through etymology of names (Elodie is thought to mean “riches, wealth” using Gothic elements)
-          	Finalized the live menu using Atlantic Union Bank information
-          	Using Day 3 notebook as a reference, updated tools to be relevant to ElodieBot (instead of “orders” as with BaristaBot, the system will take “appointments”)
-          	Cleaned notebook of unnecessary information/test code
-          	Researched and developed Gradio app demo to show how the chatbot would operate on a user interface (UI)
-          	Clearly documented notebook to highlight the five distinct demonstrations of the chatbot along with the LangGraph-produced graph elements
-          	Wrote introduction to the notebook with the clear use case/how GenAI solves the problem
-          	Performed careful review of all code and documentation to ensure everything ran smoothly
 
All work was completed using Kaggle and Google Colab, with Discord and Gmail being our main forms of communication.
