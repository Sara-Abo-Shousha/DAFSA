# DAFSA

In computer science, a deterministic acyclic finite state automaton (DAFSA),[1] also called a directed acyclic word graph (DAWG; though that name also refers to a related data structure that functions as a suffix index) is a data structure that represents a set of strings, and allows for a query operation that tests whether a given string belongs to the set in time proportional to its length. Algorithms exist to construct and maintain such automata,[1] while keeping them minimal.

The program first builds a Trie and them performs a DFA minimization to convert it into a DAWG.

there are 2 ways of creating a DAFSA/DAWG:

Creating a trie then minimizing it
Creating a dawg in one step
