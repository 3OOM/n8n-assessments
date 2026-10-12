# n8n Practical Assessments Repository

> **Student / Trainee:** Abhishek Nikam  
> **Institution:** Tayana Academy  
> **Course:** n8n Workflow Automation (Hands-On Practical Series)  
> **Target Platform:** n8n version 1.0.0+  

---

## 📌 Repository Overview

This repository serves as a centralized, structured portfolio containing all completed practical assessments for the **n8n Workflow Automation** curriculum at Tayana Academy. Organizing all topics into a single repository keeps course submissions clean, accessible, and easily reviewable by instructors without managing dozens of separate repositories.

Each assessment is housed in its own dedicated directory containing:
1. **Exported Workflow (`.json`)**: Importable directly into any n8n instance (Cloud, Self-Hosted, Docker, or Local).
2. **Comprehensive Documentation (`README.md`)**: Full step-by-step breakdown, architecture diagram, node configurations, testing results, and troubleshooting.
3. **Evidence & Verification (`screenshots/`)**: High-resolution screenshots of canvas layout, configuration panels, test executions, and JSON/Table/Schema output views.
4. **Demonstration & Submission Notes**: Ready-to-use submission comments for LMS grading and demo video guide.

---

## 📂 Assessments Index

| Folder | Topic / Assessment | Difficulty | Status | Deliverables |
| :--- | :--- | :--- | :--- | :--- |
| [`topic-01-create-your-first-workflow/`](./topic-01-create-your-first-workflow/) | **Topic 1: Create Your First Workflow**<br>Manual Trigger + Edit Fields (Set) -> `Hello, n8n!` | Beginner | ✅ Completed | [Workflow JSON](./topic-01-create-your-first-workflow/My_First_N8N_Workflow.json) • [Docs](./topic-01-create-your-first-workflow/README.md) |
| [`topic-02-workflow-execution-and-debugging/`](./topic-02-workflow-execution-and-debugging/) | **Topic 2: Understanding Workflow Execution & Debugging Basics**<br>Manual Trigger ➔ Edit Fields ➔ HTTP Request (Error & Resolution) | Beginner | ✅ Completed | [Workflow JSON](./topic-02-workflow-execution-and-debugging/Topic_2_Debugging_Workflow.json) • [Docs (MD)](./topic-02-workflow-execution-and-debugging/README.md) • [Docs (PDF)](./topic-02-workflow-execution-and-debugging/README.pdf) |
| [`topic-03-core-nodes-and-data-mapping/`](./topic-03-core-nodes-and-data-mapping/) | **Topic 3: Working with Core Nodes & Data Mapping**<br>Manual Trigger ➔ Set Original Data ➔ Modify & Map | Beginner | ✅ Completed | [Workflow JSON](./topic-03-core-nodes-and-data-mapping/Topic_3_Core_Nodes_Workflow.json) • [Docs (MD)](./topic-03-core-nodes-and-data-mapping/README.md) • [Docs (PDF)](./topic-03-core-nodes-and-data-mapping/README.pdf) |
| [`topic-04-json-objects-arrays-expressions/`](./topic-04-json-objects-arrays-expressions/) | **Topic 4: Working with JSON Objects, Arrays & Expressions**<br>Manual Trigger ➔ Mock Nested JSON Data ➔ Extract Values | Beginner | ✅ Completed | [Workflow JSON](./topic-04-json-objects-arrays-expressions/Topic4_JSON_Data_Assessment.json) • [Docs (MD)](./topic-04-json-objects-arrays-expressions/README.md) • [Docs (PDF)](./topic-04-json-objects-arrays-expressions/README.pdf) |
| [`topic-05-expressions-and-variables/`](./topic-05-expressions-and-variables/) | **Topic 5: Expressions & Variables**<br>Manual Trigger ➔ Generate Employee Data ➔ Process Expressions | Beginner | ✅ Completed | [Workflow JSON](./topic-05-expressions-and-variables/Topic5_Expressions_Assessment.json) • [Docs (MD)](./topic-05-expressions-and-variables/README.md) • [Docs (PDF)](./topic-05-expressions-and-variables/README.pdf) |
| `topic-06-conditional-logic/` *(upcoming)* | Topic 6: Flow Control & Conditional Logic (If / Switch) | Intermediate | ⏳ Upcoming | — |

---

## 🚀 How to Import Any Workflow into n8n

Follow these simple steps to import and run any workflow from this repository in your n8n workspace:

1. **Clone or Download this repository:**
   ```bash
   git clone https://github.com/3OOM/n8n-assessments.git
   ```
2. **Open n8n:**
   - Access your n8n instance (Cloud, Docker, or local at `http://localhost:5678`).
3. **Import Workflow:**
   - Click **Workflows** in the left sidebar.
   - Click the **three dots menu (`...`)** in the top right corner (or use keyboard shortcut `Ctrl+O` / `Cmd+O`).
   - Select **Import from File...** and select the `.json` file from the respective topic folder (e.g., `topic-01-create-your-first-workflow/My_First_N8N_Workflow.json`).
   - Alternatively, open the `.json` file in an editor, copy the entire JSON text, click on the blank canvas in n8n, and press `Ctrl+V` (or `Cmd+V`) to paste nodes directly.
4. **Test the Workflow:**
   - Click **Test workflow** at the bottom of the canvas.
   - Click on the last node to view the resulting payload in **Table**, **JSON**, or **Schema** views.

---

## 🛠️ Global Prerequisites & Tools

- **n8n:** Version 1.0.0 or higher
- **Browser:** Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari
- **Screen Recording:** Loom, YouTube, or OBS Studio
- **Version Control:** Git & GitHub

---

## 👤 Author Information

- **Name:** Abhishek Nikam
- **Email:** abhishek.n@tayanasolutions.com
- **GitHub:** [@3OOM](https://github.com/3OOM) (abhisheknikam3)
