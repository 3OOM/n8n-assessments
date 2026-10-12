# LMS Submission Form & Description Content

> **Copy and paste the section below directly into the LMS Description / Comments submission box.**

---

### LMS Description Text (Copy Below):

**Assessment Name:** N8N Hands-On Beginner | Topic 1: Create Your First Workflow  
**Student Name:** Abhishek Nikam  
**Student Email:** abhishek.n@tayanasolutions.com  
**Workflow Name:** My First N8N Workflow  
**GitHub Repository Link:** https://github.com/3OOM/n8n-assessments/tree/main/topic-01-create-your-first-workflow  
**Demo Video Link:** [REPLACE WITH YOUR LOOM OR YOUTUBE LINK]  

---

#### 1. Workflow Summary & Implementation
The workflow begins with an initial **Manual Trigger** node (`When clicking ‘Test workflow’`) connected left-to-right to an **Edit Fields (Set)** node. The Edit Fields node is configured with a String key `greeting` assigned the exact value `Hello, n8n!`. The workflow was executed, saved, and validated to yield the required JSON output `{ "greeting": "Hello, n8n!" }` across Table, JSON, and Schema views with zero execution errors.

#### 2. Challenges Faced & Resolutions
- **Node Naming Discrepancies in n8n v1+:** In n8n versions prior to 1.0, the node was simply named "Set". In n8n v1.0.0 and above, the node is listed in the search panel as "Edit Fields (Set)".  
  *Resolution:* Located the modern `n8n-nodes-base.set` node under the "Edit Fields (Set)" action name and verified that typeVersion 3.4 assignments work smoothly.
- **Strict String Type & Casing Matching:** Ensuring exact punctuation (`Hello, n8n!`) and lowercase field naming (`greeting`) without unintended whitespace or trailing characters.  
  *Resolution:* Validated the payload directly through the built-in JSON inspector and Schema tab, confirming the string primitive type and clean JSON syntax.

#### 3. Assumptions Made
- **Manual Trigger Scope:** Assumed this baseline workflow is intended for isolated testing and verification via the manual editor canvas rather than automated triggers (like Webhook or Schedule).
- **Data Payload Standard:** Assumed standard UTF-8 string encoding for the greeting text and single-item array execution output per standard n8n data conventions.

#### 4. Known Limitations
- The workflow requires human intervention to trigger via the "Test workflow" button; it cannot be triggered autonomously on external events without attaching a Webhook or Cron/Schedule trigger node.
- The payload is currently static; dynamic parameterization via expressions (`{{ $json... }}`) or external inputs can be added in subsequent topics.

#### 5. Additional Improvements Implemented
- **Unified Assessments Repository Structure:** Created a single organized GitHub repository (`n8n-assessments`) with topic-based subfolders to keep course submissions consolidated and easy for evaluators to navigate.
- **Execution State Pinning (pinData):** Included pinned test execution data in the exported JSON file so reviewers can immediately inspect the validated `{ "greeting": "Hello, n8n!" }` output upon importing into their own n8n instance without needing to re-run.
- **Multi-View Schema Documentation:** Fully documented how the output reflects across Table, JSON, and Schema tabs to ensure complete compliance with assessment grading criteria.
