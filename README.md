# Dave Wang

I’m a master’s student at Cornell Tech. I build backend services and full-stack applications. My recent work focuses on tracing measurements to their sources and keeping long-running tasks consistent across retries and reconnects.

### [Materials Evidence Workbench](https://github.com/YuqiWang1106/materials-evidence-workbench)

I designed and developed a materials knowledge-base workflow with contributions from other project members. Reviewers can trace a measurement to the source that supports it and see when a change calls for a new review. The [offline example](https://github.com/YuqiWang1106/materials-evidence-workbench/tree/main/examples/evidence_review) walks through that decision using synthetic data and no API keys.

### [Reliable Learning Workflows](https://github.com/YuqiWang1106/Adaptive-Learning-Chatbot)

A Django and Celery application for long-running learning tasks. A run keeps its identity across retries, saves checkpoints, and records progress events so the browser can pick up where it left off. Follow a run through the [execution service](https://github.com/YuqiWang1106/Adaptive-Learning-Chatbot/blob/main/learning_apps/adaptive_agent/run_service.py) and the [offline integration tests](https://github.com/YuqiWang1106/Adaptive-Learning-Chatbot/tree/main/tests/integration/agent).

### [Peer Assessment System · AssessMate](https://github.com/YuqiWang1106/assessmate)

I led a six-person team building a Django application for peer assessment. Instructors create assessments, students review their teammates, and instructors review the results. We cache generated feedback so a report can reuse an earlier analysis. The [data models](https://github.com/YuqiWang1106/assessmate/blob/main/my_app/models.py) show how each response connects to an assessment and how we identify cached feedback for a team and question.

### [CookAI](https://github.com/RuolongMao/CookAI)

CookAI is a team-built recipe app. Users can ask for recipe ideas, save recipes, and share them with other cooks. I worked on the React and FastAPI setup, the sign-in and registration screens, and the [database models and recipe-sharing API](https://github.com/RuolongMao/CookAI/commit/dc3c6701a585feab2a3d2a3805e80bf9ccdb59a9).
