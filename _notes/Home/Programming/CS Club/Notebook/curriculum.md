# curriculum

### week 1

- exercises vs problems
- ACPS page 9
    
    ![[/Screen Shot 2022-11-02 at 20.03.59.png]]
    
    ![[/Screen Shot 2022-11-02 at 20.04.08.png]]
    

explain what exercise is and what problem is

exercise: calculate $5436^3$ without using a calculator

problem: calculate $\frac{1}{1\times2}+\frac{1}{2\times3}+\frac{1}{3\times4}+\cdots+\frac{1}{99\times100}$

in computer science or computer olympiad it is similar 

exercise: write a program to get a string and only output the odd indexed chars

- problem: ([https://atcoder.jp/contests/arc145/tasks/arc145_a](https://atcoder.jp/contests/arc145/tasks/arc145_a))
    
    ![[/Screen Shot 2022-11-02 at 20.15.20.png]]
    
    the code is simple but to find the solution you have to think, the proof of it
    
    you can use this problem to explain wishful thinking
    
- explain the three levels of problem solving
    - A Mountaineering Analogy
        - photo
            
            ![[/Screen Shot 2022-11-02 at 20.19.15.png]]
            
            - 
        - mountaineering to mathematics and computer science
        - prove that the product of four consecutive natural numbers cannot be the square of an integer i.e. $f(n)=n(n+1)(n+2)(n+3)$ can’t be be equal to a perfect square

### week 2

- strategies for investigating problems
- Psychological Strategies
    - connect the houses
        
        ![[/Screen Shot 2022-11-02 at 20.23.31.png]]
        
- creativity
    - connect all nine points below with an unbroken path of four straight lines
        
        ![[/Screen Shot 2022-11-02 at 20.24.54.png]]
        

---

- 1st step: orientation

A few things need to be done at the beginning of every problem.

- Read the problem carefully. Pay attention to details such as positive vs. negative, finite vs. infinite, etc.
- Begin to classify: is it a “to find” or “to prove” problem? Is the problem similar to others you have seen?
- Carefully identify the hypothesis and the conclusion.
- Try some quick preliminary brainstorming:
    - Think about convenient notation.
    - Does a particular method of argument (see Section 2.3) seem plausible?
    - Can you guess a possible solution? Trust your intuition!
    - Are there key words or concepts that seem important? For example, might prime numbers or perfect squares or infinite sequences play an important role?
- 2nd step: get your hands dirty
    - Plug in lots of numbers. Keep playing around until you see a pattern. Then play around some more, and try to figure out why the pattern you see is happening. It is a well-kept secret that much high-level mathematical research is the result of low-tech “plug and chug” methods.
    - 1. The great Carl Gauss,
    widely regarded as one of the greatest mathematicians in history (see page 64), was a big fan of
    this method. In one investigation, he painstakingly computed the number of integer solutions to $*𝑥^2 + 𝑦^2 ≤ 90000*$
    - penultimate step: Once you know what the desired conclusion is, ask yourself, “What will yield the conclusion in a single step?” Sometimes a penultimate step is “obvious,” once you start looking for one. And the more experienced you are, the more obvious the steps are.
- 3rd step: wishful thinking and make it easier
    - [https://codeforces.com/contest/1375/problem/C](https://codeforces.com/contest/1375/problem/C)
    - make the left and right side 1