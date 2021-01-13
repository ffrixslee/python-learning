# Python-learning
Repository to store attempted python exercises

## readings
Resources related to software engineering (and some thoughts)

<b> Decision tables:</b>  
https://www.hillelwayne.com/decision-tables/  

<b> Z3 solver: </b>  
https://rise4fun.com/z3/tutorial 
- A SMT solver that can produce multiple solutions by setting constraints.  

<b> Dramatically Reducing Software Vulnerabilities (2016) on formal methods:</b>  
https://nvlpubs.nist.gov/nistpubs/ir/2016/NIST.IR.8151.pdf  
- Software analysis approaches based on mathematics and logic include parsing, type checking, correctness proofs, model-based development and correct-by-construction.  
- Advances in algorithms for solving Boolean Satisfiability(SAT) problems, satisfiability modulo theories(SMT) and reasoning models(e.g., abstract interpretation and separation logic) dramatically slashed resources required to answer questions about software.  
- Model checkers can be used to check for vulnerabilities and potential bugs in the system.  
- However, formal methods are less effective if there are no clear software requirements or what constitutes as the expected behaviour.  

<ins>Sound Static Program Analysis</ins>
- Static analysis: Examination of software for specific properties without executing it.  
- Heuristic analysis: Trial-and-error  
- Hybrid is potentially better as it can check for properties that are absent in the individual analysis  
- Source code analysis: self-explanatory; most mature  

<ins> Model Checkers, SAT Solvers and Other "Light Weight" Decision Algorithms</ins>  
- These algorithms can answer questions about desirable higher level properties.  
- These algorithms can also be applied to analyze detailed design artifacts, such as finite (and infinite) state machines.  
- In other words; constraint solvers.  
- However, a potential issue is the size of the problem.  

<ins> Assertions, Pre- and Postconditions, Invariants, Aspects and Contracts</ins>  
- Automated aids, such as Counterexample-Guided Abstraction Refinement(CEGAR), can help produce statements. These statements are activated("compiled in") during development and testing, then may be deactivated before release.  
- Tests may be generated directly from assertions.  
- However, must check that preconditions do not conflict with the model checker constraints.  

<ins> Correct-by-Construction and Model-Based Development</ins>
- Behaviour may be specified in a higher-level or domain-specific language or model, and then code is automatically generated.  
- Keyword: code synthesis, test suites or oracles  

<ins> Directory of Verified Tools and Verified Code</ins>
- As a code or "live" instantiation of a repository, the Open Web Application Security Project(OWASP) foundation coordinated a project to develop a shared application program interface (API) that encapsulated key security operation, called Enterprise Security API (ESAPI).
