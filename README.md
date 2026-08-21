# AI-Launch-PMM-Agent
An agentic AI system I designed and built to automate product marketing launch management, cross-functional workflows, task tracking, and stakeholder communications.

The Problem
Complex product launches require PMMs to coordinate dozens of tasks, owners, dependencies, deadlines, and stakeholders. Much of that work is manual: checking status trackers, identifying blockers, following up with owners, and communicating launch health.

I wanted to see how much of that operational work could be automated with AI.

What I Built
I built an AI-powered Launch PMM Agent that operates through Slack and connects directly to a live Google Sheets launch tracker.

The agent enables teams to:

Ask questions about a launch in natural language
See individual tasks, owners, deadlines, and blockers
Update task status directly from Slack
Identify overdue and at-risk work
Generate launch health snapshots
View tasks across multiple simultaneous launches
Reduce manual PMM coordination and status tracking
How It Works
Slack → Slack App → Heroku/Python → Google Sheets API + Intent Engine

Slack serves as the user interface, Heroku hosts the Python application, and the Google Sheets API connects the agent to live launch data.

Built With
Claude Code · Python · Slack API · Google Sheets API · Heroku

Project Documentation
This repository includes:

System Architecture — architecture, integrations, and deployment model
Commands Reference — examples of the workflows and capabilities available to users
Why I Built It
I believe the next generation of product marketers won’t just use AI to create content. They’ll use agents to automate GTM operations and give teams more time to focus on customers, strategy, positioning, and growth.

This project was an experiment in building that future.
