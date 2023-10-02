# Sharing the first iteration of our VEBAO.
# VEBAO
# Usage: Make sure to have Wolfram, ScholarAI and either BrowserOP or WebPilot as your plugins. Load into GPT-4 informing it that this is a challege template. Then raise the subjet matter you want to challenge GPT-4 to consider for the challenge you can ask GPT-4 to present specialized areas within the subject matter for user selection and further investigation. Make a selection and ask GPT-4 to add it to the VEBAO

Verbalized Execution Blueprint for AI Operations
Challenge [Number]:

Name: [Descriptive title for the challenge]

Category: [Type of task or domain the challenge falls under]

Task: [Detailed description of the task the AI is expected to perform]. The AI's response will be evaluated based on its relevance to this task (Task Relevance Score - TRS, score range: 0-1).

Dependencies: [Any prerequisites or capabilities the AI needs to complete the task]. The AI's ability to utilize and fulfill these dependencies will be scored (Dependency Fulfillment Score - DFS, score range: 0-1).

Ground Truth:
Raw Text of the Answer: [The expected format of the AI's response]
Exact Strings Required in the Final Answer: [Specific content that must be present in the AI's response]. The alignment of the AI's response with this ground truth will be measured (Ground Truth Alignment Score - GTAS, score range: 0-1).
Exact Strings That Should Not Be in the Final Answer: [Information that should be excluded from the AI's response].
Files Used for Retrieval: [Any external sources or references the AI might use].

Mock Response:
Function to Mock the Agent's Response: [Specified function name that represents the AI's action]
Task to Provide for the Mock Function: [A brief description of the function's objective].
Additional Information:

Difficulty: [Perceived challenge level of the task]
Description: [A brief overview of the challenge's purpose and goals]. Adherence to this information will be scored (Additional Information Adherence Score - AIAS, score range: 0-1).
Side Effects: [Potential consequences if the AI fails to complete the challenge correctly].

Scoring System:
Bias Detection Score (BDS): Measures the AI's ability to avoid biases, discriminations, or any other specified undesired behavior (score range: 0-1).
Overall Benchmark Score (OBS): Calculated as the weighted average of TRS, GTAS, DFS, AIAS and BDS. Formula: OBS = (TRS + GTAS + DFS + AIAS + BDS ) / 5.

Relevant Goals:
[Specific goal 1]
[Specific goal 2]
…

Instructions:
[Step-by-step instruction 1]
[Step-by-step instruction 2]
…

Constraints:
[Specific constraint or limitation 1]
[Specific constraint or limitation 2]
…