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

** QUIZ 1!!**

#Week 6
This week marks the start of the lecture for Quiz 2
The class focused on: Functions

**Functions**
- it has three main parts:
Domain
- the set of all possible inputs of a function which allow the function to work; the sets does not apply to the domain
Codomain
- the set of all possible outputs of a function; directly affected by the sets
Range
- Range - a subset of Codomain or the used values of the Codomain hence "Actually Occurring values"

Types of Functions:
Injunction or One-to-One
- given any b in set B, there is only one a in set A that can be paired with the given b
- each domain is assigned to another codomain, no domain can be assigned to another same codomain (all values are paired)
Surjection or Onto
- if every element b in set B has a corresponding element a in set A such that f(a) = b
- the range and codomain are equal
Bijection or One-to-One and Onto
- each element of set A is paired with exactly one element of set B, and each element of the set B is paired with exactly one element of set A (no unpaired elements); 
- must satisfy onto and one-to-one
**A function must be a Bijection to be inversed**

Other Types of Functions:
Floor Function
- rounds the number down
ex. flr(1.4) = 1, flr(2.1) = 2

Ceiling Function
- rounds the number up
ex. ceil(1.1) =2, ceil(2.1) = 3

Does not affect whole numbers

# Week 7

The week the class focused on:
- Algorithms
- Pseudocode

Algorithms
- is a procedure or formula for solving a problem, based on conductiong a sequence of specified actions

Types of Algorithms:
Searching Algorithms
- the problem of finding an element in an ordered and sorted list
A. Linear Search Algorithm
- compare each value until the value wanted is found
B. Binary Search Algorithm
- find the middle term of the indices and compare it, 
- if not found and greater than the value in the middle index, use the upper part of the indices
- if not found and lower the the value in the middle index, use the lower part of the indices
- compare the new middle value and compare it, repeat until value is found

Sorting Algorithms
- the problem of putting elements in an increasing order
A. Bubble Sort
- compare the 2 adjacent elements and place the lower value element in front
- compare the next 2 adjacent elements, repeat until sorted
B. Insertion Sort
- compare compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.

Greedy Algorithms
- the process of finding the best path

# Week 8

This week the class focused on:
- Big O notations
- Quiz 2

Big O notation
- is used in Computer Science to describe the performance or complexity of an algorithm. Big O specifically describes the worst-case scenario, and can be used to describe the execution time required or the space used by an algorithm.
- Big O specifies the upper bound wherein the C*gx is always greater than the f(x)



# Week 9

This week the class focused on:
- Big Omega
- Big Theta

Big Omega notation
- The big omega also shows the time complexity of an algorithm without showing the upper bound limits. The big omega specifies the lower bound wherein the c*gx is always smaller than the f(x)

Big Theta
- basically, it is the combination of big O and big Omega.

# Week 10

This week the class focused on:
- Graph theory

Graph theory 
- heavily realies on the visual logic of a person
- A graph consists of two main parts namely:
A. Vertex 
- the nodes wherein the edges are connected
B. Edges
- lines that connects nodes with another node

Each vertex has its own degree. A degree of a vertex is the number of edges incident with it.
A graph can also has its own subgraph as long as it contains the same vertex and same edges and as long as the two graphs are not equal at both the vertices and edges.

Handshaking Theorem
- 2e = Sum[deg(v)] 
- is mainly used to determine the number of edges or the number of degrees that the vertices have. 

A picture of the Konigsberg problem is shown as an introduction to Eulers.

Euler Circuit 
- a Euler circuit is a graph wherein all the edges are passed-by without repeating an edge. Also, the starting vertex is also the end vertex
- to determine if a graph is a Euler circuit, all of the degree of its vertices should be even.

Euler Path
- same concept as Euler circuit. However, the starting vertex is not the end vertex.
- to determine if a graph is a Euler path, exactly 2 of its vertices should have odd degree.

Hamiltonina Circuit
- a Hamiltonian circuit is a graph wherein all the vertices are passed-by without repeating an edge. Also, the starting vertex is also the end vertex

Hamiltonina Path
- same concept as Hamiltonian circuit. However, the starting vertex is not the end vertex.

- Quiz 3!!

# Week 11
- More concepts regarding Graph Theory

Isomorphic Graph
- Graphs that have equal vertices/nodes, and have the same connection. However, the graph is twisted so it doesn't look alike

Planar Graph
- No edges cross in a graph.
- Isomorphic graphs tend to complicate whethere a graph is planar or non-planar

Euler's formula for counting the regions: 
r = e - v +2

For solving if a graph is planar or non-planar:
Kuratowski's Theorem 
- Nonplanar if and only if it contains a subgraph homeophobic to K3,3 and K5.

# Week 12
- We were asked by Sir Cabatuan to study at home the topics of Trees

# FINAL EXAM :D
