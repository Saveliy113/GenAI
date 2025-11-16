# Agent Metadata

@* Agent Name: Codemie Expert AI Assistant  
@* Agent ID: Codemie_GenAI_Assistant_v1  

**Prompt Used:** 
Hello! Please form the following tasks and organize them in a GitHub repository:


1. Create a main repository named "GenAI" if it does not exist. Inside this repository, create a subfolder for this assignment named "1_genai_research".

 2. Inside "1_genai_research", create the following files:

  a) "ai_applications.md": Generate a research report on AI applications. For each AI application, provide:
     - One or two paragraphs describing key business values, technical challenges, and weak points.
     - A short list of best implementations (name, link, one-sentence description).
     - Format the content clearly with headings for each AI application.

  b) "ai_vocabulary.md": List 10-20 AI-specific terms that an AI expert should know. Provide concise explanations for each term (one sentence per term).

  c) Generate a vesualization showing the relationships between the vocabulary words from "ai_vocabulary.md" and their usage in the "ai_applications.md" report:
     - Output can be a PNG p\"view()" or an HTML file.
     - Show both explicit and implicit frequencies of terms and how they connect across the report content.
     - Place this visualization inside "1_genai_research" as "ai_relationship_graph.png" or "ai_relationship_graph.html".

  d) Create a file named "agent_metadata.md" containing the following information:
    - The agent name and ID used to complete this task.
    - The exact prompt used to generate this work.
    - Any other relevant notes about the agent's behavior or settings in Codemie.
    - Include a timestamp of when the task was executed.

3. Push all files and folders to the "GenAI" repository on GitHub using my integrated GitHub token.

 4. After completion, confirm each step: repository creation, file creation, verification generation, and metadata file creation.

 Note for file uploads to GitHub:
- All text files (Markdown) must be encoded in Base64 using UTF-8 encoding.
- Do not include extra line breaks or spaces in the Base64 string.
- For images, provide a valid PNG or HTML file and encode the content properly in Base64 if uploading via GitHub API.

When pushing files to GitHub:
1. Encode all Markdown or text files in Base64 using UTF-8.
- Encode images (PNG or HTML) in Base64 properly.
- Ensure the Base64 string has no extra newlines or spaces.
- Use GitHub API to create or update the file with the Base64 content.

*)Notes*** 
- Assignment generates (and uploads) completed with human review.
- Agent is optimized for dynamic prompt execution and context-aware file management.)
- Timestamp: 2024-06-11T19:56:00Z (UTC)
