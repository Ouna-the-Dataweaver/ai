# ai

This is a small repo where I store stuff useful for ai coding: skills, prompts, agent setups. 

## Skills

### Structured commits
I'm a lazy person who quite often work on different features inside one branch, so with this skill it's easy to untangle changes into logical commits. Plus, it has commit style I'm usually using. 

### Slurm
TODO: gonna be a skill for starting slurm jobs, where one can specify their slurm setup, name of machines etc

## Prompts
Prompts for agents. 

### Context agent
Search MCPs have low free limits. So, I wanted to utilize web chats efficiently for repo-specific questions. This agent would take in your query and enrich it with repo-specific context. It adds code snippets, info on your tech stack into the request, and you just paste a prepared detailed question to chat of your choice! 

### Search/Deep Search
Prompts to run search inside your repo with opencode. Check the opencode.json to see how to setup these agents. Be careful, deep search agent can use like 50-150 searches sometimes(depending on how hard the question is and on your LLM of choice), so with free MCP quotas you'll not be able to use this one a lot. 
