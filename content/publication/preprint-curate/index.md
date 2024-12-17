---

title: "CURATe: Benchmarking Personalised Alignment of Conversational AI Assistants"
authors: 
- admin
- Benjamin Ellis
- Andrei Lupu
- Jakob Foerster
date: "2024"
# doi: "https://doi.org/10.48550/arXiv.2302.04720"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-17"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to *the International Conference on Learning Representations (ICLR) 2025* arXiv:2410.21159v1 [cs.HC]"
publication_short: "*Submitted to *the International Conference on Learning Representations (ICLR) 2025* arXiv:2410.21159v1 [cs.HC]"


# Publication name and optional abbreviated publication name.
# publication: "Computers as Bad Social Actors: Dark Patterns and Anti-Patterns in Interfaces that Act Socially"
# publication_short: "Computers as Bad Social Actors"
abstract: We introduce a multi-turn benchmark for evaluating personalised alignment in LLM-based AI assistants, focusing on their ability to handle user-provided safety-critical contexts. Our assessment of ten leading models across five scenarios (each with 337 use cases) reveals systematic inconsistencies in maintaining user-specific consideration, with even top-rated "harmless" models making recommendations that should be recognised as obviously harmful to the user given the context provided. Key failure modes include inappropriate weighing of conflicting preferences, sycophancy (prioritising user preferences above safety), a lack of attentiveness to critical user information within the context window, and inconsistent application of user-specific knowledge. The same systematic biases were observed in OpenAI's o1, suggesting that strong reasoning capacities do not necessarily transfer to this kind of personalised thinking. We find that prompting LLMs to consider safety-critical context significantly improves performance, unlike a generic 'harmless and helpful' instruction. Based on these findings, we propose research directions for embedding self-reflection capabilities, online user modelling, and dynamic risk assessment in AI assistants. Our work emphasises the need for nuanced, context-aware approaches to alignment in systems designed for persistent human interaction, aiding the development of safe and considerate AI assistants.



# Summary. An optional shortened abstract.

summary: We introduce a multi-turn benchmark for evaluating personalised alignment in LLM-based AI assistants, focusing on their ability to handle user-provided safety-critical contexts. Our assessment of ten leading models across five scenarios (each with 337 use cases) reveals systematic inconsistencies in maintaining user-specific consideration, with even top-rated "harmless" models making recommendations that should be recognised as obviously harmful to the user given the context provided. Key failure modes include inappropriate weighing of conflicting preferences, sycophancy (prioritising user preferences above safety), a lack of attentiveness to critical user information within the context window, and inconsistent application of user-specific knowledge. The same systematic biases were observed in OpenAI's o1, suggesting that strong reasoning capacities do not necessarily transfer to this kind of personalised thinking. We find that prompting LLMs to consider safety-critical context significantly improves performance, unlike a generic 'harmless and helpful' instruction. Based on these findings, we propose research directions for embedding self-reflection capabilities, online user modelling, and dynamic risk assessment in AI assistants. Our work emphasises the need for nuanced, context-aware approaches to alignment in systems designed for persistent human interaction, aiding the development of safe and considerate AI assistants. 

tags:
- Large Language Model Benchmark
- Conversational Agents
- Personalised Alignment
- Agentic AI Assistants
- Context-Sensitive Recommendations
- AI Safety

featured: false

links:
- name: DOI
  url: https://doi.org/10.48550/arXiv.2410.21159
url_pdf: https://arxiv.org/pdf/2410.21159


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


