# Building AI Products with OpenAI course
Built an amazing service that takes in my favorite podcast and produced a newsletter with a summary of an episode. 

## The Problem

🎧 Discovering the right podcast episodes within a busy schedule is tough. Despite show notes and timestamps, it's hard to grasp an episode's uniqueness and decide if it's worth a listen. Simplifying this process to find truly engaging content is the key challenge.

## Solution

💡 Our solution involves crafting a tailored weekly newsletter summarizing new podcast episodes. By analyzing guest details, key themes, and highlights, users can swiftly identify episodes of interest. This solution streamlines discovery, enabling informed listening choices.

## Approach

We will divide the approach to building this product into three parts -

- Part 1: use a Large Language Model (LLM) from OpenAI to build the information extraction functionality paired with a Speech to Text model for transcribing the podcast
- Part 2: use a simple cloud deployment provider (modal) to easily convert the information extraction function to run on demand - this would be the app backend
- Part 3: use ChatGPT from OpenAI as your coding assistant to create and deploy a front-end that allows users to experience the end to end functionality
