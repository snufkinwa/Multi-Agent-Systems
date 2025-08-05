### 🔍 Reflection on Multi-Agent System

**Architecture:**
The system uses four agents—Inventory, Quoting, Sales, and Finance—each with clearly defined roles. I chose this structure to simplify coordination and allow each agent to focus on a single responsibility. The orchestrator routes requests and ensures agents act in the right sequence.

**Performance Evaluation:**
From the test results, the system successfully processed full orders when inventory allowed and triggered reorders or partial fulfillment when needed. Liquidity and asset values updated correctly, and user-friendly responses were generated. A highlight was its ability to dynamically switch to partial orders while initiating restocking.

**Improvements:**

1. Add persistent memory to track customer preferences or repeat orders.
2. Replace the rule-based orchestrator with a planning agent to handle more complex workflows.

This project helped me move from prompt-based AI to designing full agentic systems with real-world logic and decision-making.
