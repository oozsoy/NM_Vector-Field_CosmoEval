# NM_Vector-Field_CosmoEval

#### The project intends to include various Mathematica/Python nb files to study the cosmological evolution of non-minimally coupled spectator spin-1 fields:
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
#### with $m_{\rm eff}^2 = m^2 + \alpha^2 H^2$. 
#### Notice from the equations of motion that i) transverse modes $A_{\pm}$ may exhibit tachyonic instability during radiation dominated universe $w = 1/3$ and for $\alpha^2 H^2 \gg m^2$ for which effects of the non-minimal coupling is relevant. ii) Similarly, during RDU longitudinal modes may exhibit a gradient instability

#### Working in the $\alpha^2 H_I^2 \gg m^2$ regime where $H_I$ is the Hubble scale during inflation, we track the dynamics of the longitudinal/transverse modes during inflation followed by the radiation dominated universe:

1. To show that $A_{\pm}$ do not exhibit any dangerous behavior which can be tied to the fact that i) tranverse modes stay in their vacuum configuration during inflation (for the light mass regime we are considering $m/H_{\rm I}\to 0$) ii) as a result, velocity gradients introduced during the short transient tachyonic regime following the end of inflation is not enough to drive the amplitude of $A_{\pm}$ to large values during inflation. The analysis that lead to this conclusion is presented in AT_Eval.nb Mathematic notebook file.
2. To check whether the maximally enhanced modes (corresponding to extremely small scales) of the $A_L$ during the gradient instability phase could contribute to the power spectrum $\mathcal{P}_{A_L}$ (and hence to their late time energy density), in particular for the parameter space of interest that leads to the observed DM abundance. This analysis is presented in NM_AL_CosmoEval_ShortModes.ipynb
