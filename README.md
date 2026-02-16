# CSP — Get Structured Answers, Not "It Depends"

**Conceptual Skeleton Protocol (CSP)**  
A framework for making AI answers clear, structured, and debuggable by separating meanings before reasoning.

---

## 🎯 Who Is This For

Use CSP if you are:

- Building RAG systems
- Fine-tuning LLMs
- Writing system prompts
- Debugging AI reasoning
- Frustrated with vague or inconsistent AI answers

---

## ❗ The Problems CSP Solves

### ✅ Stop vague "it depends" answers
**Problem:** AI mixes meanings and gives unclear conclusions.  
**Solution:** CSP separates meanings first → clearer decisions.

### ✅ RAG that retrieves the right concept
**Problem:** Keyword search retrieves irrelevant info.  
**Solution:** CSP indexes concepts, not words.

### ✅ Consistent fine-tuning datasets
**Problem:** Training data mixes meanings.  
**Solution:** CSP labels components separately.

### ✅ Debug reasoning, not just outputs
**Problem:** You see wrong answers but don't know why.  
**Solution:** CSP tracks where meaning got mixed.

### ✅ Content that doesn't contradict itself
**Problem:** Same word used in different senses.  
**Solution:** CSP enforces one meaning at a time.

---

## 🧠 How CSP Works

CSP forces analysis in 3 layers:

### 1. Meaning Separation
One term → one meaning at a time.

### 2. Component Analysis
Split into:
- **F — Foundation** (definitions, assumptions)
- **E — Experience** (data, observations)
- **C — Causality** (mechanisms, logic)

### 3. Decision Framework
For practical questions → value mapping + clear boundaries.

---

## 🧪 Example

**Question:**  
*"Is remote work good?"*

**Without CSP:**
> It depends on context…

**With CSP:**
- **F:** productivity metrics definition
- **E:** employee satisfaction data
- **C:** impact on retention
- **Decision:** trade-off between output stability and flexibility.

Clear structure → clear reasoning.

---

## ⚙️ How To Use CSP

### Option 1 — System Prompt
Paste CSP into your system message and ask questions normally.

### Option 2 — RAG Integration
1. Split documents into F / E / C components
2. Index separately
3. Retrieve by component type

### Option 3 — Dataset Labeling
Annotate training data with CSP components to prevent concept mixing.

---

## 🧭 When CSP Helps Most

Use CSP if your AI:

- Gives vague answers
- Retrieves wrong meaning in RAG
- Produces inconsistent datasets
- Is hard to debug
- Mixes concepts in long responses

---

## ⚠️ Limitations

- Requires careful prompt design
- Not ideal for creative writing
- Needs testing per domain

---

## 🤝 Contributing

Ideas, experiments, benchmarks, and integrations are welcome.  
Open an issue or discussion.

---

## 📄 License

**CC BY-NC-ND 4.0**

This protocol may be used, referenced, and integrated into non-commercial research, evaluation, and experimental AI systems, provided it is not modified or redistributed as a derivative work.

Commercial deployment, resale, or integration into proprietary AI products, agents, or training datasets requires a Commercial License.
