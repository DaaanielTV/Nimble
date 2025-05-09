---
title: Nimble
emoji: 🐳
colorFrom: blue
colorTo: blue
sdk: docker
pinned: true
app_port: 5173
license: mit
short_description: Generate any application with deepseek
models:
  - deepseek-ai/DeepSeek-V3-0324
---

# Nimble 🐳
Nimble is a coding platform powered by DeepSeek AI, designed to make coding smarter and more efficient. Tailored for developers, data scientists, and AI engineers, it integrates generative AI into your coding projects to enhance creativity and productivity.

## How to use it locally

Run Nimble locally

Clone the repo using git

git clone https://huggingface.co/spaces/enzostvs/nimble

Install the dependencies (make sure node is installed on your machine)

npm install

Create your .env file and add the HF_TOKEN variable

Make sure to create a token with inference permissions and optionally write permissions (if you want to deploy your results in Spaces)

Build the project

npm run build

Start it and enjoy with a coffee ☕

npm run start