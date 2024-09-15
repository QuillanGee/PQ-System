# PQ-System
**Question:** What is the pq system? And how can we use it to define a theorem and an axiom? How can you apply the PQ- system to our current coding standards? What is the history of the PQ-System? Because of its simplicity and use for formal systems, is their any research being done on the PQ-System to this day?

## Chatting with ChatGPT

### What is the PQ-System:
**(1) Definition:** The PQ-system is a formal system introduced by Douglas Hofstadter in his book Gödel, Escher, Bach: An Eternal Golden Braid to illustrate how formal systems work. It is a simple string manipulation system, which allows us to explore basic ideas of formal logic, theorems, and axioms.

**(2)Components of the PQ-System**
The PQ-system consists of three symbols:

- P, Q, and - (dash)
- The system works with strings that have the following general form:

    𝑥𝑃𝑦𝑄𝑧
  
- Where 𝑥, 𝑦, and 𝑧 are strings of dashes ("-").

**(3)Axiom of the PQ-system**
- The PQ-system has only one axiom, which is a starting point or a rule that defines what is initially considered true. The axiom schema is:

    xp-Q-x-p-

- In this schema, 𝑝 represents any number of dashes, and 𝑥 can represent any number of dashes as well. It allows us to create valid strings (theorems) within the system.

**(4)Rules of Inference**
- The PQ-system has only one inference rule. If you have a string of the form:

    𝑥𝑃𝑦𝑄𝑧
- And if you know that 𝑥, 𝑦, and 𝑧 are strings of dashes, then you can infer a new string by applying the rule of inference. The rule is:

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

### History of the PQ-System

The PQ-system itself doesn’t have a long historical background in the sense of being a long-established formal system in mathematics or computer science. Instead, it was created as a conceptual example by Douglas Hofstadter in his 1979 Pulitzer Prize-winning book, Gödel, Escher, Bach: An Eternal Golden Braid. The PQ-system was designed as a simplified and illustrative tool to introduce readers to the concepts of formal systems, axioms, inference rules, and theorems, which are central to the fields of mathematical logic and formal proof theory.

**Origins in Gödel, Escher, Bach**

The PQ-system was introduced as a playful, symbolic system in Hofstadter’s book to help explain the ideas that underpin formal logic and Gödel’s incompleteness theorems. Hofstadter was interested in exploring how complex systems can arise from simple rules, and the PQ-system was one of several examples he used to demonstrate this principle. In the book, Hofstadter compares the PQ-system to more complex formal systems, such as those in mathematics, logic, and computer science.

The purpose of the PQ-system was not to create a system with real-world applications but to provide an accessible model of formal systems that could be used to teach concepts like:

- Axioms: Basic statements assumed to be true without proof.
- Theorems: Statements that are derived from axioms using formal rules.
- Inference rules: The process of deriving new theorems from existing ones by applying strict logical transformations.
  
**Connection to Gödel's Incompleteness Theorems**

In Gödel, Escher, Bach, Hofstadter uses the PQ-system and other formal systems (like the MIU-system) to set the stage for discussing Kurt Gödel’s incompleteness theorems. Gödel’s theorems, published in 1931, showed that within any sufficiently powerful formal system (such as arithmetic), there are true statements that cannot be proven within the system. Hofstadter uses simple systems like the PQ-system to illustrate how formal rules work, laying the groundwork for readers to grasp the deeper implications of Gödel’s work.

The PQ-system is part of Hofstadter's broader exploration of how meaning, self-reference, and complexity emerge from formal systems, which he connects to music (Johann Sebastian Bach), visual art (Maurits Escher), and mathematical logic (Gödel).

**Summary of the PQ-System’s Purpose**

- Designed by Douglas Hofstadter: It was created as an educational example to explain formal systems in his 1979 book.
- Illustrates key concepts: The system shows how axioms, theorems, and inference rules interact, giving readers a basic understanding of formal logic and proof systems.
- Relates to Gödel’s theorems: Hofstadter uses it as a stepping stone to introduce readers to more complex ideas about logic, particularly Gödel’s incompleteness theorems.

While the PQ-system itself doesn’t have historical roots beyond Hofstadter's book, it serves as a valuable conceptual tool for understanding the structure and behavior of formal systems in mathematics, logic, and computer science. Its simplicity allows for a hands-on exploration of how seemingly arbitrary symbols and rules can form the basis for more complex logical reasoning.


### Current Research on the PQ-System

Because the PQ-system is an illustrative system rather than one with practical applications, there hasn't been significant academic or theoretical research directly focused on it. The system's simplicity means that it doesn’t offer the same potential for development or application as more robust formal systems. Formal systems like propositional logic, predicate logic, and automated theorem proving have much broader applications and thus receive more attention from researchers.

However, related fields continue to see active research:

**(1)Formal Systems and Proof Theory:**

Formal systems and their applications in proof theory and automated theorem proving are areas of active research. Systems such as Coq, Lean, and Isabelle are widely used for formal verification, mathematics, and logic research. These systems involve formal logic similar to the principles introduced through the PQ-system but are much more complex and powerful.
The PQ-system’s purpose of teaching formal systems might indirectly contribute to the growing interest in formal methods and formal verification, especially in the verification of software and hardware systems for correctness and reliability.

**(2)Theoretical Computer Science:**

Research on type theory, lambda calculus, and formal grammars still touches on the basic principles that the PQ-system represents. These areas involve creating formal systems and ensuring their consistency, completeness, and applicability, which are deeper versions of the same concepts introduced by the PQ-system.
While researchers aren’t studying the PQ-system specifically, the principles behind formal systems—like rule-based logic and inference—continue to shape work in areas like automata theory, formal languages, and computational logic.

**(3)Educational Research:**

There may be pedagogical studies that investigate how formal systems like the PQ-system can help students grasp foundational concepts in logic, computer science, and mathematics. Since the PQ-system is so effective at explaining the basic structure of formal systems, it could be used in introductory courses on logic, proof theory, or the theory of computation.

**Broader Context: Research on Formal Logic and Systems**

Although there isn’t ongoing research specifically on the PQ-system, the ideas behind it are foundational to many fields that are actively researched. For example:

- Formal Verification: As more critical systems (like aerospace, medical devices, or financial systems) rely on software, researchers are constantly looking for ways to verify the correctness of algorithms. This ties back to the concept of proving theorems (like in the PQ-system), but with complex formal systems used to model real-world problems.

- Artificial Intelligence: Some areas of AI, particularly knowledge representation and automated reasoning, deal with formal systems that derive conclusions from axioms using inference rules. These systems, while far more advanced than the PQ-system, operate on the same core principles.

- Proof Assistants and Automated Theorem Proving: Tools like Lean, Coq, and Agda allow mathematicians and computer scientists to formally verify proofs. These systems rely on axioms and inference rules, much like the PQ-system, though they are orders of magnitude more complex.

