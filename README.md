# r a g - l l m

The following is a prototype connected system of
- Retrieval Augmented Generation (RAG) and
- Large Language Model (Llm).

## It consists of

### 1. Editor + database to enter new text / maintain texts
  <img width="1511" height="849" alt="image" src="https://github.com/user-attachments/assets/cf66a0b3-f323-4077-a365-74e0006e8ab0" />

---

### 2. Vectorizer to generate embeddings for existing documents (.pdf, docx etc.)
<img width="1296" height="455" alt="image" src="https://github.com/user-attachments/assets/d9e4b70c-717e-40fb-8450-cb5bde4283f0" />

---

### 3. Semantic search prompt on the document corpus, to find relevant documents
<img width="978" height="403" alt="image" src="https://github.com/user-attachments/assets/30b9648a-2e1d-45af-a3f6-136f61ef96ae" />

---

### 4. Connection to an LLM, i.e. hand found documents plus a question to the LLM
HW | parsing (sec) | thinking (s) | output (s)
-|-|-|-
Laptop AMD Ryzen5 | 53 | 76 | 74
Laptop i9 + RTX3080 | 4 | 7 | 12

<img width="1833" height="1148" alt="image" src="https://github.com/user-attachments/assets/b1680d7c-6f89-44f0-a935-2484fc87bc60" />
