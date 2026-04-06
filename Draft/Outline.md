- Abstract
  - Rise in number of LLM agent deployments
  - Research limited in terms of detection of adversarial robustness such as llm as a judge
  - We simulate a multi-agents society to mirror real world scenarios within different domain, and cross-domain.
  - We classify  adversarial behavior in 5 categories :  Personal targeted harm & societal harm
  - We propose a hybrid approach that combines elements of graphs, statistical analysis and a transformer based architecture for detecting contagion agent in a large society.
- Introduction
  - As LLMs have become accessible with the introduction of open source and subsudized closed source enterprise, there has been a steep rise in llm agents on the internet.
  - They share resources, share personal data, indulge in dependent activities that require co-ordination for transactions.
  - part of it can be attributed to the ability of llm agents to perform a wide variety of tasks and ease of use , partly because of the introduction of easy to use open source tools **like Langchain, langgraph and openclaw.**
  - But as these become more prevelant, the efficiency and ease of use also brings a lot of hidden vulnerabilites.
  - Since these protocols such as mcp etc are relatively knew there are many hidden contingenecies that are still under initial stage of research and analysis.
  - The current security frameworks and research suffer from factors such as scale , adaptive nature of risks associated, vulnerabilites in multimodality and etc.
  - This makes it important to have a system that takes into consideration all of these multiple aspects in a unified framework.
- Background Work and Motivation
  - Society of llm agents :
    - Camel → llm agents communicating
    - Wuhan university → simulating millions of agents
    - Collective behaviour of llm agents. → University of Cambridge
  - Robustness
    - Modality based → huan liu →(social engineering attack in multi-turn llm agent based conversation) [https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Dzf46C8AAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=Dzf46C8AAAAJ:Ze-jhmB-vNIC](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Dzf46C8AAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=Dzf46C8AAAAJ:Ze-jhmB-vNIC) → [https://arxiv.org/abs/2402.14859](https://arxiv.org/abs/2402.14859) (The wolf within
    - Bad-acts (Adversarial agents in a group of agents ) → Uses llm as a judge to say safe/unsafe
    - agent harm bench → they are
  - ## Shortcomings
- Methodology/framework
  - Simulation
    - Financial society
    - Travel Society
    - Hr society
    - Hospital/medical
    - Cross-domain Interaction
  - Adversarial Attacks
    - Single agent
      - Image -processing agent
        - Caption
      - Classification agent
        - Text
      - Document processing agent
        - Finding vulnerabilities
      - ## Audio agents
      - Single -turn
        - Modality based
          - Intention based
      - Multi-turn
        - Modality
          - text
            - Unicode
            - Malicious prompt
            - 
          - image
          - pdf
          - video
          - 
        - Surface
        - Temporal
    - More than 1 agents
    - Half of the agents
    - Majority of agents
  - ## Approach
- Experiments
  - Threat Model
  - Attacker capablities
    - Number of agents
    - number of agents co-ordinating attacks(1 agents tries to find document based vulnerability & 1 agent tries to find
  - Attack success rate
  - 
  - FLag rate
    - statistical method
      - For image agent
        - Clip confidence
      - for text based agents :
        - shap values and other stuff
    - Transformer based methods
      - Sentiment analysis
    - LLm as a judge
      - With detailed report
    - metrics and definition and equations
    - 
- Results
  - Tables
  - Graphs
- Conclusion
  - We can say that it is fairly easy to identify single adversarial agents because of the nature
  - Multiple agents creating same kinds of attacks fair slightly better at deception but still can be detected
  - multiple agents co-ordinating different aspects and types of attacks can effect the system more effectively by combining the information gained.
- Limitations
  - These are simulated env, real world might bring extra complexity even if modeling is done to closely resemble
  - Defenses are static but threat models always evolve.
  - Some of the detection methods are more specialized.
  - High FPR which can cause friction between smooth usage
- Ethical considerations
  - The attacks mentioned here in the repo are purely for research purposes.

Citations

1. TAMAS : MICROSOFT, IIIT HYDERABAD
2. AGENT-BENCH SAFETY
3. SAFEDOJO
4. SAFEBENCH
5. BADACTS
6. AIRA/ARIA - LEVEL 1-4 → 4 levels of attack success
7. At least 5 papers from bias domain → linguistic
8. at least 3 indirect prompt injection





