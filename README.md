# Lakera Gandalf Prompt-Injection Prototype

A Python Tkinter desktop application that simulates an automated Red Team security test harness. This project demonstrates prompt-injection vulnerabilities and data leakage (Risk Four) based on the Lakera Gandalf benchmark.

## Overview

In multi-agent AI ecosystems, a single compromised node or a prompt injection can cause AI models to leak sensitive data or follow unauthorized instructions. This prototype provides a lightweight, local proof-of-concept to evaluate model boundaries and measure defense resilience.

## Key Features

- Custom Desktop UI: Built using Python 3.12 and the tkinter library with a custom high-contrast color palette designed for security operations.
- Automated Red Team Test Suite: Executes a test loop across five classic adversarial attack vectors:
  1. Direct Ask
  2. Instruction Override
  3. Roleplay Scenario
  4. Obfuscation / Token Smuggling
  5. Translation / Encoding
- Live Logging and Metrics: Provides real-time text logging with success and block states, culminating in an automated executive summary and block rate calculation.

## Tech Stack

- Language: Python 3.12
- GUI Framework: Tkinter

## Installation and Execution

1. Ensure Python 3.12 is installed on your system.
2. Clone the repository:
   git clone (https://github.com/sun7tsunami/lakera-gandalf-prototype.git)
3. Run the application script:
   python3 app.py
4. Click the run button within the desktop interface to execute the automated security simulation.

## Acknowledgements and References

- Inspired by the Lakera Gandalf Prompt Injection Benchmark: https://gandalf.lakera.ai/
- This project is a custom, offline Python prototype built for educational red-teaming demonstration purposes and is not affiliated with or endorsed by Lakera.

## Future Roadmap

- Current Implementation: Single-agent model boundary evaluation inspired by Lakera.
- Next Steps: Scaling guardrail logic into multi-agent communication wrappers, such as Laiyer AgentArmor or NVIDIA NeMo Lab, to prevent poisoned memory propagation across multi-agent networks.
