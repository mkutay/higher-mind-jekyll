# chapter 1: measurements and uncertainties

# quantities in physics

## fundamental quantities

| time | t | seconds |
| --- | --- | --- |
| length | l | meter |
| mass  | m | kg |
| mole number | n | moles |
| luminous intensity | I  | candela |
| electrical current | i | ampere |
| temperature | T | kelvin |

## derived quantities

all other quantities are derived from fundamental quantities

| velocity | $ms^{-1}$ | $length\times\frac{1}{time\times time}$ |
| --- | --- | --- |
| force | $N=kgms^{-2}$ | $mass\times length\times\frac{1}{time\times time}$ |
| energy force | $kgm^2s^{-2}$ | $mass\times length \times length \times \frac{1}{time \times time}$ |

# significant figure

- non-decimal zeros at the right are not significant
- sandwiched zeros are significant
- zeros at the left are not significant

examples:

0.0002 → 1 s.f.

0.0020 → 2 s.f.

100 → 1 s.f.

0.01020 → 4 s.f.

# uncertainty

![[/ab019e0e-07e0-4b2f-8df0-7497f709bb90.png]]

$6 cm < l < 7cm$

$l=(6.5\pm0.5)cm$

uncertainty occurs due to sensitivity degree of devices

## absolute uncertainty

$a=a_0\pm\Delta a$

$\Delta a$: absolute uncertainty of a

$a_0$: median value

## fractional uncertainty

$\frac{\Delta a}{a_0}$

## percentage uncertainty

$\frac{\Delta a}{a_0}\times 100$

# error bars

error bars are used to include all possible values in graphs

![[/2d02f055-9841-43ea-a763-3711342a0a95.png]]

$P=(3,5\pm0.5)$

- example
    
    ![[/ed069af9-585e-4d26-8d00-bb85d68a1833.png]]
    
    write the length of stick and find its percentage uncertainty (error)
    
    $l=(70\pm2)$
    
    $\frac{2}{70}\times 100=\frac{20}7=\%2.88$
    

## addition/subtraction

let $a=a_0\pm\Delta a$ and $b=b_0\pm\Delta b$

$a+b=(a_0+b_0)\pm(\Delta a+\Delta b)$

$a-b=(a_0 - b_0) \pm (\Delta a + \Delta b)$

in addition and subtraction, absolute uncertainties should be added

## multiplication/division

let $a=a_0\pm\Delta a$ and $b=b_0\pm\Delta b$

$a\times b = (a_0\times b_0)\pm a_0\times b_0\times (\frac{\Delta a}{a_0}+\frac{\Delta b}{b_0})$

$\frac{a}b = (\frac{a_0}{ b_0})\pm \frac{a_0}{b_0}\times (\frac{\Delta a}{a_0}+\frac{\Delta b}{b_0})$

in multiplication and division fractional uncertainties should be added

- proof
    
    $c=a\times b=c_0\pm\Delta c$
    
    $c_0=a_0\times b_0$
    
    $\Delta c=c_0\times \frac{\Delta c}{c_0}=(\frac{\Delta a}{a_0}+\frac{\Delta b}{b_0})\times c_0 = (\frac{\Delta a}{a_0}+\frac{\Delta b}{b_0})\times (a_0+b_0)$
    
- example
    
    let there be a wooden table let one of the sides be $a=(6\pm0.2)$ cm and the other side be $b=(4\pm0.2)$ cm. find the area of the wooden table. (in 2 significant figures)
    
    $a\times b=24\pm 24 \times (\frac{0.2}{6}+\frac{0.2}4)=24\pm 2.0$
    

**note**: in calculations, the result should have significant figure same with the least certain factor.

$0.020 \times 423=8.5$

$0.020$: 2 s.f.

$423$: 3 s.f.

$8.5$: 2 s.f.

# errors

## systematic errors

systematic errors are formed due to the method of experimentation devices

you can create the same error every time

results are reliable but not valid. 

- to avoid or reduce systematic errors, devices should be calibrated well.

## random errors

errors due to experimenter

results are neither reliable nor valid.

- to avoid or reduce random errors, trials should be increased

-take average

# linearisation

![[/7615666e-ab65-4778-a7f6-4334aa74ac95.png]]

y and x are not directly proportional 

- line is not straight
- line does not cross origin

linearisation is changing axes in order to get straight best fit line

# vectors

vectors are physical quantities which have **intensity**, **unit** and **direction**.

![[/c2c60a68-b359-4549-9e5e-65fcff62e11d.png]]

- all vectors are derived quantities
- length of arrow corresponds to intensity of vector

## properties of vectors

- 1
    
    ![[/43dd1295-6f71-49f2-8c1d-111da114a566.png]]
    
    $\vec{A}\neq \vec{B}$
    
    $|\vec{A}|=|\vec{B}|\space \space A=B$: magnitudes are equal
    
- 2
    
    ![[/502764e1-e8aa-4aba-800c-a52ae10a7885.png]]
    
    $\vec{B}=2\times\vec{A}$
    
    - if vector is multiplied with scalar, its intensity changes only (positive numbers)
- 3
    
    ![[/308634a1-27a4-4219-90ba-bc0da583ab0a.png]]
    
    $\vec{A}=-\vec{B}$
    
    - if vector is multiplied with $-1$ only direction changes
- 4
    
    ![[/331b6e22-6482-4772-aad6-2ae930c31810.png]]
    
    components are shadows of vector on given axes
    

## addition and subtraction of vectors

- junction method
    
    ![[/ded36528-f2a9-4feb-a32f-5eea64e52436.png]]
    
    $\vec{A}+\vec{B}+\vec{C}=\vec{R}$
    
    - example
        
        find $\vec{R} = \vec{A}-\vec{B}+\frac{2}{3}\vec{C}$
        
        ![[/6e301fe0-614e-447b-9719-68b1bf14f4dc.png]]