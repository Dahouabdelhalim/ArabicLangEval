# Arabic Semantics Dataset

The **Arabic Semantics Dataset** evaluates LLMs on core **semantic understanding** in Modern Standard Arabic.  
It focuses on two tasks:

1. **Synonym Substitution**  
2. **Word Sense Disambiguation (WSD)**

These tasks assess the model’s ability to understand context, lexical meaning, and nuanced semantic distinctions.

---

## 1. Synonym Substitution

### Task Definition
Given an **Arabic sentence** and a **target word (W)**, the model must generate a **synonym of W that fits the same context, tone, and stylistic level**.

### Example

**Input:**
- **Sentence:** "كان الجوُّ جميلاً في الصباح."
- **Target word:** `جميل`

**Expected Output:**
- `حسن`  
(Other acceptable synonyms: `بهيّ`, `لطيف`)

---

## 2. Word Sense Disambiguation (WSD)

### Task Definition
Given an **Arabic sentence** and a **target word (W)**, the model must output the **correct meaning** of W **from the list of possible senses** provided.

### Example

**Input:**
- **Sentence:** "اقترب من عين الماء ليشرب."
- **Target word:** `عين`
- **Possible senses:**
  1. عضو البصر  
  2. نبع ماء  
  3. جاسوس  
  4. جزء من الصحراء

**Expected Output:**
- `نبع ماء`

## 3. Antonym Substitution
