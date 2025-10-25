# Team Allocation Simulator

A small simulator to explore strategies for assigning people to teams/projects given skills, availability and preferences.

Features
- Define people, projects, roles and constraints
- Plug-in allocation strategies (greedy, annealing, genetic, ILP)
- Batch experiments and export results (JSON/CSV)

Quick start (pick based on project language)
- Node.js: npm install && npm start -- --config configs/example.json
- Python: python -m simulator --config configs/example.yaml

Outputs
- Allocation maps (person → role), run metrics, CSV/JSON exports for analysis
