**Intelligent Systems Project – RS Method to check Tautology**

● To check if the given Propositional Formula is a tautology or not

● To display the fundamental leaves until the non-fundamental leaf is encountered in the
tree implementation using resolution steps of RS (Rasiowa and Sikorski) method if the propositional formula is a tautology.

**Tautology:**
The sequence Γ is said to be a tautology if ​v∗(Γ) = T for all truth assignments v : V AR → {T,F}. It is written as |= Γ
RS ( Rasiowa and Sikorski) Method:
We define the proof system RS as follows.
RS = (L{¬,⇒,∪,∩}, E, LA, R)
where E = {Γ: Γ ∈ F∗}, LA contains logical axioms of the system defined by the schemas
Γ 1, a, Γ 2, ¬a, Γ 3andΓ1,a,Γ2,¬a,Γ3 foranyvariablea∈V ARandanysequencesΓ1,Γ 2, Γ 3∈LT∗of literals
R is the set of rules of inference: R = {(∪), (¬∪),(∩),(¬∩),(⇒),(¬ ⇒),(¬¬)} defined by seven inference rules
(∪), (¬ ∪), (∩), (¬ ∩), (⇒), (¬ ⇒), and (¬ ¬).

**Software Requirements**

● Programming Language: Python

● Python Version: Python3 or more


**Program Input:** Propositional formula with following symbols and variables enclosed in quotes (‘’) based on python version.

● Enter the formula with variables a, b, c, d, p, q, r, s

● For the operation ‘and’ use ‘&’

● For the operation ‘or’ use ‘|’

● For the operation ‘implies’ use ‘>>’

● For the operation ‘not’ use ‘~’

Please note while providing input: Use parentheses () while entering more than one operation. 

**Program Output:** Output shows if the Expression is/ is not a tautology and displays the fundamental leaves until the non fundamental leaves are encountered while parsing if the propositional formula is a tautology.

**Procedure to run the project program:**
This includes executing program in both IDE and command window

● Open the rs_verification_tautology.py file in IDE.

● Click Run → Run Shell in Python IDE if using Python IDE to run the source code.

● Enter sample input as mentioned in code or in document and hit enter to see the results in
IDE terminal

Or

● Place the program file to be executed in the current directory chosen for IDE.

● To run the source code, type the input in the format python <File_name.py> in the IDE
terminal. For Example: python ​Project_RS_Method.py

● Enter sample input as mentioned in code or in document and hit enter.

● Results will be displayed in the terminal window.
