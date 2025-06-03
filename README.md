# LC-Cognition
Sponsored by Cambridge Cognition
King's College Cambridge 

Papers
<a href="https://archive.org/details/lcinterface-meta-modeldoc">Reports</a>

<img src="https://github.com/fanhubgt/LC-Cognition/blob/e741feaa73f3bfdbe2193ef546fca3b3bfdd9953/Screenshot_20250306-140058_1.png"/>

In building all the apps use Netbeans IDE 6/7 only. 
Lib/jdesktop.jar
Lib/jswing.jar, both in app zips.

##########################
                 Introduction to Letter Combinatorics
                                   by 
                            Dr. Frank Appiah
                ########################################

Letter combinatorics is about sentences or phrases and counting problems. 
It is logical structured and involves discrete operations like subtraction,
addition and multiplication. 
It is about alphanumeric labeling of sentences or phrases and proofing of 
combinatorial enumerations. This teaches the theory of combina-torics of sentences 
or phrases or words called Letter Combinatorics (LC) with the 8-bulletin requirements.
A Marriage Problem(MP) made up of 5 sentences are used in the exploit of letter combinatorics. 
A generating function is calculated for MP  to handle constraints of arrangement/selection and
the combin-atorial enumerations of MP are also calculated. This example of letter combinatorics
 shows the calculation of addition , multiplication and subtraction principles of MP.

This teaches the theory of combinatorics of sentences or 
phrases or words called Letter Combinatorics (LC). 
A Letter Marriage Problem (LMP) set is used in the exploit 
of letter combina-torics.  This example of letter combinatorics 
shows the calculation of addition, multiplication and subtraction principles of LMP.

##################################
1.0 Letter Combinatorics Requirement
##################################

1.Letter Combinatorics has or must have the following requirements:
		A countable number of sentences or phrases.
		Counting the size of selected phrases for likely occurrence of 
                        subset equality of letters is called count.
		A sentence with the number of letters specified is called П.
		The logical structure of arithmetic such as +, - and = should be applied.
		Discrete operations must include count, addition, subtraction and sizes.
		The sizes of selected phrases are enumerated.
		Proofs with the discrete operations on which the enumeration of sizes stops.
		There is a possibility of summation equal to П.

2.(Count Equality Principle) Definition: 
The size of selected phrases for likely occurrence of subset equality of letters.

	An r-combination of n distinct objects is an unordered selection, or subset of r out
       of the n objects(letters). The fundamental skills of combinatorial reasoning on 
       letter combinatorics is simply a class of counting problems. 

Count Equality is a principle of solution of specific classes of counting 
problem with no arrangement but selection with repetition. 

The two main counting principles in the elements of classes of counting problem 
are addition and multiplication principles. 

3.Addition Principle states that if there are  different objects in the first set,r1 
 different objects in the second set,r2 ...,rm and  different objects in the mth
 set, and if the different sets are disjoint, then the number of ways to select 
an object from one of the mth sets is r1+r2+r3+...rm. 
	On the other hand, Multiplication Principle supposes a procedure can be 
broken into successive (ordered) stages with r1 different outcomes in the first 
stage, r2 different outcomes in the second stage, …, and rm different outcomes 
in the mth stage. 
If the number of outcomes at each stage is independent of the choices in previous
stages and if the composite outcomes are all distinct, the total procedure has 
different r1xr2xr3...rm composite outcomes.

4.A distribution problem is equivalent to an arrangement or selection problem 
with repetition. 
The focus on modeling distribution problems can be broken into sub-cases that 
can be counted in terms of simple permutation and combinations. The process of 
distributing r identical letter objects into n different letter objects is the 
selection equivalence of distribution. 

		Selection Equivalence of Letter Distribution[SELD] (Corollary 1): 
The distributions of identical letter objects(word) are equivalent to letter 
selections.

Distributing of distinct letter objects are equivalent to arrangements but letter
 combinations do not have that as a generally specialized distribution problem.
1.(Letter Count Problem) Theorem: Letter combinatorics is a counting problem.

2.(Letter Cut) Lemma: A selected phrase is by cutting a number of possible letters.

Finally, it is a counting problem and a selected phrase is by cutting a number of
 possible letters.

	1.(Cutting Strategy) Proposition: 
        A strategy of cutting the possible matches can continue with as many 
        comparisons as needed.

	2.(П-Sentence) Axiom:  П is a number of letters specified in a sentence.

######################################
2.0 MARRIAGE PROBLEM (EXAMPLE)
######################################

(1) Damn it.
(2) What's wrong?
(3) It is a combination of 46 letters.
(4) Akua will not marry you.
(5) Pokua will not marry you.

1. Partition of Integers (Definition): A partition of countable integer, count 
to be a collection of positive integers whose sum is N. 
 
2. For the Marriage Problem(MP) Example, the partition of integers are: 
Damn       it.              (1)
4        +    2      =  N  = 6.
What's    wrong          (2)
5        +    5      =  N   = 10.
3. The collection or set of a sum and the list of integers of the partition is 
in increasing order. 
MP = { 6, 10 },  MP set is a set of marriage problem partitions of integers. 


Letter Marriage Problem is a sentential summation  operated by subtraction on 
minimum and maximum  values given as LMPSet={6, 10, 14, 19, 20, 27}. LMPSet is 
union of RMPSet1 and sum(MP6).

	A discrete operation about another discrete operation is a discrete 
        meta-operation. It seems that there is only one discrete operation in 
        the logical structure for some cases. This is not the case, the count 
        of sentence or  size of letters/word is all based on additive operation.
        sum(L4, s) is a perfect discrete meta-operation that uses both  subtraction 
        and addition operations. 
	The sentence for 4 states:
	(4)Akua will not marry you.

######################################
3.0 MOON-SUN-GO PROBLEM (EXAMPLE 2)
######################################

(1) Go away
(2) Go away moon
(3) Go away moon-sun
(4) The sun is go away thing
(5) The moon is go away thing
(6) The sun and moon goes upto the sky  | The sun and moon go upto the skies

For the MOON-SUN-GO Problem(MSGP) Example, the partition of integers are: 
Go       away                   (1)
2    +    4           =  N   = 6.
Go      away      moon          (2)
2   +    4     +    4 =  N   = 10.
The sun is  go away thing    (4)
3 + 3 + 2 + 2 + 4  + 5    =N =19

MP={6,10,19}, MP set is a set of MOON-SUN-GO problem partitions of integers. 
The MOON-SUN-GO problem and MARRIAGE problem are the same partition of integers.
Different problems with different word or sentence structures. This is Appiah Test.

--------------------------------
Appiah Test: The test of possible outcomes of sentence system yielding same 
partition of integers to one of the problems-MOON-SUN-GO problem and MARRIAGE 
problem.
#########
      Appiah Complete Information:
        A letter combinatorial solution is complete in a sentence system
        if and only if there is a partition of integers of members to the 
        set that equals{6,10,14,19,20,27} or one of Appiah Test SubSet.

 {6,10,19,20},  {6,10,14,19,20} and  {6,10,14,19,20,27} are Appiah Test SubSet.


######################################
3.0 FAMILY-VISION PROBLEM (EXAMPLE 3)
######################################

(1) At home | Family
(2) We are close
(3) We live in a house
(4) We are family business
(5) It has family set in home
(6) We have family computer in a home

For the FAMILY-VISION Problem(FVP) Example, the partition of integers are: 
We   are  close            (2)
2  +  3  +  5       =  N   = 10.
We live in a house         (3)
2 + 4 + 2 +1+ 5     =  N   = 14.
We are family business    (4)
2 + 3 + 6    +   8   =N =19.

FAMILY-VISION PROBLEM passes Appiah Test.



#####################
4.0 USER PROBLEM
#####################

A user problem is used by user of the program that have already numbers instead 
of letter in mind. It follows abaca model of sentence. Even though a user has
number, the systen is modeled on sentences, so one has model an abaca sentences
to represent the numbers in mind.

For the USER-PROBLEM Example,
abbaca      (1)
123456= N= 6
acbaca  baca (2)
  6    + 4   = N = 10
accaca   abab  baca
  6    +   4  + 4 =14
abbaca   abba  baca   abbaca
 6    +   4  +  4    +   6    =20

USER PROBLEM passes (1-4) Appiah TestSet.

#####################
Research Findings
#####################

The discrete subtraction operation of LMP is the same to the real marriage 
problem (RMP) is the first research finding. The meta-operation of LMP is 
the second research finding based on the determination of all counts of LC 
on LMPset.
The research finding is based on the introduction of discrete subtraction 
operation on the minimum and maximum summations in LC of RMP.Finally, Appiah Test 
and Appiah Complete Information are the main research findings.


-----------------------------------------------------------------
PRODUCT: LCCompute Educational Tool for Combinatorists and Combinatorians.

End Users: Computer Specialist/Scientist, Mathsist, Mathematicians, 
Mathsian, Mathematicalist, Mathematicalian and Cognitive Scientist.
