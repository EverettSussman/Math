---
layout: realAnalysisBlog
permalink: /realAnalysis/chapter1
title: Rudin Chapter 1
---

# Major Theorems

## The Equivalence of the Supremum of Lower Bounds and Infimums of Sets

The first theorem in this chapter is an excellent example of how visuals can be very helpful.  We have:

**Theorem 1. (Rudin 1.11)**:  Suppose $S$ is an ordered set with the **least-upper-bound** property, $B \subset S$, $B$ is not empty, and $B$ is bounded below. Let $L$ be the set of all lower bounds of $B$. Then
$$α = \sup L$$
exists in $S$, and $α= \inf B$ exists in $S.$

The above theorem can be captured in the below picture:

![theorem1_11](theorem1_11.jpg)

Note that $S$ is an ordered set, so relations like $x_1 < x_2, \forall x_1, x_2 \in S$ are well defined.  Further, $B$ is not empty (there exist $x_i$ like the points drawn in $B$), and $L$ must not be empty (since $B$ is bounded below by $L$).  Therefore, if we let $l_1 \in L$, then $l_1$ must be lower than any $x_i \in B$.  Similarly, any $x_i \in B$ must be greater than all of the $l_i \in L$.  Thus, $L$ is bounded from above.  

Now, we know that $S$ has the least-upper-bound property by assumption.  Therefore, there must exist a supremum of the set $L$, $\alpha$, within $S$.  By definition, this means that any element $l_i < \alpha$ is in $L$, and importantly not in $B$.  This implies that $\alpha \leq x \forall x \in B$, which in turn means $\alpha \in L$.    

We also know that every element $x_i > \alpha$ is not in $L$ since $\alpha$ is an upper bound for $L$.  This implies that any $x_i > \alpha$ is not a lower bound for $B$, or that $\alpha$ is the largest lower bound for $B$.  By definition, this makes $\alpha = \inf B$.  

Note that in the above picture, $\alpha$ does not necessarily have to be in $B$, especially in the event where there is a closed hole above $\alpha$.  However, the image makes the relationship between the supremum and infimum much clearer.  



# Relationship between Rationals and Irrationals

The first problem for this chapter is that
