# Simple-PINN-cases
Mainly introduces a **simple PINN case**, but also in my learning PINN contact with the first model, I would like to share for everyone to learn.  

The case can be changed to suit your needs. Time t is not currently considered and further updates will follow, hopefully.
 
- **PDE:** $\frac{\partial^2 u}{\partial x^2}- \frac{\partial^4 u}{\partial y^4}=\left ( 2-x^2 \right ) e^{-y} $
- **BC:**  $u_{yy} \left ( x, 0 \right ) = x^2$  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $u_{yy} \left ( x, 1 \right ) = \frac{x^2}{e} $  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $u \left ( x, 0 \right ) = x^2$    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $u \left ( x, 1 \right ) = \frac{x^2}{e} $  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $u \left ( 0, y \right ) = 0 $  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $u \left ( 1, y \right ) = e^{-y} $     

<div style="display: flex">
    <img src="https://github.com/Icebergzzz/Simple-PINN-cases/assets/157273375/2d9b2b62-128f-4ff1-88d9-e850d713788e" alt="First Image" style="margin-right: 10px;" />
    <img src="https://github.com/Icebergzzz/Simple-PINN-cases/assets/157273375/d8ca5a21-9488-4380-a819-c755aa1064c0" alt="Second Image" />
</div>


![u_comparison](https://github.com/Icebergzzz/Simple-PINN-cases/assets/157273375/06b1684d-50df-4cf9-8a2a-0d0118d3c4e5)
