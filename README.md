**These are the principles I have developed from my personal experience after 1–2 years of using AI in software development.**

1. Define the core idea and purpose of the software.
2. Identify the features and functionalities that make up the software.
3. Define the software's architecture, algorithms, and security requirements.
4. Establish an appropriate project structure that aligns with the software's needs.
5. Analyze and reason about the feasibility of the idea before entering the testing phase. (This helps avoid situations where the project is nearly finished, only for you to discover a critical flaw in the concept that forces you to rebuild the system from scratch.)
6. Ensure that the quality of test cases is as close as possible to real-world production testing.
7. Ensure that the plugins and extensions used by the AI agent are sufficient for the project's needs, but avoid unnecessary additions. (Excessive tools can unnecessarily inflate the AI's input context and reduce efficiency.)
8. If a bug occurs, make sure detailed debugging information is available so the root cause can be clearly identified before asking the AI to analyze and fix it. (I have encountered situations where insufficient debugging information caused the AI to become uncertain and rely on assumptions about what was actually happening.)
9. Always maintain a temporary Git commit or a previous backup. (This ensures that you can recover your code if the AI accidentally introduces breaking changes or violates rules and constraints that were previously established.)
