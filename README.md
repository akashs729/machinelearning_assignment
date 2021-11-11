# machinelearning_assignment
General Boundary
The general boundary G, with respect to hypothesis space H and training
data D, is the set of maximally general members of H consistent with D.
G ≡ {g ∈ H|Consistent(g, D) ^ (-∃g' ∈ H)[(g' >gg) A Consistent(g' ^ D)]}



Specific Boundary
The specific boundary S, with respect to hypothesis space H and training
data D, is the set of minimally general (i.e., maximally specific) members of H
consistent with D.
S ≡ {s ∈ H|Consistent(s, D) ^ (-∃g' ∈ H)[(s' >gs') A Consistent(s' ^ D)]}


Version space representation theorem. 
Let X be an arbitrary set of instances 
Let H be a set of boolean-valued hypotheses defined over X. 
Let c : X → {O, 1) be an arbitrary target concept defined over X, 
Let D be an arbitrary set of training examples {<x, c(x)>}. 
For all X, H, c, and D such that S and G are well defined,

VSHS= {h ∈ H| (∃s ∈ S) (∃g ∈ G) (g ≥g h ≥g s)}

Symbol meaning
∃ -	there exists
a∈A -	element of a, belongs to A	
g - grads angle unit
≡	equivalence	identical to
