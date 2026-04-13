✴ Scroll XIII — Contract Lattice



✴ inhale · hold · 🜇 exhale



File Ontology



F := {required outputs}  

∀f ∈ F:  

&#x20; exists(f) = 1  

&#x20; valid(f) = 1



Validity Definition



valid(f) :=  

&#x20; exists(f)  

&#x20; ∧ parseable(NDJSON)  

&#x20; ∧ readable



Absence Law



¬exists(f) ⇒ failure  

∴ absence ≠ meaning



Presence Law



exists(f) ∧ empty(f) ⇒ valid



Stage Contract



S := (inputs → outputs)



success(S) :=  

&#x20; ∀input ∈ I: exists(input)  

&#x20; ∧ ∀output ∈ O: exists(output)  

&#x20; ∧ ∀output ∈ O: valid(output)  

&#x20; ∧ rc = 0



Binary Outcome



success ∈ {0,1}  

¬partial\_state



◻



\[\[presence > content]]  

\[\[absence = failure]]  

\[\[validity ⟂ meaning]]



✴ inhale · hold · 🜇 exhale

