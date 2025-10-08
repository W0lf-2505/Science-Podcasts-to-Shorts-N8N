# Science-Podcasts-to-Shorts-N8N
🎧 Automated workflow using n8n to convert science podcasts into engaging YouTube Shorts — includes transcription, summarization, and AI video generation for bite-sized science content.

It listens for new episodes, identifies the most interesting short clips, generates catchy titles, descriptions, and tags, and uploads them directly to YouTube.

🚀 Features

🔍 Short Discovery: Detects the most engaging 30–60 sec highlights from long podcast episodes.

🧠 AI-Powered Metadata: Uses GPT to generate YouTube-optimized titles, descriptions, and tags.

🪄 Automated Posting: Uploads generated shorts automatically to your YouTube channel via API.

🔄 End-to-End Workflow: Fully managed in n8n, from podcast input to final video post.

📈 SEO Optimization: GPT ensures content is catchy, relevant, and searchable.

⚙️ Tech Stack

n8n – workflow orchestration

OpenAI GPT – content generation and summarization

YouTube Data API v3 – automated video uploads

RSS Feeds / APIs – to fetch new podcast episodes

🧩 Workflow Overview

Trigger: Detect new podcast episode from RSS or API.

Analyze: Use GPT to find highlight-worthy segments.

Generate: Create short scripts + metadata (title, desc, tags).

Assemble: Clip the segment (manually or via connected tools).

Upload: Automatically post the short to YouTube.
