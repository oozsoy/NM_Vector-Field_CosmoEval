# NM_Vector-Field_CosmoEval

#### The project intends to include various Mathematica/Python nb files that analyses the cosmological evolution of non-minimally coupled spectator spin-1 fields:
 ```math
 S_{\rm GF}= \int {\rm d}^4 x {\sqrt{-g}}\bigg[ -{\frac{1}{4}F^{\mu\nu}F_{\mu\nu}-\frac{1}{2}m^2 A_{\mu}A^{\mu}} + \frac{\alpha^2}{6}G_{\mu\nu} A^{\mu} A^{\nu} \bigg],
```
#### where $m$ is the bare mass parameter of the vector field and $\alpha$ parametrizes the strength of the non-minimal coupling. 
#### For a cosmological perfect fluid with equation of state $P = w \rho $, physical modes (2 transverse + 1 longitudinal) of the vector field satisfy: 
 ```math
     A''_{\pm} + \big( k^2 + a^2 (m^2 - w\, \alpha^2 H^2) \big) A_{\pm} = 0
 ```
```math
 A''_{L} + \left(1 - \frac{3 (1 + w)\,\alpha^2 H^2 }{2 m_{\rm eff}^2}\right) \frac{k^2}{k^2 + a^2 m_{\rm eff}^2} 2a H A'_{L} + \left(1 - \frac{(1+w)\alpha^2 H^2}{m_{\rm eff}^2}\right)\left(k^2 + a^2 m_{\rm eff}^2\right) A_{L} = 0
```
#### with $m_{\rm eff}^2 = m^2 + \alpha^2 H^2$. Notice that both transverse modes $A_{\pm}$ may exhibit tachyonic instability during radiation dominated universe $w = 1/3$ and for $\alpha^2 H^2 \gg m^2$ for which effects of the non-minimal coupling is relevant. Working in this regime, we track the dynamics of the transverse modes during inflation followed by the radiation dominated universe in AT_Eval.nb to show that $A_{\pm}$ do not exhibit any dangerous behavior which can be tied to the fact that i) tranverse modes stay in their vacuum configuration during inflation (for the light mass regime we are considering $m/H_{\rm I}\to 0$) ii) as a result, velocity gradients introduced during the short transient tachyonic regime following the end of inflation is not enough to drive the amplitude of $A_{\pm}$ to large values during inflation.
