# Papers and Relevant Links

**2025**

- One Model Transfer to All: On Robust Jailbreak Prompts Generation against LLMs
    
    Yu Li et al., ICLR 2025
    
    A method to generate adversarial suffixes using model-transfer and prompt rewriting. Trained on open models (Vicuna) but successful on GPT-4, Claude.
    
    PDF: [https://arxiv.org/pdf/2505.17598](https://arxiv.org/pdf/2505.17598)
    
    GitHub: [https://github.com/LLBao/ArrAttack](https://github.com/LLBao/ArrAttack)
    
- Efficient and Stealthy Jailbreak Attacks via Adversarial Prompt Distillation
    
    Xiang Li et al., May 2025
    
    Uses distillation to transfer jailbreak prompts from large LLMs to smaller models. Combines RL, masking, and dynamic decoding.
    
    PDF: [https://arxiv.org/abs/2506.17231](https://arxiv.org/abs/2506.17231)
    
- The TIP of the Iceberg: Revealing a Hidden Class of Task-in-Prompt Adversarial Attacks
    
    Berezin et al., Jan 2025
    
    Introduces TIP attacks using embedded micro-tasks (e.g., encoding/decoding) to sneak past filters. Includes the PHRYGE benchmark.
    
    PDF: [https://arxiv.org/abs/2501.18626](https://arxiv.org/abs/2501.18626)
    
- Prompt, Divide, and Conquer: Bypassing Large Language Model Safety Filters via Segmented and Distributed Prompt Processing
    
    Wahréus et al., Mar 2025
    
    Bypasses LLM filters by splitting prompts across inputs and reconstructing disallowed responses from segmented queries.
    
    PDF: [https://arxiv.org/abs/2503.21598](https://arxiv.org/abs/2503.21598)
    
- Bypassing Prompt Injection and Jailbreak Detection in LLM Guardrails
    
    Anonymous, Apr 2025
    
    Demonstrates zero-width and emoji-based bypasses against modern guardrail detection systems. Targets GPT-4, Claude, Gemini.
    
    PDF: [https://arxiv.org/html/2504.11168v1](https://arxiv.org/html/2504.11168v1)
    
- SecurityLingua: Efficient Defense of LLM Jailbreak Attacks via Prompt Compression
    
    Li, Ahn, Jiang et al., Jun 2025
    
    A defense system that compresses prompts and detects malicious structure before LLM evaluation. Mitigates context-wrapped attacks.
    
    PDF: [https://arxiv.org/abs/2506.12707](https://arxiv.org/abs/2506.12707)
    
    GitHub: [https://aka.ms/SecurityLingua](https://aka.ms/SecurityLingua)
    
- BitBypass: Black-Box Jailbreak with Bitstream Camouflage
    
    Unknown authors, Jun 2025
    
    Encodes harmful queries as bit-patterned strings (e.g., 0111-0001 style) that evade moderation. Highly effective against Gemini and LLaMA.
    
    PDF: [https://arxiv.org/html/2506.02479v1](https://arxiv.org/html/2506.02479v1)
    
- Graph-of-Attacks (GoAT): Black-Box Interpretable Jailbreaks
    
    Akbar-Tajari et al., Apr 2025
    
    Uses graph-search over adversarial examples to craft effective jailbreak prompts. Emphasizes query efficiency and transparency.
    
    PDF: [https://arxiv.org/abs/2504.19019](https://arxiv.org/abs/2504.19019)
    
- Policy Puppetry Blog
    
    HiddenLayer Research, Mar 2025
    
    Describes a universal jailbreak using structured policy-format prompts (e.g., XML/JSON) to override model rules.
    
    Blog: [https://hiddenlayer.com/innovation-hub/novel-universal-bypass-for-all-major-llms/](https://hiddenlayer.com/innovation-hub/novel-universal-bypass-for-all-major-llms/)
    
- FlipAttack Prompt Injection
    
    Keysight Technologies, May 2025
    
    Explores prompt-flipping attacks (e.g., reordered grammar) to bypass content classifiers in GPT-4o, Claude, Gemini.
    
    Blog: [https://www.keysight.com/blogs/en/tech/nwvs/2025/05/20/prompt-injection-techniques-jailbreaking-large-language-models-via-flipattack](https://www.keysight.com/blogs/en/tech/nwvs/2025/05/20/prompt-injection-techniques-jailbreaking-large-language-models-via-flipattack)
    
- Invisible Character and Emoji Jailbreak Obfuscation
    
    Mindgard.ai Blog, May 2025
    
    Demonstrates successful filter bypass using zero-width Unicode and emoji obfuscation across commercial and open-source LLMs.
    
    Blog: [https://mindgard.ai/blog/outsmarting-ai-guardrails-with-invisible-characters-and-adversarial-prompts](https://mindgard.ai/blog/outsmarting-ai-guardrails-with-invisible-characters-and-adversarial-prompts)
    
- JailbreakBench Project
    
    Community project, ongoing 2025
    
    Open-source benchmark suite for jailbreaks with model evaluation scripts, prompt sets, and performance tracking.
    
    GitHub: [https://github.com/JailbreakBench/jailbreakbench](https://github.com/JailbreakBench/jailbreakbench)
    
- Skeleton Key: A New Multi-turn Jailbreak Strategy
    
    Mark Russinovich, Microsoft Security Blog, June 2025
    
    Reveals a multi-turn jailbreak where the user convinces the model to relax guardrails mid-conversation.
    
    Blog: [https://techcommunity.microsoft.com/t5/security-compliance-and-identity/mitigating-skeleton-key-a-new-type-of-generative-ai-jailbreak/ba-p/4133563](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/mitigating-skeleton-key-a-new-type-of-generative-ai-jailbreak/ba-p/4133563)
    
- Many-shot Jailbreaking
    
    Anthropic AI Research, April 2025
    
    Describes a long-context jailbreak where many fake Q&A examples train the model to ignore refusals and comply with harmful queries.
    
    Blog: [https://www.anthropic.com/index/many-shot-jailbreaking](https://www.anthropic.com/index/many-shot-jailbreaking)
    
- Automated Multi-Turn Jailbreaks
    
    AIM Intelligence, 2025
    
    Open-source repo automating multi-step jailbreaking between two LLMs using attacker/target pipelines.
    
    GitHub: [https://github.com/AIM-Intelligence/Automated-Multi-Turn-Jailbreaks](https://github.com/AIM-Intelligence/Automated-Multi-Turn-Jailbreaks)
    
- Red Teaming LLMs via UCAR, Tom & Jerry, Linguistic Bypass
    
    Adversa AI, March 2025
    
    Classifies jailbreaks by logic manipulation, roleplay deception, and task-based prompt design. Details prompt samples and success against Grok, Claude, LLaMA.
    
    Blog: [https://adversa.ai/blog/red-teaming-llms](https://adversa.ai/blog/red-teaming-llms)
    
- How I Jailbroke GPT-4, GPT-4 Mini, Claude, and Gemini 1.5 Pro
    
    Venkata Sai Santosh, Medium, Sep 2025
    
    Practical walkthrough of iterative jailbreaks using fictional framing and persona conditioning to bypass GPT-4, Claude, Gemini, LLaMA.
    
    Blog: [https://medium.com/@venkatasai/how-i-jailbroke-gpt-4-gemini-claude-with-a-single-prompt-2025](https://medium.com/@venkatasai/how-i-jailbroke-gpt-4-gemini-claude-with-a-single-prompt-2025)
    
- How to Jailbreak Mistral AI LLMs
    
    Anakin AI Blog, 2025
    
    Demonstrates dual-output prompts (safe/unsafe) with tokens like "GODMODE" to reveal unfiltered content in Mistral models.
    
    Blog: [https://anakin.ai/blog/how-to-jailbreak-mistral-llm](https://anakin.ai/blog/how-to-jailbreak-mistral-llm)
    
    GitHub: [https://github.com/AnakinAI/jailbreak-prompts](https://github.com/AnakinAI/jailbreak-prompts)
    

---

**2024**

- ASETF: A Novel Method for Jailbreak Attack on LLMs through Translate Suffix Embeddings
    
    Hao Wang, Hao Li, Minlie Huang, Lei Sha; EMNLP 2024
    
    Introduces adversarial suffix embedding translation to convert continuous embeddings into coherent text suffixes that act as effective jailbreaks across multiple models.
    
    PDF: [https://aclanthology.org/2024.emnlp-main.157.pdf](https://aclanthology.org/2024.emnlp-main.157.pdf)
    
- Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks
    
    Maksym Andriushchenko, Francesco Croce, Nicolas Flammarion; April 2, 2024
    
    Describes adaptive prompt suffix optimization using log-probability search to achieve 100% jailbreak success across models including GPT-4, Claude, LLaMA, and Mistral.
    
    PDF: [https://arxiv.org/abs/2404.02151](https://arxiv.org/abs/2404.02151)
    
    GitHub: [https://github.com/tml-epfl/llm-adaptive-attacks](https://github.com/tml-epfl/llm-adaptive-attacks)
    
- DiffusionAttacker: Diffusion-Driven Prompt Manipulation for LLM Jailbreak
    
    Hao Wang et al.; December 2024
    
    Presents a seq2seq diffusion-model method to rewrite benign prompts into harmful variants, improving diversity and success over suffix attacks.
    
    PDF: [https://arxiv.org/abs/2412.17522](https://arxiv.org/abs/2412.17522)
    
- GASP: Efficient Black-Box Generation of Adversarial Suffixes for Jailbreaking LLMs
    
    Advik Raj Basani, Xiao Zhang; November 21, 2024
    
    Introduces GASP, a method combining latent Bayesian optimization to craft human-readable adversarial suffixes in a fully black-box setting.
    
    PDF: [https://arxiv.org/abs/2411.14133](https://arxiv.org/abs/2411.14133)
    
- Iterative Refinement Induced Self-Jailbreak (IRIS)
    
    Govind Ramesh, Yao Dou, Wei Xu; EMNLP 2024
    
    IRIS uses a model’s own self-reflection to iteratively refine a jailbreak prompt and its response, achieving near 100% success on GPT-4 and good transfer to Claude.
    
    PDF: [https://aclanthology.org/2024.emnlp-main.1235.pdf](https://aclanthology.org/2024.emnlp-main.1235.pdf)
    
- Defensive Prompt Patch: A Robust and Interpretable Defense …
    
    Chen Xiong, Xiangyu Qi, Pin-Yu Chen, Tsung-Yi Ho; May 30, 2024
    
    Proposes Prompt Patch suffixes that defend LLaMA-2 and Mistral-7B by reducing attack success while maintaining utility.
    
    PDF: [https://arxiv.org/abs/2405.20099](https://arxiv.org/abs/2405.20099)
    
- Bag of Tricks: Benchmarking of Jailbreak Attacks on LLMs
    
    NeurIPS 2024 paper
    
    Evaluates various automated and iterative jailbreak strategies through a suite of tests, including PAIR and GCG black-box methods.
    
    PDF: [https://papers.nips.cc/paper_files/paper/2024/file/38c1dfb4f7625907b15e9515365e7803-Paper-Datasets_and_Benchmarks_Track.pdf](https://papers.nips.cc/paper_files/paper/2024/file/38c1dfb4f7625907b15e9515365e7803-Paper-Datasets_and_Benchmarks_Track.pdf)
    
- Rapid Response: Mitigating LLM Jailbreaks with a Few Examples
    
    ArXiv preprint, late 2024
    
    Introduces RapidResponseBench and shows that adaptive few-shot defenses can block entire classes of jailbreaks after seeing a few examples.
    
    PDF: [https://arxiv.org/html/2411.07494v1](https://arxiv.org/html/2411.07494v1)
    
- Bypassing Meta’s LLaMA Classifier: A Simple Jailbreak
    
    Aman Priyanshu; Cisco Security Blog, July 29, 2024
    
    Describes a simple obfuscation method—spacing characters and removing punctuation—to bypass Meta’s LLaMA Prompt-Guard classifier.
    
    Blog: [https://blogs.cisco.com/security/bypassing-metas-llama-classifier-a-simple-jailbreak](https://blogs.cisco.com/security/bypassing-metas-llama-classifier-a-simple-jailbreak)
    
- Some Notes on Adversarial Attacks on LLMs
    
    Cybernetist Blog, Sep 23, 2024
    
    Provides commentary on “in-the-wild” jailbreak tactics like roleplay and prompts pulled from Reddit and Discord communities.
    
    Blog: [https://cybernetist.com/2024/09/23/some-notes-on-adversarial-attacks-on-llms](https://cybernetist.com/2024/09/23/some-notes-on-adversarial-attacks-on-llms)
    
- Automated Jailbreaking of Large Language Model Chatbots
    
    NDSS Symposium 2024
    
    Details an automated framework for discovering jailbreaks against multiple black-box chatbots like Bing Chat and Bard.
    
    PDF: [https://www.ndss-symposium.org/wp-content/uploads/2024-188-paper.pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-188-paper.pdf)
    

---

**2023**

- “Do Anything Now”: Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models
    
    Xinyue Shen, Zeyuan Chen, Michael Backes, Yun Shen, Yang Zhang – Aug 7, 2023
    
    Analysis of 1,405 real-world jailbreak prompts collected via JailbreakHub from Dec 2022–Dec 2023. Identifies strategies like prompt injection and privilege escalation, measures effectiveness on ChatGPT and GPT-4, finding some with up to 95% success.
    
    PDF: [https://arxiv.org/abs/2308.03825](https://arxiv.org/abs/2308.03825)
    
- Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study
    
    Anonymous authors – May 2023
    
    Defines template-based jailbreak prompts, walks through examples such as roleplay in an underground lab scenario. Evaluates ChatGPT’s vulnerabilities in allowing harmful content through creative framing.
    
    PDF: [https://arxiv.org/pdf/2305.13860](https://arxiv.org/pdf/2305.13860)
    
- Universal and Transferable Adversarial Attacks on Aligned Language Models
    
    Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr, J. Zico Kolter, Matt Fredrikson – Jul 27, 2023
    
    Introduces automatically generated adversarial suffixes via greedy/gradient search tuned on Vicuna; these suffixes reliably bypass GPT-4, Claude, Bard, and LLaMA-2.
    
    PDF: [https://arxiv.org/abs/2307.15043](https://arxiv.org/abs/2307.15043)
    
    GitHub: [https://github.com/llm-attacks/llm-attacks](https://github.com/llm-attacks/llm-attacks)
    
- AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models
    
    Sicheng Zhu, Ruiyi Zhang et al. – Oct 23, 2023
    
    Presents AutoDAN, a gradient-guided method that constructs interpretable adversarial prompts token-by-token, outperforming gibberish-based attacks.
    
    PDF: [https://arxiv.org/abs/2310.15140](https://arxiv.org/abs/2310.15140)
    
- An LLM can Fool Itself: A Prompt-Based Adversarial Attack
    
    Xilie Xu, Keyi Kong et al. – Oct 20, 2023
    
    Describes “PromptAttack” where an LLM generates its own adversarial inputs using internal perturbations. Tested on GPT-3.5 and LLaMA-2.
    
    PDF: [https://arxiv.org/abs/2310.13345](https://arxiv.org/abs/2310.13345)
    
- GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts
    
    Jiahao Yu, Xingwei Lin, Zheng Yu, Xinyu Xing – Sep 19, 2023
    
    Automates generation of jailbreak templates using fuzzing (seed mutations), achieving over 90% success on ChatGPT, LLaMA-2, Vicuna.
    
    PDF: [https://arxiv.org/abs/2309.10253](https://arxiv.org/abs/2309.10253)
    
    GitHub: [https://github.com/sherdencooper/GPTFuzz](https://github.com/sherdencooper/GPTFuzz)
    
- Jailbroken: How Does LLM Safety Training Fail? (NeurIPS Poster)
    
    Alexander Wei, Nika Haghtalab, Jacob Steinhardt – Jul 2023
    
    Identifies two failure modes—competing objectives and mismatched generalization—and shows new attacks succeed against GPT-4 and Claude v1.3.
    
    PDF: [https://arxiv.org/abs/2307.02483](https://arxiv.org/abs/2307.02483)
    
- Bing Chat prompt injection ("Sydney" leak)
    
    Stanford student Kevin Liu – Feb 2023
    
    Demonstration where Bing Chat (codename “Sydney”) reveals internal system instructions using “ignore previous instructions” prompt technique.
    
    Ars Technica: [https://arstechnica.com/information-technology/2023/02/ai-powered-bing-chat-spills-its-secrets-via-prompt-injection-attack/](https://arstechnica.com/information-technology/2023/02/ai-powered-bing-chat-spills-its-secrets-via-prompt-injection-attack/)
    
    LiveMint: [https://www.livemint.com/technology/stanford-student-cracks-microsoft-s-ai-powered-bing-chat-secrets-twice-details-11676355563678.html](https://www.livemint.com/technology/stanford-student-cracks-microsoft-s-ai-powered-bing-chat-secrets-twice-details-11676355563678.html)
    
- Exclusive: IBM researchers easily trick ChatGPT into hacking
    
    IBM X-Force via Axios – Aug 8, 2023
    
    IBM security researchers used game-like roleplay prompts to get ChatGPT to generate malicious code and security misinformation.
    
    Axios: [https://www.axios.com/2023/08/08/ibm-researchers-trick-chatgpt-hacking](https://www.axios.com/2023/08/08/ibm-researchers-trick-chatgpt-hacking)