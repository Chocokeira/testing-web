# Extra structured task (removed from Problem Set B · Secondary Upper)

Removed from `problem-set-b-data.js` (`window.SPECIMENS.secupper.structured`) on 2026-07-13 to keep the paper at three Section B tasks / 100 marks. The former Task 4 (Build & Evaluate a Classifier in Python) was renumbered to Task 3. Preserved here in full, including the marking guide, for possible reuse.

## Task · Emerging Theme: Design a Grounded, Fair AI Agent (20 marks)

**Tags:** AI Agent · System Design · Ethics & Safety

**Scenario.** **Emerging-technology theme: agentic & retrieval-augmented AI.** Design a reference-desk agent for a public library that answers patrons' questions. It may use a **Retriever** (searches the library's licensed encyclopedias), an **LLM**, and a **Calculator**.

**Parts**

a) Sketch the agent's loop (inputs → retrieve → reason/act with tools → output). Where is retrieval (RAG) used and why does it lower hallucination?

b) Give one evaluation metric for answer quality and how you would measure it.

c) Identify two risks (hallucinated citations, bias, privacy of student data) with a concrete safeguard for each.

d) State one limitation your design cannot fully solve.

## Marking guide

**Knowledge**

- Knows the agent loop, the role of retrieval in grounding, and that evaluation needs a defined metric.
- RAG conditions generation on retrieved trusted text, reducing fabrication.

**Skill**

- a) Coherent architecture with retrieval placed before generation and justified. (8 marks)
- b) A measurable metric, e.g. % of answers whose claims are supported by a retrieved source, checked on a sample. (4 marks)
- c) Two real risks each with a matched safeguard (cite-and-verify; human review; anonymise data). (6 marks)

**Disposition**

- d) Honest limitation, e.g. retrieval can't fix gaps or errors in the source documents themselves. (2 marks)
- A mini research-style appraisal: method, evaluation, limitations: the bridge to NOAI/IOAI.

## Learning outcomes

- a) US.P4.2, US.P4.3, US.P4.4, US.P4.5, US.P5.3
- b) US.P4.2, US.P4.3, US.P4.4, US.P4.5
- c) US.P4.2, US.P4.3, US.P4.4, US.P4.5, US.P5.3, US.P5.4, US.P5.5
- d) US.P4.2, US.P4.3, US.P4.4, US.P4.5

## Original JSON (verbatim, for pasting back into the data file if needed)

```json
{"title":"Task 3 · Emerging Theme - Design a Grounded, Fair AI Agent","marks":20,"tags":[["AI Agent","t-agent"],["System Design","t-design"],["Ethics & Safety","t-ethics"]],"scenario":"<b>Emerging-technology theme: agentic &amp; retrieval-augmented AI.</b> Design a reference-desk agent for a public library that answers patrons’ questions. It may use a <b>Retriever</b> (searches the library’s licensed encyclopedias), an <b>LLM</b>, and a <b>Calculator</b>.","parts":[["a)","Sketch the agent’s loop (inputs → retrieve → reason/act with tools → output). Where is retrieval (RAG) used and why does it lower hallucination?"],["b)","Give one evaluation metric for answer quality and how you would measure it."],["c)","Identify two risks (hallucinated citations, bias, privacy of student data) with a concrete safeguard for each."],["d)","State one limitation your design cannot fully solve."]],"marking":{"k":["Knows the agent loop, the role of retrieval in grounding, and that evaluation needs a defined metric.","RAG conditions generation on retrieved trusted text, reducing fabrication."],"s":["a) Coherent architecture with retrieval placed before generation and justified. (8 marks)","b) A measurable metric, e.g. % of answers whose claims are supported by a retrieved source, checked on a sample. (4 marks)","c) Two real risks each with a matched safeguard (cite-and-verify; human review; anonymise data). (6 marks)"],"d":["d) Honest limitation, e.g. retrieval can’t fix gaps or errors in the source documents themselves. (2 marks)","A mini research-style appraisal: method, evaluation, limitations - the bridge to NOAI/IOAI."]},"partLo":[["US.P4.2","US.P4.3","US.P4.4","US.P4.5","US.P5.3"],["US.P4.2","US.P4.3","US.P4.4","US.P4.5"],["US.P4.2","US.P4.3","US.P4.4","US.P4.5","US.P5.3","US.P5.4","US.P5.5"],["US.P4.2","US.P4.3","US.P4.4","US.P4.5"]]}
```
