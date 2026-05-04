\# AI-Powered Autonomous QA Test Scenario Generator

This project demonstrates an end-to-end autonomous Quality Assurance (QA) pipeline using \*\*Zapier\*\*, \*\*Groq API (Llama 3)\*\*, and \*\*Notion\*\*.



\## 🚀 Live Demo \& Templates

Want to replicate this system in your own workspace? Use the templates below:

\- \*\*Test the System (Google Forms):\*\* \[Click here to submit a module name](https://forms.gle/vPA6ja9T7UPCZK2R8)

\- \*\*Zapier Workflow Template:\*\* \[Duplicate my Zap](https://zapier.com/templates/details/ai-powered-qa-automation-ff2435?secret=MTp0ZW1wbGF0ZTo2cGlEQ18xTkl2MGc2dTQwU1VnRlZnMzVMMEVJTEtHOU5MNC11eDN5YXB3OmFtNzE4dQ)

\- \*\*Notion Database Template:\*\* \[Duplicate the QA Database](https://broadleaf-pint-86e.notion.site/34fbd2eee947801db5cbfba2cf33abf8?v=34fbd2eee94780f295e7000c9969e419\&source=copy\_link)



\## 🏗️ Architecture

1\. \*\*Trigger:\*\* Google Forms collects the name of the software module to be tested.

2\. \*\*Brain:\*\* Groq API (Llama 3) processes requirements using prompt engineering and guardrails.

3\. \*\*Database:\*\* Automated test scenarios are saved and categorized in a structured Notion database.



\## 🧠 The AI Prompt (Guardrails Included)

To prevent hallucinations and ensure valid outputs, the following prompt architecture is used in the Groq API step:



> "You are a Senior QA Analyst. The user will provide a text input. First, evaluate if the input is a valid software module or feature (e.g., 'Login Page', 'Payment Gateway'). 

> - If the input is meaningless, unrelated, or a random word (e.g., 'Kastamonu', 'apple'), DO NOT generate tests. Return exactly this error message: 'Invalid input. Please provide a valid software module name.'

> - If the input is valid, generate exactly 3 standardized test scenarios in this format: 1 Positive Test, 1 Negative Test, and 1 Validation Test. Output only the test scenarios."



\## ✨ Features

\- \*\*Zero-Code Integration:\*\* Fully automated workflow.

\- \*\*AI-Driven Logic:\*\* High-speed inference and logical consistency.

\- \*\*Safety Guardrails:\*\* Prevents AI hallucinations using advanced prompting.

\- \*\*Academic Standard:\*\* Documentation follows IEEE conference paper standards.



\## 📄 Academic Reference

This architecture is documented in a formal academic paper formatted according to IEEE standards. You can find the full research paper (Turkish \& English) in the repository files (`IEEE\_TestCase\_Paper.pdf` and `IEEE\_TestCase\_Paper.docx`).

