# {index}`Logic`
## Introduction
Logic is the systematic study of reasoning and argumentation. It provides a structured framework for understanding how propositions (statements) relate to each other and how conclusions can be drawn from given premises. Logic is an essential tool in various disciplines, including philosophy, mathematics, computer science, linguistics, and more. It helps us evaluate the validity of arguments and make informed decisions based on sound reasoning.

Logic is governed by various laws and principles that help us analyze and manipulate propositions. For instance the **{index}`Law of Non-Contradiction`** states that
> *A proposition cannot be both true and false at the same time.*

<iframe width="560" height="315" src="https://www.youtube.com/embed/DkQhK8O9Jik?si=7-SYvoETvxLYfrAN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Logic can be done in natural language (English, Finnish...) or through a formal language, as seen below.

## Basic concepts of logic

**Propositions**
- {index}`Closed proposition`s are statements that can be true (T) or false (F), but not both simultaneously. For example, "The sky is blue" and "$2 + 2 = 5$" are closed propositions and they can be determined definitively based on established facts or logical reasoning.
- {index}`Open propositions` are statements that cannot be definitively assigned a truth value because it contains variables, ambiguous terms, or is dependent on future events or circumstances. For example "It will rain tomorrow." and "$5x+4=4$" are open propositions.

**{index}`Logical connectives`**
Logical connectives are words or symbols that combine propositions to create more complex statements. Common logical connectives include

| Connective      | Symbol            | Meaning                           | Example |
|-----------------|-------------------|-----------------------------------| ------- |
| Negation        | $\neg$            | NOT, reverses truth value         | "It's not cloudy." |
| Disjunction     | $\lor$            | OR, at least one proposition true | "It's raining OR it's snowing." |
| Conjunction     | $\land$           | AND, both propositions are true   | "It's sunny AND it's warm." |
| Implication     | $\Rightarrow$     | IF...THEN, implication            | "If it's raining, then the ground is wet." |
| Biconditional   | $\Leftrightarrow$ | IF AND ONLY IF, equivalence       | "It's cold IF AND ONLY IF it's not warm." |

> If a statement involves multiple logical connectives, the order of evaluation is
> 1. negation
> 2. conjunction and disjunction
> 3. implication and biconditional

**{index}`Truth Tables`** are tables that show all possible truth values of compound propositions based on the truth values of their component propositions. For all possible values of propositions of $p$ and $q$, a truth table can be written as

|   $p$   |   $q$   |  $\neg p$   |  $p \lor q$  |  $p \land q$  |  $p \Rightarrow q$  |  $p \Leftrightarrow q$ |
|-------|-------|-------|---------|---------|---------|---------|
|   T   |   T   |   F   |    T    |    T    |    T    |    T    |
|   T   |   F   |   F   |    T    |    F    |    F    |    F    |
|   F   |   T   |   T   |    T    |    F    |    T    |    F    |
|   F   |   F   |   T   |    F    |    F    |    T    |    T    |

A **{index}`tautology`** is a logical statement that is always true, for example $p \lor \neg p$, "I own a bicycle OR I don't own a bicycle." A **{index}`contradiction`** then again is always false, for example $p \land \neg p$, "I own a bicycle AND I don't own a bicycle."