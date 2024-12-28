# LLM4S2
LLM for System/Software Security

## Bug detection
* [Large Language Models Based JSON Parser Fuzzing for Bug Discovery and Behavioral Analysis ](https://it-bill.github.io/uploads/llm-json-parser-fuzzing-final-report.pdf) (Arxiv) 
  
  This paper presents JFuzz, leveraging Large Language Models (LLMs) to enhance JSON parser testing by generating test cases for bug discovery and analyzing behavioral diversity among parsers.
* [Your Fix Is My Exploit: Enabling Comprehensive DL Library API Fuzzing with Large Language Models](https://www.computer.org/csdl/proceedings-article/icse/2025/056900a508/215aWTZ8XRe) (ICSE 2025) 
  
  This paper introduces DFUZZ, a methodology that utilizes LLM from a white-box perspective, infers edge cases and generates an initial test program to provide efficient API fuzzing testing of DL libraries, effectively improving API coverage and vulnerability detection.
* [Fuzz4All: Universal Fuzzing with Large Language Models](https://dl.acm.org/doi/abs/10.1145/3597503.3639121) (ICSE 2024) 
  
  Fuzz4All is a universal fuzzer leveraging large language models to target diverse input languages and features. It employs an autoprompting technique and an LLM-powered fuzzing loop to generate realistic and diverse inputs, significantly improving code coverage and bug detection across various systems and languages compared to existing fuzzers.
* [Magneto: A Step-Wise Approach to Exploit Vulnerabilities in Dependent Libraries via LLM-Empowered Directed Fuzzing](https://dl.acm.org/doi/abs/10.1145/3691620.3695531) (ASE 2024) 
  
  Magneto is a step-wise approach that uses LLM-empowered directed fuzzing to exploit vulnerabilities in dependent libraries. It decomposes the fuzzing process into smaller steps, leveraging LLMs for seed generation, and has shown a 75.6% improvement in successfully exploiting vulnerabilities.
* [How Eﬀective Are They? Exploring Large Language Model BasedFuzz Driver Generation](https://dl.acm.org/doi/10.1145/3650212.3680355) (ISSTA 2024)
  
  This paper provides an in-depth study of the effectiveness of Large Language Models in generatingfuzzy testdrivers by designing and evaluating six different prompting strategies and comparing them with an industrial-grade OSS-Fuzz driver, revealing the potential and challenges of LLMs in this field.
* [WhiteFox: White-Box Compiler Fuzzing Empowered by Large Language Models](https://dl.acm.org/doi/10.1145/3689736) (OOPSLA 2024) 

  WhiteFox is the first white-box compiler fuzzer empowered by LLMs to test compiler optimizations, focusing on detecting deep logic bugs, particularly in DL compilers. It uses a dual-model framework for analysis and generation, leveraging source-code information to produce high-quality test programs that exercise complex optimizations more effectively than existing fuzzers.
* [Fuzzing JavaScript Interpreters with Coverage-Guided Reinforcement Learning for LLM-Based Mutation](https://dl.acm.org/doi/10.1145/3650212.3680389) (ISSTA 2024)

  This paper introduces a novel approach that combines coverage-guided reinforcement learning with large language models to generate mutations for fuzzing JavaScript interpreters. This method enhances the effectiveness of finding bugs by leveraging LLMs' natural language capabilities and reinforcement learning's ability to optimize for code coverage.
* [LLMIF: Augmented Large Language Model for Fuzzing IoT Devices](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a196/1WPcYnhN15u) (SP 2024)
  
  LLMIF is an IoT fuzzing algorithm that leverages an augmented large language model to extract protocol information and reason about device responses from protocol specifications. It aims to overcome limitations in IoT fuzzing, such as unknown message formats and lack of test case evaluations. 
* [Large Language Model guided Protocol Fuzzing](https://www.ndss-symposium.org/ndss-paper/large-language-model-guided-protocol-fuzzing/) (NDSS 2024)
  
  This paper introduces a method that utilizes large language models (LLMs) to enhance protocol fuzzing by addressing key challenges: dependence on initial seeds, unknown message structures, and unknown state spaces. The approach involves extracting machine-readable grammars, enriching initial seeds, and inferring state spaces to surpass coverage plateaus. Evaluations show significant improvements in state and code coverage and the discovery of previously unknown bugs in protocol implementations.
* [Fuzzing BusyBox: Leveraging LLM and Crash Reuse for Embedded Bug Unearthing](https://www.usenix.org/conference/usenixsecurity24/presentation/asmita) (USENIX Security 2024)
  
  This paper introduces techniques to enhance fuzz testing of BusyBox in embedded systems. It uses LLMs to generate initial seeds and employs crash reuse to find bugs efficiently. The study shows significant improvements in identifying vulnerabilities in BusyBox without extensive fuzzing, highlighting the potential of these methods for embedded firmware security.
* [Evaluating Large Language Models for Enhanced Fuzzing: An Analysis Framework for LLM-Driven Seed Generation](https://ieeexplore.ieee.org/document/10731701) (IEEE Access 2024)
  
  This paper presents a framework to assess the use of LLMs for generating effective seed inputs in fuzzing. It highlights the importance of LLM selection in seed effectiveness and demonstrates that LLM-generated seeds can rival or surpass traditional fuzzing campaigns in certain cases. The study also addresses challenges like input format limitations and context window constraints.
* [Large language models are edge-case generators: Crafting unusual programs for fuzzing deep learning libraries](https://dl.acm.org/doi/abs/10.1145/3597503.3623343) (ICSE 2024)
  
  The paper introduces FuzzGPT, which leverages in-context learning and fine-tuning to create unusual inputs, achieving higher coverage and discovering new bugs in PyTorch and TensorFlow compared to existing fuzzers.
* [Harnessing Large Language Models for Seed Generation in Greybox Fuzzing](https://arxiv.org/pdf/2411.18143) (Arxiv)
  
  This paper introduces SeedMind, a system that uses LLMs to enhance greybox fuzzing by generating test case generators rather than individual test cases. SeedMind employs an iterative process to refine seed generation, aiming to increase code coverage. It addresses challenges like input format limitations and context constraints, showing effectiveness in real-world applications, outperforming existing LLM-based solutions and, in some cases, human-generated seeds.
* [LiftFuzz: Validating Binary Lifters through Context-aware Fuzzing with GPT](https://dl.acm.org/doi/pdf/10.1145/3658644.3670276) (CCS 2024)
  
  LiftFuzz is a novel framework that employs context-aware fuzzing with GPT to validate binary lifters. It uses an assembly language model based on GPT to generate test cases that consider instruction interactions, creating diverse contexts for validation. LiftFuzz compiles these into binaries, translates them into IRs using binary lifters, and then recompiles and executes them alongside the original binaries to compare runtime information and detect inconsistencies. This approach significantly outperforms traditional methods, identifying more issues with fewer test cases and highlighting critical problems in binary lifters.
* [Large Language Model assisted Hybrid Fuzzing](https://arxiv.org/abs/2412.15931) (Arxiv)
  
  This paper introduces HyLLfuzz, a hybrid fuzzing approach that integrates greybox fuzzing with LLMs to overcome limitations of symbolic execution. HyLLfuzz uses LLMs to generate inputs that reach desired branches when greybox fuzzing hits a roadblock, achieving superior coverage compared to AFL, Intriguer, and Qsym, and is 4-19 times faster than existing concolic execution in hybrid fuzzing tools.
* [ProphetFuzz: Fully Automated Prediction and Fuzzing of High-Risk Option Combinations with Only Documentation via Large Language Model](https://dl.acm.org/doi/10.1145/3658644.3690231) (CCS 2024)
  
  ProphetFuzz is an LLM-based tool for fully automated prediction and fuzzing of high-risk option combinations in software programs, using only documentation. It predicts which combinations are more likely to contain vulnerabilities and conducts fuzz testing automatically. 
* [LLM-Enhanced Static Analysis for Precise Identification of Vulnerable OSS Versions](https://arxiv.org/abs/2408.07321) (Arxiv)
  
  introduces Vercation, a method that combines static analysis, LLMs, and semantic-level code clone detection to identify vulnerable versions in open-source C/C++ software. Vercation extracts vulnerability-related statements, refines them with LLMs, and detects semantic clones to pinpoint vulnerability-introducing commits. It achieved an F1 score of 92.4%, outperforming state-of-the-art methods and detecting 134 incorrect vulnerable OSS versions in NVD reports.
* [Enhancing vulnerability detection efficiency: An exploration of light-weight LLMs with hybrid code features](https://www.sciencedirect.com/science/article/pii/S2214212624002278) (JISA)
  
  This paper proposes VulACLLM, a framework that combines AST and CFG features with LLMs for vulnerability detection. It evaluates various LLMs, selects the most effective ones, and introduces a hybrid approach to improve detection efficiency. The paper also compares model compression techniques and proposes a Top-K Efficiency metric to balance performance and efficiency in vulnerability detection.
* [Large Language Models for Code Analysis: Do LLMs Really Do Their Job?](https://www.usenix.org/system/files/usenixsecurity24-fang.pdf) (USENIX Security 2024)
  
  This paper evaluates the effectiveness of LLMs in code analysis, especially with obfuscated code. The study finds that LLMs like GPT-3.5 and GPT-4 can automate code analysis with value, yet have limitations, particularly with complex obfuscation. They struggle with longer, complicated code and WebAssembly insertions, and smaller LLMs perform poorly. The paper suggests constructing obfuscated code datasets for fine-tuning LLMs and exploring memorization phenomena in LLMs. It concludes that while LLMs cannot replace experts, they can assist in initial code analysis and reverse engineering.
* [LLMs Cannot Reliably Identify and Reason About Security Vulnerabilities (Yet?): A Comprehensive Evaluation, Framework, and Benchmarks](https://ieeexplore.ieee.org/document/10646663) (SP 2024)
  
  This paper evaluates the capability of LLMs in detecting and reasoning about security vulnerabilities. The study introduces SecLLMHolmes, an automated framework, to assess LLM performance across various dimensions using 228 code scenarios. Findings show LLMs provide inconsistent responses, incorrect reasoning, and struggle with real-world scenarios, indicating they are not yet reliable for automated vulnerability detection.
## Decompile
* [DeGPT: Optimizing Decompiler Output with LLM](https://www.ndss-symposium.org/ndss-paper/degpt-optimizing-decompiler-output-with-llm/) (NDSS 2024)
  
  DeGPT optimizes decompiler output using LLMs, employing a three-role mechanism and MSSC to enhance readability without altering function semantics. It improves efficiency and depth of analysis, reducing cognitive load by 24.4% and significantly improving variable naming and comment addition.
* [Enhancing Reverse Engineering: Investigating and Benchmarking Large Language Models for Vulnerability Analysis in Decompiled Binaries](https://arxiv.org/pdf/2411.04981) (Arxiv)
  
  This paper evaluates the effectiveness of LLMs in identifying vulnerabilities in decompiled binaries. The study benchmarks different LLMs, using prompts to generate vulnerability assessments and CWE classifications. It finds that API-based models like GPT-4 achieve higher accuracy in vulnerability detection compared to other models. The paper also discusses the challenges of applying LLMs to vulnerability analysis in decompiled code.
* [ReSym: Harnessing LLMs to Recover Variable and Data Structure Symbols from Stripped Binaries](https://dl.acm.org/doi/10.1145/3658644.3670340) (CCS 2024)
  
  This paper presents ReSym, a system that uses LLMs and program analysis to recover variable symbols, including names and types, from stripped binaries. It tackles the challenge by dividing it into two sub-problems: local variable recovery and user-defined data structure recovery. ReSym fine-tunes two LLMs for these tasks and employs a Prolog-based algorithm to aggregate results, enhancing accuracy and overcoming token limitations. The system significantly outperforms state-of-the-art methods in recovering variable information and user-defined data structures.

## Program Repair
* [ThinkRepair:sel-Directed Automated Program Repair](https://dl.acm.org/doi/10.1145/3650212.3680359) (ISSTA 2024)
  
  This paper introduces ThinkRepair, an LLM-based automated program repair (APR) framework that leverages chain-of-thought reasoning and few-shot learning to enhance the understanding of function semantics for bug fixing. It has two phases: collection, which gathers pre-fixed knowledge, and fixing, which applies CoT-based prompting and few-shot learning to address bugs. ThinkRepair outperforms traditional LLM-based APRs, showing improved repair capabilities across various projects.
* [InferFix: End-to-End Program Repair with LLMs](https://dl.acm.org/doi/10.1145/3611643.3613892) (ESEC/FSE 2023)
  
  This paper presents an end-to-end program repair framework that utilizes large language models to automatically fix bugs in code. It employs a prompt engineering strategy to guide the LLM through the repair process, from understanding the error to generating and validating fixes. InferFix demonstrates high repair accuracy and efficiency, significantly outperforming traditional repair techniques and showing the potential of LLMs in automated program repair.
* [RepairAgent:An Autonomous, LLM-Based Agent for Program Repair](https://arxiv.org/abs/2403.17134) (Arxiv)
  
  This paper introduces RepairAgent, the first autonomous agent leveraging LLMs to address program repair challenges. It operates by dynamically updating prompts to guide the LLM through bug repair, invoking a set of tools to interact with the codebase, and using middleware for communication. RepairAgent successfully autonomously repaired 164 bugs, including 39 not fixed by prior techniques, at a cost of approximately 14 cents per bug, setting a new state of the art in program repair.
  