# dismathportfolio-delioparedes
dismathportfolio-josedelioparedes created by GitHub Classroom

#Week 1:
This week the class was introduced to **DISMATH** (Discrete Mathematics)
- The Syllabus for DISMATH was explained
- I have learned that DISMATH integrates heavily on logic
- I have learned about the propositional logic which is a statement which can be answered by True (T) or False (F)
- I also learned about the logical connectives which are used to connect two or more propositional logic
## The basic logical connectives are: 

| Logical Operator                     |Also called as      | Logical Symbol   | Logical Expression              |
| -------------------------------------|:------------------:|:----------------:|--------------------------------:|
|            Negation                  |NOT                 |   ¬              |          ¬p                     |
|          Conjunction                 |AND                 |   ∧              |       p ∧ q                     |
|           Disjunction                |OR                  | ∨                |         p ∨ q                   | 
|      Exclusive Disjunction           |XOR                 | ⊕               |  p ⊕ q ≡ (¬p ∧ q)  ∨  (p ∧ ¬q)  |
|           Conditional                |If-then, etc.       |   →              |        p → q ≡ ¬p ∨ q           |
|          Biconditional               |If and only if, etc.|    ↔             |    p ↔ q ≡ (p → q) ∧ (q → p)    |

- We also learned on how to solve the value of a given statement (with two or more logical connectives) using the **Truth Tables**.
- In a truth table, all possible interpretations are listed and the value is then computed by using the logical expressions of the operators used.

### Implication
- I have learned that the logical operator conditional "→" can be manipulated. 
- These are: 

  Conditinal Operator |  Expression 
:-------------------:|:------------:
Inverse | ¬p → ¬q 
Converse | q → p 
Contrapositive | ¬q → ¬p

In which the **Contrapositive is equal to the Conditional** and the **Inverse is equal to the Converse**

#Week 2

This week we discussed about Propositional Equivalances 
- We also discussed about the operator precedence
- These are (in order):
|Operator Precedence|
|---|
|Negation|
|Conjuction|
|Disjunction|
|Implication|
|Biconditional|
- This means that the negation should be applied first before proceeding with conjunctions and so on.

We also discussed three new terminologies for describing a propositional statement
- **Tautology** is for the statement which always be **__true__** on any interpretations
- **Contradiction** is for the statement which always be **__false__** on any interpretations
- **Contigency** is for the statement which can be **__true__** or **__false__** 

Logical equivalances provides a new way of proving a propositional formula (without using the truth table)
The logical equivalances are: 

| Equivalence | Name |
| :---------: | :--: |
| p ∧ **T** ≡ p<br/> p ∨ **F** ≡ p | Identity Laws |
| p ∨ **T** ≡ **T**<br/> p ∧ **F** ≡ **F** | Domination Laws |
| p ∨ p ≡ p<br/> p ∧ p ≡ p | Idempotent Laws |
| ¬(¬p) ≡ p | Double Negation Law |
| p ∨ q ≡ q ∨ p<br/> p ∧ q ≡ q ∧ p | Commutative Laws |
| (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)<br/> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)| Associative Laws |
| p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)<br/> p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)| Distributive Laws |
| ¬(p ∧ q) ≡ ¬p ∨ ¬q<br/> ¬(p ∨ q) ≡ ¬p ∧ ¬q | De Morgan's Law |
| p ∨ (p ∧ q) ≡ p<br/> p ∧ (p ∨ q) ≡ p | Absorption Laws |
| p ∨ ¬p ≡ **T**<br/> p ∧ ¬p ≡ **F** | Negation Laws |
| p → q ≡ ¬p ∨ q | Implication Equivalence |

#Week 3
This week the class focused on:
- practicing the logical connectives
- to be more familiarized with the logical connective **biconditional**
- An introduction to **First-Order Logic** was made

**First Order Logic**
- a predicate can only refer to a single subject. 

#Week 4
This week the class focused on:
- the concept of instantation or the concept of the quantifiers

There are two types of **Quantifiers**:

**1. Existential Quantifier ('Ǝ') **
- which can be translated to "there exists"
- to prove existence, state an example 
Ǝx.P(x)
- is true if atleast one element in the domain such that P(x) is true

**2. Universal Quantifier ('Ɐ') **
- which can be translated to "for all"
- to prove universality, there must be a counter example or all iterations must be True or False
Ɐx.P(x) 
- is true if all the elememnts in the domain such that P(x) is true

A main part of the lecture was focused on translating English senteces into Quantifier formulas

#Week 5
This week the class focused on:
- The Rules of Inference, which is like the Logical Equivalance.

**Rules of Inference**
- inference rule or transformation rule is a logical form consisting of a function which takes premises, analyzes their syntax, and returns a conclusion
Shown below is the table for the various rules of inferences:

 | Rule of Inference | Logical Connectives |  Name  |
 | :-------: | :--------------: | :---------: |
 | p<br/>p→q<br/>∴q |  (p ∧ (p → q)) → q  | Modus Ponens  |
 | ¬q<br/>p → q<br/>∴ ¬p  |  (¬q ∧ (p → q)) → ¬p |  Modus Tollens  |
 | p → q<br/>q → r<br/>∴ p → r  | ((p → q) ∧ (q → r)) → (p → r) |  Hypothetical Syllogism  |
 | p ∨ q<br/>¬p<br/>∴ q  | ((p ∨ q) ∧ ¬p) → q   |  Disjunctive Syllogism |
 | p<br/>∴ p ∨ q  |  p → p ∨ q  |  Addition  |
 | p ∧ q<br/>∴ p  |  (p ∧ q) → p  | Simplification  |
 |  p<br/>q<br/>∴ p ∧ q |  ((p) ∧ (q)) → (p ∧ q)  |  Conjunction  |
 | p ∨ q<br/>¬p ∨ r<br/>∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r | Resolution  |
 
Each line on the column of Rule of Inference represents the gradual finding of the conclusion of a given function and formula

- All the different types of proofs
- These proofs are also called as **General Strategies for Proving Theorems**
1. Direct Proof (p → q)
Steps: 
A. Assume p(hypothesis) is true
B. Show/Prove that q(conclusion) must be true

2. Indirect Proof or Proof by Contraposition (¬q → ¬p)
Steps:
A. Assume ¬q(hypothesis) is true
B. Show/Prove that ¬p(conclusion) must be true
- or given p → q, let p → q ≡ ¬q → ¬p then apply direct proof on ¬q → ¬p

3. Proof by Contradiction (p ^ ¬q)
Steps:
A. Negate the whole statement (if the statement is in the form of (p → q)
B. Then show that a contradiction will exists
- or given p → q, assume p is true and ¬q is true, then substitute ¬q in p which will lead to a contradiction

4. Proof by Cases
Steps:
A. List all the possible iterations for the inputs
B. Find the output for each set of inputs
- example will be a **Truth Table**

5. Proof by Equivalence
Steps:
Use the table for Logical Equivalances and apply it the formula until simplified.
Some of the most common logical equivalances are:
A. Identity Laws
B. Domination Laws
C. Idempotent Laws
D. Double Negation Laws
E. Commutative Laws
F. Associative Laws
G. Distributive Laws
H. De Morgan's Law
I. Absorption Laws
J. Negation Laws
K. Implication Equivalence

#Week 6
