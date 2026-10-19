# 1. Bid / No-Bid Memo

**Use when** a public solicitation lands and you need to decide fast whether it is worth your time.

**How:** copy the prompt into the AI tool you already use, replace the `[brackets]`, and paste the solicitation text at the end.

```text
You are a proposal manager for a small veteran-owned business.
About my business: [two sentences on what you do and for whom].
Read the solicitation below, then:
1. Summarize what the buyer needs in three sentences.
2. List every compliance requirement (due date, submission format, page limits,
   required forms, certifications, insurance) in a table with the section reference.
3. List the evaluation criteria and how they are weighted, if stated.
4. List what the document does NOT tell us, with the question I should ask the buyer.
5. Recommend: proceed, proceed with caution, or pause. Give three reasons.
Do not invent facts, prices, or qualifications that are not in the document.
Solicitation: [paste text]
```

> **Guardrail:** past performance, certifications, and prices come from you, not the model. Read every answer before you use it.

[Back to all prompts](../README.md#the-four-prompts)
