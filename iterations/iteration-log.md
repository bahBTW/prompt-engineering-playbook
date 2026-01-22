# Prompt Iteration Log

This document records applied experiments comparing
unstructured prompts versus structured prompts
using a consistent Role / Task / Constraints / Output format.

The goal is to evaluate the impact of prompt structure
on output quality, consistency, and controllability.

## Experiment 1 — Task-Oriented Web Development Prompt

### Context
Tested prompt behavior while asking the model to create
a simple JavaScript-based to-do list application.

### Hypothesis
A structured prompt would produce:
- clearer separation of concerns
- more complete code
- fewer assumptions

### Comparison
- Unstructured prompt: open-ended request
- Structured prompt: role, task, constraints, output format

### Observations
- Structured prompt produced more organized code
- Reduced unnecessary explanations
- Better adherence to requested technologies

### Outcome
Structured prompting improved technical accuracy
and reduced irrelevant output.

### Learning
Prompt structure significantly improves
developer-oriented tasks where precision matters.

## Experiment 2 — Customer Communication Messages

### Context
Generated customer-facing messages for a retail environment,
based on real-world communication needs.

### Hypothesis
Structured prompts would reduce ambiguity
and produce more professional, consistent messaging.

### Comparison
- Without structure: variable tone and verbosity
- With structure: controlled tone and format

### Observations
- Structured prompts produced clearer, more concise messages
- Reduced risk of inappropriate tone
- Improved consistency across outputs

### Outcome
Structured prompting increased reliability
for business communication tasks.

### Learning
Explicit constraints are essential for tone-sensitive outputs.

## Experiment 3 — Travel Planning & Spreadsheet Generation

### Context
Tested prompts for generating structured travel planning data,
including destination lists and spreadsheet-style outputs.

Tests were performed across different models.

### Hypothesis
Defining output format explicitly would improve
data usability and reduce manual post-processing.

### Comparison
- Free-form prompts vs structured output constraints
- Cross-model behavior observation

### Observations
- Structured prompts produced more consistent tables
- Reduced formatting errors
- Improved cross-model reliability

### Outcome
Output constraints significantly improve
AI-generated structured data.

### Learning
Format specification is critical
for data-oriented tasks.
