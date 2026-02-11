# Explaining the following Prompt Engineering types with examples - Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting.
    
### NAME: Rakshitha P
### REGISTER NUMBER : 212223220083

# Aim: 
To write the prompts for these following prompt types and evaluate that using any one method 
1. Straightforward Prompts,
2. Tabular Format Prompting
3.Preceding Question Prompting and
4. Missing Word Prompting

---

## Types of Prompt Engineering

### 1. Straightforward Prompts

**Definition:**
Direct and simple instructions given to the AI without extra context. Best for deterministic, repetitive tasks where the output format is fixed.

**Key Features:**

* Clear and direct phrasing.
* Minimal ambiguity.
* Works well for factual or standard replies.

**Use Cases:**

* Order tracking responses.
* Providing product availability.
* Greeting/closing messages.

**Example:**

```plaintext
Prompt: "Define Artificial Intelligence in one sentence."

**Conversation:**

User: "Define Artificial Intelligence in one sentence."

Chatbot: "Artificial Intelligence is the simulation of human intelligence in machines that are programmed to think and learn."
```

**Conversation:**

* Prompt: "List three advantages of online education."*
* Chatbot: *"Response:

Flexible learning schedule

Access to global resources

Cost-effective education."*

**Advantages:** Fast and reliable for structured queries.
**Limitations:** Lacks flexibility, may fail for vague queries.

---

### 2. Tabular Format Prompting

**Definition:**
Organizes information into a **structured table** for consistent responses.

**Key Features:**

* Easy mapping between **Issue → Solution → Tone**.
* Ensures consistency.
* Best when multiple query categories exist.

**Use Cases:**

* Troubleshooting guides.
* Policy summaries (refunds, returns, replacements).
* Tone-based responses.

**Conversation:**

* Customer: *"My package hasn’t arrived yet."*
* Chatbot: *"I understand your concern. Your order is still in transit and is expected to arrive by September 14, 2025. Tracking number: TR123456."*

**Advantages:** Easy scalability & consistency.
**Limitations:** May feel robotic if overused.

---

### 3. Missing Word Prompting (Cloze Prompting)

**Definition:**
AI fills in **blanks in a template**, ensuring structured responses.

**Key Features:**

* Template-driven replies.
* Guarantees inclusion of required fields (name, ID, date).
* Reduces formatting errors.

**Use Cases:**

* Personalized responses.
* Order updates with placeholders.
* FAQs with uniform style.

**Example Prompt:**

```plaintext
"Fill in the blanks in this template:  
Hello [name], your order [order_id] is currently [status]. Expected delivery: [date]."
```

**Conversation:**

* Customer: *"Hi, I’m Arjun. My order 5678 hasn’t been delivered yet."*
* Chatbot: *"Hello Arjun, your order 5678 is currently delayed in transit. Expected delivery: September 16, 2025."*

**Advantages:** Highly structured & accurate.
**Limitations:** Rigid, may not handle free-flow conversations well.

---

### 4. Preceding Question Prompting

**Definition:**
The AI **first asks clarifying questions** when the query lacks details.

**Key Features:**

* Adds a confirmation step.
* Improves accuracy & trust.
* Reduces wrong replies.

**Use Cases:**

* Refund requests without order ID.
* Troubleshooting without device details.
* Subscription/account issues.

**Example:**

```plaintext
Prompt: "If customer’s query is missing details (like order ID), ask a clarifying question first."
```

**Conversation:**

* Customer: *"I need a refund."*
* Chatbot: *"I can help with that! Could you please share your order number so I can check the refund details?"*

**Advantages:** Prevents errors, builds trust.
**Limitations:** Adds extra steps (slightly longer conversation).

---

### 5. Few-Shot Prompting

**Definition:**
AI is provided with a **few examples (input → output pairs)** to learn a style or reasoning pattern.

**Key Features:**

* Learns through examples.
* Handles varied queries consistently.
* Best when strict rules don’t exist.

**Use Cases:**

* Technical troubleshooting.
* Domain-specific FAQs.
* Customer query handling with nuance.

**Example Prompt:**

```plaintext

Here are some examples:

Customer: "My laptop is overheating."
Chatbot: "Please ensure the laptop is placed on a flat surface and the ventilation area is not blocked. You may also try cleaning the cooling vents."

Customer: "My Wi-Fi keeps disconnecting."
Chatbot: "Try restarting your router and reconnecting to the network. If the issue continues, check if other devices are facing the same problem."

Now respond to:
Customer: "My Bluetooth is not connecting."

```

**Expected Output:**

* Chatbot: *"It looks like the app might have a bug. Please try clearing the cache or reinstalling the app. If the problem continues, let me know and I’ll help further."*

**Advantages:** Flexible & adaptive.
**Limitations:** Needs well-chosen examples; too many can confuse the AI.

---

## 🧩 Prompt Design Guidelines

Designing effective prompts is essential for achieving reliable and high-quality AI responses. The following guidelines help ensure clarity, accuracy, and adaptability across different use cases.

### 1. Define the Objective Clearly
Each prompt should have a clear goal, such as requesting information, generating structured output, or initiating reasoning. A well-defined objective prevents irrelevant responses.

### 2. Choose the Appropriate Prompt Type
Select the prompt style based on the task:
- Use **straightforward prompts** for factual or fixed responses.
- Apply **tabular prompts** when structured comparison is required.
- Use **preceding questions** for incomplete or unclear inputs.
- Choose **missing word prompts** for assessments and validation.

### 3. Maintain Consistent Structure
Consistency in formatting helps the AI produce predictable outputs. Templates, tables, and fixed phrasing improve reliability, especially in repetitive tasks.

### 4. Minimize Ambiguity
Avoid vague terms and unclear instructions. Precise language ensures the AI correctly interprets user intent and reduces the chance of incorrect responses.

### 5. Anticipate User Variations
Design prompts that can handle different user inputs, including missing information, spelling errors, or partial queries.

### 6. Validate and Refine Prompts
Test prompts with multiple scenarios and refine them based on AI behavior. Iterative improvement leads to better performance and robustness.

### 7. Balance Structure and Flexibility
While structure is important, prompts should also allow flexibility for natural conversation when required, especially in interactive applications.


---
## Conclusion

Implementing diverse prompt engineering techniques empowers chatbots to deliver accurate, context-aware, and user-friendly interactions. Straightforward prompts ensure fast, reliable responses for routine queries, while tabular format prompts provide consistency and structure across multiple scenarios. Missing word (cloze) prompts enable precise personalization, and preceding question prompts enhance clarity by addressing incomplete inputs. Each approach has unique advantages, and strategically combining them maximizes efficiency, accuracy, and customer satisfaction. Thoughtful prompt design not only improves response quality but also fosters trust, scalability, and adaptability, positioning chatbots as effective, reliable, and intelligent tools in modern customer service ecosystems.

## Result

By applying **Straightforward, Tabular, Missing Word, Preceding Question, and Few-Shot Prompting**, customer service chatbots can:

1) Deliver accurate answers.
2) Maintain a natural conversational flow.
3) Improve customer trust and satisfaction.

Each method has its **strengths and trade-offs**, and the right combination depends on the **type of query** and **business goals**.

---


