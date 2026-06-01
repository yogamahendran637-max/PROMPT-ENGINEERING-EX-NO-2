EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
1. Zero-Shot Prompting

Prompt:
Summarize the following article about blockchain technology in simple terms for undergraduate students.

ChatGPT Output:
Blockchain is a digital system that records transactions across many computers so that the data cannot be easily changed. Each record is stored in blocks connected together using cryptography. This technology is best known for supporting cryptocurrencies like Bitcoin, but it is also used in supply chains, healthcare, and digital identity systems. Blockchain improves transparency and security but still faces issues such as high energy use and slow scalability.

Gemini Output:
Blockchain is a distributed ledger technology where transactions are stored in blocks connected in a chain. It allows secure and transparent data sharing without a central authority. It powers cryptocurrencies and can also be used in industries like healthcare, finance, and logistics. Despite its advantages, challenges such as regulation and energy consumption remain.

Claude Output:
Blockchain is a decentralized record-keeping system that stores data in linked blocks across many computers. Because each block is connected with cryptographic hashes, altering data becomes extremely difficult. The technology enables applications such as cryptocurrencies and smart contracts but faces limitations including scalability and energy usage.

2. Few-Shot Prompting

Prompt:
Example:
Text: Artificial Intelligence helps machines learn patterns from data.
Summary: AI enables machines to learn from data.

Text: Blockchain is a decentralized ledger system used to record transactions securely across many computers.

Provide a short summary like the example.

ChatGPT Output:
Blockchain is a decentralized system that securely records transactions across multiple computers without a central authority.

Gemini Output:
Blockchain is a distributed ledger that securely stores transaction data across a network and removes the need for intermediaries.

Claude Output:
Blockchain is a secure decentralized ledger that records transactions in linked blocks across a network.

3. Chain-of-Thought Prompting

Prompt:
Read the article.
Step 1: Identify the key concepts.
Step 2: Identify the applications.
Step 3: Identify the challenges.
Step 4: Create a final summary for students.

ChatGPT Output:
Key Concepts: decentralized ledger, cryptographic blocks, transparency
Applications: cryptocurrency, healthcare, supply chain, digital identity
Challenges: scalability, energy consumption, regulation

Final Summary:
Blockchain is a decentralized digital ledger that stores transaction data in secure blocks linked with cryptography. It removes the need for central authorities and increases transparency. The technology powers cryptocurrencies and can also improve industries such as supply chains and healthcare. However, blockchain still faces challenges like energy consumption and scalability.

Gemini Output:
Key Concepts: distributed ledger, block structure, security
Applications: cryptocurrency, smart contracts, logistics tracking
Challenges: scalability and regulation

Final Summary:
Blockchain is a distributed ledger technology that securely records transactions in linked blocks across a network. It is widely used for cryptocurrencies and smart contracts but faces technical and regulatory challenges.

Claude Output:
Key Concepts: decentralized network, immutable records
Applications: digital currency, identity verification, supply chain
Challenges: performance limits and energy cost

Final Summary:
Blockchain is a decentralized system that stores data in cryptographically connected blocks across many computers. It enables transparent and secure transactions but must overcome performance and energy issues.

4. Role-Based Prompting

Prompt:
You are a university professor explaining blockchain technology to first-year undergraduate students. Summarize the article in simple academic language.

ChatGPT Output:
Blockchain is a distributed digital ledger that records transactions in blocks linked together using cryptography. Because the ledger is shared across many computers, it is difficult to alter records once they are stored. This technology is widely used in cryptocurrencies but also has applications in areas such as healthcare, supply chain management, and digital identity systems.

Gemini Output:
Think of blockchain as a shared digital notebook where every transaction is recorded permanently. Each page (block) is connected to the previous one using encryption. This system improves transparency and security while removing the need for central authorities.

Claude Output:
Blockchain can be understood as a decentralized database where information is stored in blocks that form a secure chain. Because many computers maintain the ledger, it becomes extremely difficult to change past data. This makes blockchain useful for secure transactions and digital contracts.


SUMMARY TABLE:
| Platform | Accuracy | Coherence | Simplicity | Speed | User Experience |
| -------- | -------- | --------- | ---------- | ----- | --------------- |
| ChatGPT  | 5        | 5         | 4          | 5     | 5               |
| Gemini   | 4        | 4         | 5          | 5     | 4               |
| Claude   | 5        | 4         | 4          | 4     | 4               |

RESULT:
Thus, the prompt input in different AI platforms and compare them is completed successfully.
