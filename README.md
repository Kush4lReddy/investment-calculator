### **Introduction for the Investment Calculator**  
This **Investment Calculator** helps users plan their financial future by offering two calculation modes:  
1. **Target-Based Calculation** – Enter your desired future amount, and the calculator will determine how much you need to invest regularly or as a lump sum to reach that goal.  
2. **Current-Based Calculation** – Input your current investment details, and the calculator will estimate the future value based on your contributions and interest rate.  

This tool is designed to assist users in making informed investment decisions by applying financial mathematics to project potential returns.  

---

### **Mathematical Formulas Used**  

#### **1. Future Value Calculation (Starting with Current Situation)**  
For compound interest:  
\[
FV = P(1 + r/n)^{nt} + \frac{C \left((1 + r/n)^{nt} - 1\right)}{r/n}
\]
Where:  
- \( FV \) = Future Value  
- \( P \) = Initial Investment  
- \( r \) = Annual Interest Rate (as a decimal)  
- \( n \) = Number of compounding periods per year  
- \( t \) = Number of years  
- \( C \) = Regular contribution per period  

#### **2. Reverse Calculation (Target-Based Approach)**  
To determine the required initial investment \( P \):  
\[
P = \frac{FV - \frac{C \left((1 + r/n)^{nt} - 1\right)}{r/n}}{(1 + r/n)^{nt}}
\]
To find the required regular contribution \( C \):  
\[
C = \frac{FV - P(1 + r/n)^{nt}}{( (1 + r/n)^{nt} - 1) / (r/n)}
\]
  
This allows users to backtrack from a financial goal and determine the necessary savings or investment contributions to achieve it.
