# PQ-System
**Question:** What is the pq system? And how can we use it to define a theorem and an axiom? How can you apply the PQ- system to our current coding standards?

## Chatting with ChatGPT

### What is the PQ-System:
**Definition:** The PQ-system is a formal system introduced by Douglas Hofstadter in his book Gödel, Escher, Bach: An Eternal Golden Braid to illustrate how formal systems work. It is a simple string manipulation system, which allows us to explore basic ideas of formal logic, theorems, and axioms.

**Components of the PQ-System**
The PQ-system consists of three symbols:

P, Q, and - (dash).
The system works with strings that have the following general form:

𝑥𝑃𝑦𝑄𝑧
Where 𝑥, 𝑦, and 𝑧 are strings of dashes ("-").

**Axiom of the PQ-system**
The PQ-system has only one axiom, which is a starting point or a rule that defines what is initially considered true. The axiom schema is:

xp-Q-x-p-

In this schema, 𝑝 represents any number of dashes, and 𝑥 can represent any number of dashes as well. It allows us to create valid strings (theorems) within the system.

**Rules of Inference**
The PQ-system has only one inference rule. If you have a string of the form:

𝑥𝑃𝑦𝑄𝑧
And if you know that 
𝑥, 𝑦, and 𝑧 are strings of dashes, then you can infer a new string by applying the rule of inference. The rule is:
/text{xp-Q-x}, /text{ then replace one or more p characters and form the pq one}


### Examples of how PQ-Systems Parallel Coding Standards
The PQ-system shows us that formal systems consist of simple rules that can lead to complex and valid outcomes. We can see this in syntax and coding guidelines throughout all programming languages.

In coding, you could think of a simple analogy to the PQ-system when dealing with loops or recursion. For example:
- A base case in recursion could be akin to an axiom in the PQ-system.
- A recursive step could represent an inference rule, where each recursive call transforms the problem into a simpler version.
- The solution to the recursive problem is analogous to deriving a theorem in the PQ-system.

For instance, in functional programming (Haskell, Python, etc.), you might define a recursive function to calculate the factorial:

def factorial(n):
    if n == 0:
        return 1  # Base case (Axiom)
    else:
        return n * factorial(n - 1)  # Recursive step (Inference)
        
This code adheres to a set of rules (syntax), and through valid transformations (recursive calls), it produces a result. The base case ensures the recursion halts, just like a valid axiom in a formal system ensures that derivations have a starting point.

