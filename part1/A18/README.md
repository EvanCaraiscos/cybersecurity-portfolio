# A18 - AI Hallucination Cases

## What is an AI Hallucination?
When a generative AI model produces output that is factually 
incorrect, fabricated, or misleading. Often stated with 
high confidence. This is a known limitation of large language 
models (LLMs).

## Test Environment
- Model tested: ChatGPT (GPT-4)
- Date conducted: 31/03/2026
- Hallucination types: Factual/historical fabrication, 
  Mathematical reasoning error

## Case 1 — UWA Fire (Historical Fabrication)
- **Prompt:** `prompt1.txt`
- **Outcome:** Model fabricated a detailed account of a fire 
  at UWA's Law School on 30 March 2003, including cause, 
  impact, and aftermath
- **Verification:** No evidence of this event found via 
  Google search or UWA records
- **Screenshot:** `Picture1.png`

## Case 2 — Prime Number Error (Mathematical Reasoning)
- **Prompt:** `prompt2.txt`
- **Outcome:** Model incorrectly stated 3821 is not prime, 
  claiming 43 × 89 = 3821, before correcting after a user prompt
- **Verification:** 43 × 89 = 3827, not 3821. 3821 is 
  actually a prime number
- **Screenshot:** `Picture2.png`

## Analysis
These two cases demonstrate different hallucination types. 
Case 1 shows how models fabricate specific historical details 
when local/niche events are underrepresented in training data. 
Case 2 shows how LLMs can reason incorrectly on arithmetic 
without tool assistance. Both were stated with high confidence, 
highlighting the importance of verifying AI outputs.

## References
Evidence1.png
Evidence2.png
