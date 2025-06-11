# Awesome LLM Attack & Security Learning Resources 🤖🔒

A comprehensive list of learning resources for Large Language Model (LLM) security, prompt injection attacks, AI red teaming, and defensive measures. Perfect for security researchers, penetration testers, developers, and AI enthusiasts.

## 🎯 Table of Contents

- [Learning Platforms & Interactive Training](#learning-platforms--interactive-training)
- [Official Documentation & Standards](#official-documentation--standards)
- [Practical Exercises & CTF Challenges](#practical-exercises--ctf-challenges)
- [Vulnerable Applications & Labs](#vulnerable-applications--labs)
- [Tools & Frameworks](#tools--frameworks)
- [Research Papers & Technical Articles](#research-papers--technical-articles)
- [Community Resources & Repositories](#community-resources--repositories)
- [Industry Guides & Best Practices](#industry-guides--best-practices)
- [Video Resources & Tutorials](#video-resources--tutorials)

---

## 📚 Learning Platforms & Interactive Training

### **PortSwigger Web Security Academy**
- **URL**: https://portswigger.net/web-security/llm-attacks
- **Type**: Comprehensive Training Course
- **Description**: Extensive coverage of web LLM attacks including prompt injection, insecure output handling, training data poisoning, and API exploitation. Covers both direct and indirect prompt injection techniques.
- **Key Topics**: LLM API attacks, excessive agency, indirect prompt injection, insecure output handling
- **Level**: Beginner to Advanced

### **Learn Prompting - Prompt Hacking**
- **URL**: https://learnprompting.org/docs/prompt_hacking/injection
- **Type**: Educational Documentation
- **Description**: Detailed explanation of prompt injection fundamentals with examples of direct injection, indirect injection, code injection, and recursive injection attacks.
- **Key Topics**: Types of prompt injection, real-world examples (Remoteli.io incident), defense strategies
- **Level**: Beginner to Intermediate

### **Gandalf by Lakera**
- **URL**: https://gandalf.lakera.ai/
- **Type**: Interactive CTF Platform
- **Description**: Test your prompting skills by trying to make Gandalf reveal secret information through prompt injection techniques.
- **Key Topics**: Practical prompt injection, social engineering, defense evasion
- **Level**: Beginner to Advanced

### **Immersive Labs - AI Prompting**
- **URL**: https://prompting.ai.immersivelabs.com/
- **Type**: Interactive Training Platform
- **Description**: Hands-on exercises for learning prompt injection and AI security concepts.
- **Level**: Intermediate

---

## 🏛️ Official Documentation & Standards

### **OWASP Top 10 for LLM & Generative AI**
- **URL**: https://genai.owasp.org/
- **Type**: Security Standards & Guidelines
- **Description**: The definitive resource for LLM security risks. Covers the top 10 most critical vulnerabilities in LLM applications with comprehensive mitigation strategies.
- **Key Topics**: Prompt injection, insecure output handling, training data poisoning, supply chain vulnerabilities, sensitive information disclosure
- **Status**: OWASP Flagship Project

### **IBM - Prompt Injection Guide**
- **URL**: https://www.ibm.com/topics/prompt-injection
- **Type**: Corporate Documentation
- **Description**: Enterprise-focused guide to understanding and mitigating prompt injection attacks.
- **Level**: Intermediate

### **Microsoft Azure - AI Red Teaming**
- **URL**: https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming
- **Type**: Official Microsoft Documentation
- **Description**: Comprehensive guide to planning and executing red teaming exercises for LLM applications.
- **Key Topics**: Red teaming methodology, testing frameworks, best practices
- **Level**: Advanced

---

## 🎮 Practical Exercises & CTF Challenges

### **Prompt Airlines by Wiz**
- **URL**: https://promptairlines.com/
- **Type**: AI Security CTF
- **Description**: Interactive challenge where you manipulate a customer service AI chatbot to get a free airline ticket. Created by Wiz security researchers.
- **Key Topics**: Social engineering, prompt manipulation, business logic bypass
- **Level**: Beginner to Intermediate

### **Secdim AI Games**
- **URL**: https://play.secdim.com/game/ai
- **Type**: Prompt Injection Games
- **Description**: Collection of prompt injection challenges and games for hands-on learning.
- **Level**: Beginner to Intermediate

### **SpyLogic by Scott Logic**
- **URL**: https://github.com/ScottLogic/prompt-injection
- **Type**: Open Source CTF Platform
- **Description**: Two-mode application: Go undercover to extract secrets from ScottBrewBot, or configure defenses and try to crack your own system.
- **Key Features**: Defense configuration, attack simulation, educational gameplay
- **Level**: Intermediate to Advanced

---

## 🏗️ Vulnerable Applications & Labs

### **Damn Vulnerable LLM Agent**
- **URL**: https://github.com/WithSecureLabs/damn-vulnerable-llm-agent
- **Type**: Vulnerable Application
- **Description**: Educational chatbot with intentional vulnerabilities for learning ReAct agent prompt injection, including Thought/Action/Observation injection.
- **Key Features**: Two flags to capture, SQL injection via LLM, realistic vulnerable environment
- **Technologies**: Langchain, GPT-4, Streamlit
- **Level**: Intermediate to Advanced

### **OWASP Vulnerable LLM Applications**
- **URL**: https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/wiki/Vulnerable-LLM-Applications
- **Type**: Collection of Vulnerable Apps
- **Description**: Curated list of intentionally vulnerable LLM applications for security testing and research.
- **Level**: Intermediate to Advanced

---

## 🛠️ Tools & Frameworks

### **PyRIT - Python Risk Identification Tool**
- **URL**: https://azure.github.io/PyRIT/
- **Type**: Microsoft Open Source Framework
- **Description**: Comprehensive framework for assessing security and safety issues in generative AI systems. Designed for AI red teaming with extensible architecture.
- **Key Components**: Orchestrators, targets, converters, scorers, memory systems, auxiliary attacks
- **Features**: Dataset management, prompt transformation, automated scoring, attack orchestration
- **Level**: Advanced

### **LLM Security Framework**
- **URL**: https://github.com/greshake/llm-security
- **Type**: Research & Security Framework
- **Description**: Collection of tools and research for LLM security testing and analysis.
- **Level**: Intermediate to Advanced

### **Prompt Analysis Tools (PallMS)**
- **URL**: https://github.com/mik0w/pallms
- **Type**: Analysis Framework
- **Description**: Tools for analyzing and testing LLM prompts for security vulnerabilities.
- **Level**: Advanced

---

## 📖 Research Papers & Technical Articles

### **Simon Willison - Prompt Injection Explained**
- **URL**: https://simonwillison.net/2023/May/2/prompt-injection-explained/
- **Type**: Expert Analysis & Video
- **Description**: Comprehensive explanation of prompt injection from security researcher Simon Willison, including video presentation, slides, and detailed transcript.
- **Key Insights**: Why AI-based defenses won't work, dual LLM pattern solution, security implications
- **Level**: Intermediate to Advanced

### **NCC Group - Exploring Prompt Injection Attacks**
- **URL**: https://research.nccgroup.com/2022/12/05/exploring-prompt-injection-attacks/
- **Type**: Security Research Paper
- **Description**: In-depth technical analysis of prompt injection attack vectors and defensive measures.
- **Level**: Advanced

### **Vicki Li - Hacking LLMs with Prompt Injections**
- **URL**: https://vickieli.medium.com/hacking-llms-with-prompt-injections-6a5ebffb182b
- **Type**: Technical Blog Post
- **Description**: Practical guide to understanding and executing prompt injection attacks.
- **Level**: Intermediate

### **Bugcrowd - AI Vulnerability Deep Dive**
- **URL**: https://www.bugcrowd.com/blog/ai-vulnerability-deep-dive-prompt-injection/
- **Type**: Security Analysis
- **Description**: Detailed analysis of prompt injection vulnerabilities from a bug bounty perspective.
- **Level**: Intermediate

### **Cobalt - Prompt Injection Attacks**
- **URL**: https://www.cobalt.io/blog/prompt-injection-attacks
- **Type**: Security Blog
- **Description**: Comprehensive overview of prompt injection attack techniques and mitigation strategies.
- **Level**: Intermediate

---

## 🌐 Community Resources & Repositories

### **Awesome LLM Security**
- **URL**: https://github.com/corca-ai/awesome-llm-security
- **Type**: Curated Resource List
- **Description**: Comprehensive collection of LLM security resources, papers, and tools.
- **Level**: All Levels

### **Awesome LLM Collection**
- **URL**: https://github.com/Hannibal046/Awesome-LLM
- **Type**: General LLM Resources
- **Description**: Massive collection of LLM-related resources including security considerations.
- **Level**: All Levels

### **Awesome AI Security**
- **URL**: https://github.com/ottosulin/awesome-ai-security
- **Type**: AI Security Resource Collection
- **Description**: Curated list of AI security resources, including LLM-specific content.
- **Level**: All Levels

### **AI Village - Threat Modeling LLMs**
- **URL**: https://aivillage.org/large%20language%20models/threat-modeling-llm/
- **Type**: Community Resource
- **Description**: Community-driven resource for threat modeling Large Language Models.
- **Level**: Intermediate to Advanced

### **LLM Security Resource Hub**
- **URL**: https://llmsecurity.net/
- **Type**: Specialized Portal
- **Description**: Dedicated portal for LLM security resources, news, and research.
- **Level**: All Levels

---

## 📋 Industry Guides & Best Practices

### **Bugcrowd - Ultimate Guide to AI Security**
- **URL**: https://www.bugcrowd.com/wp-content/uploads/2024/04/Ultimate-Guide-AI-Security.pdf
- **Type**: Comprehensive PDF Guide
- **Description**: Complete guide to AI security including LLM-specific threats and mitigation strategies.
- **Level**: Intermediate to Advanced

### **HackerOne - Managing Ethical and Security Risks in AI**
- **URL**: https://www.hackerone.com/resources/e-book/the-ultimate-guide-to-managing-ethical-and-security-risks-in-ai
- **Type**: Industry eBook
- **Description**: Enterprise-focused guide to managing AI security risks and ethical considerations.
- **Level**: Management & Technical

### **NVIDIA AI Red Team Introduction**
- **URL**: https://developer.nvidia.com/blog/nvidia-ai-red-team-an-introduction/
- **Type**: Technical Blog
- **Description**: Introduction to AI red teaming practices from NVIDIA's security team.
- **Level**: Intermediate to Advanced

### **Lakera - Real World LLM Exploits**
- **URL**: https://lakera-marketing-public.s3.eu-west-1.amazonaws.com/Lakera%2BAI%2B-%2BReal%2BWorld%2BLLM%2BExploits%2B(Jan%2B2024)-min.pdf
- **Type**: Research Report
- **Description**: Documentation of real-world LLM exploits and attack patterns.
- **Level**: Advanced

### **Snyk - OWASP Top 10 LLM Guide**
- **URL**: https://go.snyk.io/rs/677-THP-415/images/owasp-top-10-llm.pdf
- **Type**: Security Guide
- **Description**: Snyk's interpretation and practical guidance on the OWASP Top 10 for LLMs.
- **Level**: Intermediate

---

## 🎓 Advanced Resources & Specialized Topics

### **Offensive ML Playbook**
- **URL**: https://wiki.offsecml.com/Welcome+to+the+Offensive+ML+Playbook
- **Type**: Comprehensive Wiki
- **Description**: Detailed playbook for offensive machine learning techniques and red teaming.
- **Level**: Advanced

### **Promptingguide - Adversarial Risks**
- **URL**: https://www.promptingguide.ai/risks/adversarial
- **Type**: Technical Documentation
- **Description**: Deep dive into adversarial risks in prompt engineering and mitigation strategies.
- **Level**: Advanced

### **Promptingguide - RAG Security**
- **URL**: https://www.promptingguide.ai/research/rag
- **Type**: Research Documentation
- **Description**: Security considerations for Retrieval-Augmented Generation (RAG) systems.
- **Level**: Advanced

### **System Weakness - LLM Pentesting Series**
- **URL**: https://systemweakness.com/large-language-model-llm-pen-testing-part-i-2ef96acb6763
- **Type**: Technical Blog Series
- **Description**: Multi-part series on penetration testing Large Language Models.
- **Level**: Advanced

### **Blaze InfoSec - LLM Agent Hacking**
- **URL**: https://www.blazeinfosec.com/post/llm-pentest-agent-hacking/
- **Type**: Security Research
- **Description**: Advanced techniques for leveraging agent integration for remote code execution in LLM systems.
- **Level**: Expert

---

## 🔗 Additional Resources

### **MITRE ATLAS Matrix**
- **URL**: https://atlas.mitre.org/matrices/ATLAS/
- **Type**: Threat Framework
- **Description**: MITRE's framework for understanding adversarial tactics against machine learning systems.
- **Level**: Advanced

### **Unite AI - Prompt Hacking Guide**
- **URL**: https://www.unite.ai/prompt-hacking-and-misuse-of-llm/
- **Type**: Educational Article
- **Description**: Comprehensive overview of prompt hacking techniques and LLM misuse scenarios.
- **Level**: Intermediate

### **Crucible by Dreadnode**
- **URL**: https://crucible.dreadnode.io/
- **Type**: Advanced Platform
- **Description**: Advanced AI security testing platform (requires registration)
- **Level**: Advanced

---

## 🏷️ Tags & Categories

**By Difficulty Level:**
- 🟢 **Beginner**: Gandalf, Learn Prompting, Prompt Airlines
- 🟡 **Intermediate**: PortSwigger, OWASP, Most GitHub repos
- 🔴 **Advanced**: PyRIT, Offensive ML Playbook, Research papers
- ⚫ **Expert**: MITRE ATLAS, Advanced pentesting resources

**By Resource Type:**
- 📚 **Training**: PortSwigger, Learn Prompting, Immersive Labs
- 🎮 **CTF/Games**: Gandalf, Prompt Airlines, SpyLogic
- 🛠️ **Tools**: PyRIT, LLM Security Framework
- 📖 **Documentation**: OWASP, Microsoft, IBM
- 🏗️ **Labs**: Damn Vulnerable LLM Agent, Vulnerable Apps
- 🔬 **Research**: Simon Willison, NCC Group, Academic papers

**By Attack Type:**
- 💉 **Prompt Injection**: Most resources
- 🔓 **Jailbreaking**: Gandalf, CTF challenges
- 🎭 **Social Engineering**: Prompt Airlines, Real-world examples
- 🔧 **Tool Exploitation**: Agent-based vulnerabilities
- 📊 **Data Exfiltration**: Training data poisoning resources

---

## 📝 Contributing

Found a great LLM security resource? Please contribute by:
1. Opening an issue with the resource details
2. Submitting a pull request with proper categorization
3. Including a brief description and difficulty level

---

## ⚠️ Disclaimer

These resources are provided for educational and defensive security purposes only. Always ensure you have proper authorization before testing any techniques on systems you do not own. The authors and contributors are not responsible for any misuse of this information.

---

## 📊 Statistics

- **Total Resources**: 37 unique learning resources
- **Categories**: 8 main categories
- **Difficulty Levels**: 4 levels (Beginner to Expert)
- **Resource Types**: Training platforms, CTFs, tools, documentation, research
- **Last Updated**: June 2025

---

*This awesome list is maintained by the AI security community. Star ⭐ this repository to stay updated with the latest LLM security resources!*
