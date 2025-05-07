# Prompt-Engineering-4.1  
# EXP 4 Scenario-Based Report Development Utilizing Diverse Prompting Techniques  
## Lab Scenario: Smart Health Assistant System  



### Description:

#### Background  
You are part of a development team working on an AI-based Smart Health Assistant named **"MediGuide"** that assists elderly patients in managing chronic diseases like diabetes, hypertension, and arthritis. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

#### Objective  
Develop a scenario-based report that demonstrates how diverse prompting techniques (**zero-shot**, **few-shot**, **chain-of-thought**, **role-based**, and **multi-modal prompts**) can be used to optimize MediGuide’s responses in different use cases.

---

### Algorithm

1. **Identify Use Cases**: Define common scenarios where elderly users interact with MediGuide.  
2. **Select Prompting Techniques**: Choose appropriate prompting strategies based on the scenario.  
3. **Design Prompts**: Create examples using each prompting technique.  
4. **Evaluate Outputs**: Analyze responses for accuracy, empathy, and clarity.  
5. **Refine Prompts**: Optimize the prompts based on performance.  
6. **Document Findings**: Record how each prompting style impacts the response quality.

---
```
Name    : Sam Israel D
Reg. No : 212222230128
```
### Output

#### Scenario 1: Zero-shot Prompting  
- **Use Case**: User asks, “What are symptoms of high blood sugar?”  
- **Prompt**: `"List symptoms of high blood sugar."`  
- **Output**:  
  - MediGuide replies:  
    > "Common symptoms of high blood sugar include increased thirst, frequent urination, fatigue, blurred vision, and slow-healing wounds."

#### Scenario 2: Few-shot Prompting  
- **Use Case**: User seeks daily diabetic tips.  
- **Prompt**:
```Q: What is a good health tip for diabetes?
A: Stay hydrated and monitor your blood sugar regularly.

Q: Give me a daily diabetes tip.
A: Eat balanced meals with consistent carbohydrate intake.

Q: Share a useful diabetic health reminder.
A: 
```

- **Output**:  
- MediGuide replies:  
  > "Remember to check your feet daily for any sores or changes, as diabetes can affect circulation."

#### Scenario 3: Chain-of-Thought Prompting  
- **Use Case**: User asks, “Why should I take my hypertension medication even if I feel fine?”  
- **Prompt**:  
`"Let's think through this step by step: High blood pressure often has no symptoms..."`  
- **Output**:  
- MediGuide replies:  
  > "High blood pressure is known as the 'silent killer' because it may not cause noticeable symptoms. Even if you feel fine, untreated hypertension can lead to heart attacks, strokes, and kidney damage over time. That’s why it’s important to take your medication regularly."

#### Scenario 4: Role-based Prompting  
- **Use Case**: User feels anxious about managing arthritis pain.  
- **Prompt**:  
`"You are a compassionate digital health coach. Provide emotional support and a simple pain management tip for arthritis."`  
- **Output**:  
- MediGuide replies:  
  > "I understand how challenging arthritis can be. You're doing your best, and that matters. One tip that might help is applying a warm compress to sore joints—it can ease stiffness and improve flexibility."

#### Scenario 5: Multi-modal Prompting  
- **Use Case**: User uploads a photo of a medication label and asks for dosage clarification.  
- **Prompt**:  
*Includes image + question: "Can you tell me the dosage instructions on this label?"*  
- **Output**:  
- MediGuide replies after analyzing the label:  
  > "This medication should be taken once daily with food. Be sure to follow your doctor’s instructions and not exceed the recommended dose."

---

### Result

Using diverse prompting techniques significantly improves MediGuide's performance by enabling more relevant, empathetic, and accurate responses tailored to elderly users' health needs. Each technique addresses different challenges—ranging from reasoning and context-awareness to emotional intelligence and multi-modal input handling.
