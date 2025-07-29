# Claude Meal Planning System
A comprehensive meal planning application using claude code subagets to create personalized weekly meal plans.  Currently only tested with 1 person for the meal plan.

Shout out to https://github.com/vijaythecoder/awesome-claude-agents for inspiration for the structure of this repository


## How It Works

The system uses **8 specialized agents** that work together:

1. **Meal Plan Orchestrator** - Coordinates the entire process and manages workflow between agents
2. **Macro Calculator Agent** - Calculates precise macro distribution across all meals
3. **Dietary Restriction Analyzer** - Analyzes dietary needs and creates safe ingredient lists
4. **Recipe Generator** - Creates individual recipes that meet specific nutritional targets
5. **Recipe Critic Validator** - Validates each recipe for safety, nutrition, and compliance
6. **Recipe Optimizer Agent** - Fine-tunes portions to hit exact macro targets
7. **Batch Cooking Planner** - Creates Sunday prep schedules and shopping lists
8. **Meal Plan Formatter** - Generates professional documentation (planned for future use)

## Technical Architecture

The system demonstrates:
- **Agent Coordination**: How specialized agents can work together on complex tasks
- **Workflow Management**: Orchestrated multi-step processes with dependencies
- **Quality Control**: Validation and optimization loops ensure accuracy
- **Documentation Generation**: Automated creation of user-friendly guides

