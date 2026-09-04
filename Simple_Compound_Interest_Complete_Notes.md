# 📈 SIMPLE & COMPOUND INTEREST (साधारण एवं चक्रवृद्धि ब्याज) — ONE SHOT MASTER NOTES

> **Source:** Kaushik Mohanty Sir (Career Definer / Ex-Banker RRB)  
> **Target Exams:** IBPS PO/Clerk, SBI PO/Clerk, RRB PO/Clerk, RBI Assistant, LIC AAO, NIACL, SSC CGL & All Banking/Insurance Prelims + Mains  
> **Note Architecture:** Dual-Approach Pedagogy (🎯 Kaushik Sir's Speed Method / Fraction / Tree / Ratio / Successive % / Multiplier Method + 📘 Standard Detailed Algebraic Method) with Bilingual Statements (Hindi + English).

---

## 📑 TABLE OF CONTENTS
1. [Master Formula Sheet & Core Concepts](#1-master-formula-sheet--core-concepts)
   - 1.1 Simple Interest (SI) Core Foundations & Effective Rate Concept
   - 1.2 Compound Interest (CI) Dynamics: Fraction, Tree & Successive % Frameworks
   - 1.3 Compounding Frequencies (Annual, Half-Yearly, Quarterly, Monthly)
   - 1.4 The SI vs CI Difference Master Theorems ($D_2$, $D_3$, and Ratio $\frac{D_3}{D_2}$)
   - 1.5 Particular Year CI vs Cumulative Total CI (Tree Differentiation)
   - 1.6 The "Times" (गुना) Rules: SI Linear vs CI Geometric Progression
   - 1.7 Equal-Interval Multiplier Theorem (Geometric Progression of Amounts)
   - 1.8 Installment Frameworks (SI vs CI Loan Amortization)
   - 1.9 Master Rate & Effective Percentage Conversion Table
2. [Complete Question Bank — All 36 Questions Solved](#2-complete-question-bank--all-36-questions-solved)
   - **Set 1: Basic Rate Finding, Compounding Cycles & Tree Fundamentals (Q01 – Q08)**
   - **Set 2: SI-CI Differences & Multi-Stage Reinvestment Schemes (Q09 – Q17)**
   - **Set 3: Comparative Investments, Two Schemes & Alligation Dynamics (Q18 – Q24)**
   - **Set 4: Advanced Scenarios, Variable Rates & Ratio of Differences (Q25 – Q36)**
3. [Master Answer Key & Quick Revision Matrix](#3-master-answer-key--quick-revision-matrix)
4. [Speed Drill & Exam Cheatsheet](#4-speed-drill--exam-cheatsheet)

---

# 1. MASTER FORMULA SHEET & CORE CONCEPTS

## 1.1 Simple Interest (SI) Core Foundations & Effective Rate Concept

```
            Year 1             Year 2             Year 3
       ┌──────────────┐   ┌──────────────┐   ┌──────────────┐
  P ──►│ Interest = I │──►│ Interest = I │──►│ Interest = I │
       └──────────────┘   └──────────────┘   └──────────────┘
       (Every year interest remains IDENTICAL because Principal never changes)
```

### Core Definitions & Formulas:
1. **Principal ($P$):** The initial sum borrowed, lent, or invested (always $100\%$ in percentage calculations).
2. **Rate of Interest ($R\%$):** The interest charged per ₹100 per unit time (usually per annum).
3. **Time ($T$):** The duration for which the principal is lent/borrowed (in years).
4. **Simple Interest ($SI$):**
   $$SI = \frac{P \times R \times T}{100}$$
5. **Total Amount ($A$):**
   $$A = P + SI = P\left(1 + \frac{R \times T}{100}\right)$$

### ⚡ The Kaushik Sir Effective Rate Method:
In Simple Interest, the principal never changes. Therefore, total interest percentage is simply linear multiplication:
$$\text{Effective SI } \% = (R \times T)\%$$
- **Example 1:** $12.5\%$ for $4$ years $\implies 12.5 \times 4 = 50\%$ of $P$.
- **Example 2:** $15\%$ for $3$ years $\implies 15 \times 3 = 45\%$ of $P$.
- **Amount %:** $\text{Effective Amount } \% = (100 + R \times T)\%$.

---

## 1.2 Compound Interest (CI) Dynamics: Fraction, Tree & Successive % Frameworks

In Compound Interest, interest earned in previous periods is added to the principal to form the new principal for subsequent periods ("Interest on Interest").

```
             Year 1                     Year 2                       Year 3
       ┌─────────────────┐       ┌─────────────────┐          ┌─────────────────┐
       │  Interest on P  │       │  Interest on P  │          │  Interest on P  │
       │       (A)       │       │       (A)       │          │       (A)       │
       └─────────────────┘       └────────┬────────┘          └────────┬────────┘
                                          │                            │
                                          ▼                            ▼
                                 ┌─────────────────┐          ┌─────────────────┐
                                 │  Interest on A  │          │ Interest on 2A  │
                                 │       (B)       │          │      (2B)       │
                                 └─────────────────┘          └────────┬────────┘
                                                                       │
                                                                       ▼
                                                              ┌─────────────────┐
                                                              │  Interest on B  │
                                                              │       (C)       │
                                                              └─────────────────┘
```

### 1. The Successive Percentage Formula (for 2 years):
$$\text{Net CI } \% = \left(a + b + \frac{a \times b}{100}\right)\%$$
- If rate is uniform ($R\%$ each year):
  $$\text{Net CI } \% = \left(2R + \frac{R^2}{100}\right)\%$$
- **Standard Values (Must Memorize):**
  - $10\%$ for 2 yrs: $10 + 10 + 1 = 21\%$
  - $20\%$ for 2 yrs: $20 + 20 + 4 = 44\%$
  - $25\%$ for 2 yrs: $25 + 25 + 6.25 = 56.25\% = \frac{9}{16}$
  - $15\%$ for 2 yrs: $15 + 15 + 2.25 = 32.25\%$
  - $12\%$ for 2 yrs: $12 + 12 + 1.44 = 25.44\%$

### 2. The Fractional Multiplier / Ratio Method ($P : A$):
Convert rate $R\%$ into fraction $\frac{1}{x}$:
$$\text{Principal : Amount for 1 period} = x : (x + 1)$$
- For $n$ periods:
  $$P : A = x^n : (x + 1)^n$$
  $$\text{Compound Interest } (CI) = (x + 1)^n - x^n \text{ units}$$
- **Example:** $R = 25\% = \frac{1}{4}, n = 3$ years:
  $$P : A = 4^3 : 5^3 = 64 : 125 \implies CI = 125 - 64 = 61\text{ units}$$

### 3. Kaushik Sir's Master Tree Method (ट्री मेथड):
Let rate $R = \frac{1}{a}$. Assume Principal $P = a^2$ (for 2 yrs) or $a^3$ (for 3 yrs):

#### **2-Year Tree ($P = a^2$):**
- **Year 1:** $a$
- **Year 2:** $a + 1$
- **Total SI for 2 yrs:** $2a$
- **Total CI for 2 yrs:** $2a + 1$
- **Difference ($CI_2 - SI_2$):** $1\text{ unit}$

#### **3-Year Tree ($P = a^3$):**
- **Year 1:** $a^2$
- **Year 2:** $a^2 + a$
- **Year 3:** $a^2 + 2a + 1$
- **Total SI for 3 yrs:** $3a^2$
- **Total CI for 3 yrs:** $3a^2 + 3a + 1$
- **Difference ($CI_3 - SI_3$):** $3a + 1\text{ units}$

---

## 1.3 Compounding Frequencies

When interest is compounded $m$ times a year:
$$\text{Effective Rate per period } (R') = \frac{R}{m}, \quad \text{Effective Number of periods } (n') = n \times m$$

| Frequency | Periods per year ($m$) | Rate per cycle ($R'$) | Cycles in $T$ years ($n'$) | Example: $R=20\%, T=1\text{ yr}$ |
| :--- | :---: | :---: | :---: | :---: |
| **Annually** | 1 | $R$ | $T$ | $R'=20\%, n'=1 \implies 20\%$ |
| **Half-Yearly (अर्धवार्षिक)** | 2 | $\frac{R}{2}$ | $2T$ | $R'=10\%, n'=2 \implies 21\%$ |
| **Quarterly (त्रैमासिक)** | 4 | $\frac{R}{4}$ | $4T$ | $R'=5\%, n'=4 \implies 21.55\%$ |
| **Monthly (मासिक)** | 12 | $\frac{R}{12}$ | $12T$ | $R'=1.67\%, n'=12$ |

---

## 1.4 The SI vs CI Difference Master Theorems

### 1. Difference for 2 Years ($D_2 = CI_2 - SI_2$):
$$D_2 = P \left(\frac{R}{100}\right)^2 = \frac{SI \times R}{200}$$
- **Direct Formula for Principal:**
  $$P = \frac{D_2 \times 100^2}{R^2} = D_2 \times \left(\frac{100}{R}\right)^2$$

### 2. Difference for 3 Years ($D_3 = CI_3 - SI_3$):
$$D_3 = P \left(\frac{R}{100}\right)^2 \left(3 + \frac{R}{100}\right) = D_2 \times \left(3 + \frac{R}{100}\right)$$
- In fractional units ($R = \frac{1}{a}, P = a^3$):
  $$D_3 = (3a + 1)\text{ units}$$

### 3. Master Ratio of Differences (3 Years vs 2 Years):
$$\frac{D_3}{D_2} = \frac{CI_3 - SI_3}{CI_2 - SI_2} = \frac{300 + R}{100} = 3 + \frac{R}{100}$$
- **Direct Rate Shortcut:**
  $$R = \left(\frac{D_3}{D_2} - 3\right) \times 100\%$$
- *Example:* If $\frac{D_3}{D_2} = \frac{13}{4} = 3.25 \implies R = (3.25 - 3) \times 100 = 25\%$. (Direct 2-second strike!)

---

## 1.5 Particular Year CI vs Cumulative Total CI

> ⚠️ **CRITICAL DISTINCTION IN BANK EXAMS:**  
> "CI for 3 years" means **Cumulative Total Interest** across all 3 years ($CI_1 + CI_2 + CI_3$).  
> "CI in 3rd year" means **Interest earned during the 3rd year alone** ($CI_3$).

### Comparison Table (for $P = a^3, R = \frac{1}{a}$):
| Parameter | 1st Year | 2nd Year | 3rd Year | Total (Cumulative) |
| :--- | :---: | :---: | :---: | :---: |
| **Simple Interest** | $a^2$ | $a^2$ | $a^2$ | $3a^2$ |
| **Compound Interest** | $a^2$ | $a^2 + a$ | $a^2 + 2a + 1 = (a+1)^2$ | $3a^2 + 3a + 1$ |
| **Difference between consecutive years** | — | $(a^2 + a) - a^2 = a$ | $(a^2 + 2a + 1) - (a^2 + a) = a + 1$ | — |
| **Diff: 3rd Year CI vs 2nd Year CI** | — | — | **$(a + 1)\text{ units}$** | — |

---

## 1.6 The "Times" (गुना) Rules: SI Linear vs CI Geometric

### Case 1: Simple Interest (Linear Arithmetic Progression)
In SI, interest added each period is constant:
$$P \to N \times P \implies SI = (N - 1)P$$
Since $SI \propto T$:
$$\frac{N_1 - 1}{T_1} = \frac{N_2 - 1}{T_2} = \frac{R}{100}$$

- **Example:** A sum becomes $17\times$ in 40 years:
  $$17 - 1 = 16\text{ times } SI \text{ in } 40\text{ yrs} \implies \frac{16}{40} = \frac{R}{100} \implies R = 40\%$$

### Case 2: Compound Interest (Geometric Progression)
In CI, the amount multiplies by equal factor in equal time intervals:
$$P \xrightarrow{T\text{ yrs}} n \cdot P \xrightarrow{T\text{ yrs}} n^2 \cdot P \xrightarrow{T\text{ yrs}} n^3 \cdot P \dots$$
- **Power-Time Matching Rule:**
  $$P \to n^1 \cdot P \quad \text{in } T_1\text{ years}$$
  $$P \to n^k \cdot P \quad \text{in } T_2 = k \times T_1\text{ years}$$
- **General Equation:**
  $$(N_1)^{\frac{1}{T_1}} = (N_2)^{\frac{1}{T_2}}$$

---

## 1.7 Equal-Interval Multiplier Theorem (CI Geometric Progression)

When time intervals between consecutive amounts are identical ($\Delta T$ is equal):
$$\frac{A_1}{P} = \frac{A_2}{A_1} = \frac{A_3}{A_2} = \dots = \text{Multiplier } (M) = \left(1 + \frac{R}{100}\right)^{\Delta T}$$

### Crucial Inferences:
1. **To find Principal ($P$):**
   $$P = \frac{A_1^2}{A_2}$$
2. **To find subsequent Amount ($A_3$):**
   $$A_3 = \frac{A_2^2}{A_1}$$

---

## 1.8 Installment Frameworks (ऋण किस्त)

### 1. Simple Interest Installments (Annual Payment $x$):
Total debt due after $T$ years at $R\%$ per annum:
$$\text{Debt} = x \cdot T + \frac{x \cdot R}{100} \times \frac{T(T-1)}{2}$$

### 2. Compound Interest Installments (Annual Payment $x$):
Borrowing $P$ repaid in $n$ equal annual installments $x$ at $R\%$ CI:
$$P = \frac{x}{\left(1 + \frac{R}{100}\right)} + \frac{x}{\left(1 + \frac{R}{100}\right)^2} + \dots + \frac{x}{\left(1 + \frac{R}{100}\right)^n}$$

---

## 1.9 Master Rate & Effective Percentage Conversion Table

| Annual Rate ($R$) | Fraction | 2-Yr Effective SI | 2-Yr Effective CI | 2-Yr Diff ($D_2\%$) | 3-Yr Effective SI | 3-Yr Effective CI | 3-Yr Diff ($D_3\%$) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **5%** | $\frac{1}{20}$ | $10\%$ | $10.25\%$ | $0.25\%$ | $15\%$ | $15.7625\%$ | $0.7625\%$ |
| **8%** | $\frac{2}{25}$ | $16\%$ | $16.64\%$ | $0.64\%$ | $24\%$ | $25.9712\%$ | $1.9712\%$ |
| **10%** | $\frac{1}{10}$ | $20\%$ | $21.00\%$ | $1.00\%$ | $30\%$ | $33.10\%$ | $3.10\%$ |
| **12%** | $\frac{3}{25}$ | $24\%$ | $25.44\%$ | $1.44\%$ | $36\%$ | $40.4928\%$ | $4.4928\%$ |
| **12.5%** | $\frac{1}{8}$ | $25\%$ | $26.5625\% = \frac{17}{64}$ | $1.5625\%$ | $37.5\%$ | $42.3828\% = \frac{217}{512}$ | $4.8828\%$ |
| **15%** | $\frac{3}{20}$ | $30\%$ | $32.25\%$ | $2.25\%$ | $45\%$ | $52.0875\%$ | $7.0875\%$ |
| **20%** | $\frac{1}{5}$ | $40\%$ | $44.00\%$ | $4.00\%$ | $60\%$ | $72.80\%$ | $12.80\%$ |
| **25%** | $\frac{1}{4}$ | $50\%$ | $56.25\% = \frac{9}{16}$ | $6.25\%$ | $75\%$ | $95.3125\% = \frac{61}{64}$ | $20.3125\%$ |

# 2. COMPLETE QUESTION BANK — ALL 36 QUESTIONS SOLVED

## SET 1: Basic Rate Finding, Compounding Cycles & Tree Fundamentals (Q01 – Q08)

---

### 🔹 QUESTION 01
**Topic:** Simple Interest to Compound Interest Conversion | **Concept:** Times Rule & Half-Yearly Compounding

**English:**  
A sum becomes 17 times itself when invested for 40 years at $r\%$ simple interest per annum. Find the compound interest earned if ₹75,000 is invested at $r\%$ per annum compounded half-yearly for 1 year.

**हिन्दी:**  
एक धनराशि $r\%$ वार्षिक साधारण ब्याज पर 40 वर्षों के लिए निवेश करने पर स्वयं की 17 गुना हो जाती है। यदि ₹75,000 को उसी $r\%$ वार्षिक दर पर 1 वर्ष के लिए अर्धवार्षिक रूप से संयोजित चक्रवृद्धि ब्याज पर निवेश किया जाए, तो अर्जित चक्रवृद्धि ब्याज ज्ञात कीजिए।

**Options:**  
a) ₹30,000  
b) ₹36,000  
c) ₹34,000  
d) ₹33,000  
e) ₹32,000  

**Correct Answer:** **d) ₹33,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Times Rule & Half-Yearly Cycle):
1. **Find Rate $r\%$ using SI Times Shortcut:**
   - Amount $= 17P \implies SI = (17 - 1)P = 16P$.
   - Effective SI % in 40 years $= 1600\%$.
   $$r = \frac{1600\%}{40} = 40\% \text{ p.a.}$$
2. **Apply Half-Yearly Compounding on ₹75,000 for 1 Year:**
   - Compounding frequency $= 2$ cycles per year.
   - Cycle Rate $R' = \frac{40\%}{2} = 20\%$.
   - Total cycles $n = 1 \times 2 = 2$ cycles.
3. **Successive % for 2 cycles at 20%:**
   $$\text{Effective CI } \% = 20 + 20 + \frac{20 \times 20}{100} = 44\%$$
4. **Calculate Compound Interest:**
   $$CI = 44\% \text{ of } ₹75,000 = 0.44 \times 75,000 = \mathbf{₹33,000}$$

---

#### 📘 Standard Algebraic Approach:
- Let the Principal be $P$.
- Given: $A = 17P \implies SI = A - P = 16P$.
- Using $SI = \frac{P \times r \times T}{100}$:
  $$16P = \frac{P \times r \times 40}{100} \implies r = \frac{16 \times 100}{40} = 40\%$$
- Now, for CI: Principal $P' = ₹75,000$, Rate per half-year $r' = \frac{40}{2}\% = 20\%$, Time period $n = 2$ half-years.
- Amount $A' = P'\left(1 + \frac{r'}{100}\right)^n = 75000 \times \left(1 + \frac{20}{100}\right)^2 = 75000 \times \left(\frac{6}{5}\right)^2 = 75000 \times \frac{36}{25} = 3000 \times 36 = ₹1,08,000$.
- Compound Interest $CI = A' - P' = 1,08,000 - 75,000 = \mathbf{₹33,000}$.

---

### 🔹 QUESTION 02
**Topic:** Interlinking CI & SI | **Concept:** Power-Ratio Matching & SI Linear Rate

**English:**  
A certain sum becomes 1.75 times itself when invested for $T$ years at $R\%$ simple interest per annum. Find $R$ if ₹6250 amounts to ₹10,800 in $T$ years at 20% compound interest compounded annually.

**हिन्दी:**  
एक निश्चित धनराशि $T$ वर्षों में $R\%$ वार्षिक साधारण ब्याज पर स्वयं की 1.75 गुना हो जाती है। यदि ₹6250 की राशि $20\%$ वार्षिक चक्रवृद्धि ब्याज की दर से $T$ वर्षों में ₹10,800 हो जाती है, तो $R$ का मान ज्ञात कीजिए।

**Options:**  
a) 15%  
b) 20%  
c) 25%  
d) 30%  
e) 35%  

**Correct Answer:** **c) 25%**

---

#### 🎯 Kaushik Sir's Speed Approach (Ratio Power Matching):
1. **Find Time $T$ from the CI Scheme:**
   - Rate $= 20\% = \frac{1}{5} \implies P : A \text{ for 1 year} = 5 : 6$.
   - Given: Principal $= ₹6250$, Amount $= ₹10,800$.
   $$\frac{P}{A} = \frac{6250}{10800} = \frac{625}{1080} = \frac{125}{216} = \left(\frac{5}{6}\right)^3$$
   - Since base ratio is $\frac{5}{6}$, the power gives time:
     $$T = 3\text{ years}$$
2. **Find Rate $R\%$ from the SI Scheme:**
   - Sum becomes $1.75$ times $\implies SI = 1.75P - P = 0.75P = 75\%$ of $P$.
   - In SI, total rate is spread evenly over time:
     $$R = \frac{\text{Total SI } \%}{T} = \frac{75\%}{3} = \mathbf{25\%}$$

---

#### 📘 Standard Algebraic Approach:
- In the CI scheme:
  $$A = P\left(1 + \frac{r}{100}\right)^T \implies 10800 = 6250\left(1 + \frac{20}{100}\right)^T$$
  $$\frac{10800}{6250} = \left(\frac{6}{5}\right)^T \implies \frac{216}{125} = \left(\frac{6}{5}\right)^T \implies \left(\frac{6}{5}\right)^3 = \left(\frac{6}{5}\right)^T \implies T = 3\text{ years}$$
- In the SI scheme:
  $$A = 1.75P \implies SI = 0.75P$$
  $$SI = \frac{P \times R \times T}{100} \implies 0.75P = \frac{P \times R \times 3}{100}$$
  $$R = \frac{0.75 \times 100}{3} = \mathbf{25\%}$$

---

### 🔹 QUESTION 03
**Topic:** CI Base Ratio to SI Deduction | **Concept:** Square-Root Period Reduction

**English:**  
The amount received when ₹3200 is invested at $R\%$ compound interest for 2 years is ₹5000. Find the simple interest earned when ₹2400 is invested at $(R - 10)\%$ per annum for 5 years.

**हिन्दी:**  
₹3200 को $R\%$ चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश करने पर प्राप्त मिश्रधन ₹5000 है। यदि ₹2400 को $(R - 10)\%$ वार्षिक साधारण ब्याज पर 5 वर्षों के लिए निवेश किया जाए, तो अर्जित साधारण ब्याज ज्ञात कीजिए।

**Options:**  
a) ₹1200  
b) ₹1500  
c) ₹1800  
d) ₹2100  
e) ₹2400  

**Correct Answer:** **c) ₹1800**

---

#### 🎯 Kaushik Sir's Speed Approach (Square-Root Ratio Method):
1. **Find Rate $R\%$ from CI 2-Year Ratio:**
   $$\frac{P}{A} = \frac{3200}{5000} = \frac{16}{25}$$
   - For 2 years, take square root to get 1-year multiplier:
     $$\sqrt{\frac{16}{25}} = \frac{4}{5} \implies \text{Interest} = 5 - 4 = 1\text{ unit on } 4$$
     $$R = \frac{1}{4} \times 100\% = 25\%$$
2. **Calculate New SI Rate:**
   $$R_{\text{new}} = R - 10\% = 25\% - 10\% = 15\%$$
3. **Calculate Simple Interest for 5 Years:**
   - Effective SI % $= 15\% \times 5 = 75\% = \frac{3}{4}$.
   $$SI = \frac{3}{4} \times ₹2400 = \mathbf{₹1800}$$

---

#### 📘 Standard Algebraic Approach:
- For CI: $A = P\left(1 + \frac{R}{100}\right)^2$
  $$5000 = 3200\left(1 + \frac{R}{100}\right)^2 \implies \frac{5000}{3200} = \frac{25}{16} = \left(1 + \frac{R}{100}\right)^2$$
  $$1 + \frac{R}{100} = \sqrt{\frac{25}{16}} = \frac{5}{4} \implies \frac{R}{100} = \frac{5}{4} - 1 = \frac{1}{4} \implies R = 25\%$$
- For SI:
  - Rate $R' = R - 10 = 25 - 10 = 15\%$.
  - Principal $P' = ₹2400$, Time $T' = 5$ years.
  $$SI = \frac{2400 \times 15 \times 5}{100} = 24 \times 75 = \mathbf{₹1800}$$

---

### 🔹 QUESTION 04
**Topic:** CI Duration to SI Power Scale | **Concept:** Ratio Multiplier & Fractional Unit Scaling

**English:**  
A invested ₹12,000 in Scheme X for $n$ years at 25% compound interest per annum and earned a compound interest of ₹6750. Find the simple interest earned by B if he invests ₹8000 at 12.5% per annum for $n^3$ years.

**हिन्दी:**  
A ने योजना X में ₹12,000 को $n$ वर्षों के लिए 25% वार्षिक चक्रवृद्धि ब्याज पर निवेश किया और ₹6750 का चक्रवृद्धि ब्याज अर्जित किया। यदि B ₹8000 को $12.5\%$ वार्षिक साधारण ब्याज पर $n^3$ वर्षों के लिए निवेश करता है, तो उसके द्वारा अर्जित साधारण ब्याज ज्ञात कीजिए।

**Options:**  
a) ₹6000  
b) ₹7200  
c) ₹8000  
d) ₹9000  
e) ₹10,000  

**Correct Answer:** **c) ₹8000**

---

#### 🎯 Kaushik Sir's Speed Approach (Ratio Base Inspection):
1. **Analyze Scheme X (CI):**
   - Principal $P = ₹12,000$, Interest $CI = ₹6750$.
   - Amount $A = 12,000 + 6750 = ₹18,750$.
   $$\frac{P}{A} = \frac{12000}{18750} = \frac{1200}{1875} = \frac{48}{75} = \frac{16}{25} = \left(\frac{4}{5}\right)^2$$
   - Since $R = 25\% = \frac{1}{4}$, the 1-year ratio is $4 : 5$.
   - Therefore: $n = 2\text{ years}$.
2. **Analyze Scheme Y (SI):**
   - Time period $= n^3 = 2^3 = 8\text{ years}$.
   - Rate $= 12.5\% = \frac{1}{8}$.
   - Effective SI % $= 12.5\% \times 8 = 100\%$.
   $$SI = 100\% \text{ of } ₹8000 = \mathbf{₹8000}$$

---

#### 📘 Standard Algebraic Approach:
- In Scheme X:
  $$A = P\left(1 + \frac{25}{100}\right)^n \implies 18750 = 12000\left(\frac{5}{4}\right)^n$$
  $$\left(\frac{5}{4}\right)^n = \frac{18750}{12000} = \frac{25}{16} = \left(\frac{5}{4}\right)^2 \implies n = 2$$
- In Scheme Y:
  - Principal $P_B = ₹8000$, Rate $R_B = 12.5\% = \frac{25}{2}\%$.
  - Time $T_B = n^3 = 2^3 = 8$ years.
  $$SI_B = \frac{8000 \times 12.5 \times 8}{100} = \frac{8000 \times 100}{100} = \mathbf{₹8000}$$

---

### 🔹 QUESTION 05
**Topic:** SI Linear Growth & CI Two-Year Rate | **Concept:** Variable Principal Scaling & Successive %

**English:**  
A sum of $5P$ amounts to $8P$ in $t$ years at 12% simple interest per annum. If a sum of $5P$ is invested at 20% compound interest per annum for $(t - 3)$ years, the compound interest earned is ₹1760. Find the value of $P$.

**हिन्दी:**  
$5P$ की एक धनराशि $12\%$ वार्षिक साधारण ब्याज की दर से $t$ वर्षों में $8P$ हो जाती है। यदि $5P$ की उसी धनराशि को $20\%$ वार्षिक चक्रवृद्धि ब्याज की दर से $(t - 3)$ वर्षों के लिए निवेश किया जाए, तो अर्जित चक्रवृद्धि ब्याज ₹1760 है। $P$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹500  
b) ₹600  
c) ₹750  
d) ₹800  
e) ₹1000  

**Correct Answer:** **d) ₹800**

---

#### 🎯 Kaushik Sir's Speed Approach:
1. **Find Time $t$ via Effective SI:**
   - Principal $= 5P$, Amount $= 8P \implies SI = 3P$.
   - Percentage gain $= \frac{3P}{5P} \times 100\% = 60\%$.
   - Annual Rate $= 12\% \implies t = \frac{60\%}{12\%} = 5\text{ years}$.
2. **Find CI Duration:**
   - Time $= t - 3 = 5 - 3 = 2\text{ years}$.
3. **Effective CI Rate for 2 Years at 20%:**
   $$\text{Effective CI } \% = 20 + 20 + 4 = 44\%$$
4. **Relate to Real Value:**
   $$44\% \text{ of } (5P) = ₹1760$$
   $$5P = \frac{1760}{0.44} = ₹4000 \implies P = \frac{4000}{5} = \mathbf{₹800}$$

---

#### 📘 Standard Algebraic Approach:
- Step 1: In SI, $SI = 8P - 5P = 3P$.
  $$3P = \frac{5P \times 12 \times t}{100} \implies 3 = \frac{60t}{100} \implies t = \frac{300}{60} = 5\text{ years}$$
- Step 2: In CI, Principal $= 5P$, Rate $= 20\%$, Time $= 5 - 3 = 2$ years.
  $$CI = 5P\left[\left(1 + \frac{20}{100}\right)^2 - 1\right] = 5P\left[\frac{36}{25} - 1\right] = 5P \times \frac{11}{25} = \frac{11P}{5}$$
- Step 3: Equate to given CI:
  $$\frac{11P}{5} = 1760 \implies P = \frac{1760 \times 5}{11} = 160 \times 5 = \mathbf{₹800}$$

---

### 🔹 QUESTION 06
**Topic:** Particular Year Compound Interest | **Concept:** Tree Method for 3rd Year Only Interest

**English:**  
Shivam invested ₹$X$ in a scheme offering 25% compound interest per annum for 3 years. If the compound interest earned in the 3rd year alone is ₹31,250, then find the value of $X$.

**हिन्दी:**  
शिवम ने एक योजना में 3 वर्षों के लिए 25% वार्षिक चक्रवृद्धि ब्याज पर ₹$X$ का निवेश किया। यदि केवल तीसरे वर्ष में अर्जित चक्रवृद्धि ब्याज ₹31,250 है, तो $X$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹60,000  
b) ₹64,000  
c) ₹72,000  
d) ₹80,000  
e) ₹96,000  

**Correct Answer:** **d) ₹80,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Tree Structure Base $a^3$):
1. **Fraction of Rate:**
   $$R = 25\% = \frac{1}{4} \implies a = 4$$
2. **Construct 3-Year Tree on Base $P = a^3 = 4^3 = 64\text{ units}$:**
   - 1st Year Interest $= a^2 = 16\text{ units}$.
   - 2nd Year Interest $= a^2 + a = 16 + 4 = 20\text{ units}$.
   - 3rd Year Interest alone $= (a + 1)^2 = 5^2 = 25\text{ units}$.
     $$\text{Alternatively: } 16\text{ (on P)} + 4 + 4\text{ (on previous interest)} + 1\text{ (on 4)} = 25\text{ units}$$
3. **Equate 3rd Year Unit Value:**
   $$25\text{ units} = ₹31,250$$
   $$1\text{ unit} = \frac{31250}{25} = ₹1,250$$
4. **Calculate Principal ($X$):**
   $$X = 64\text{ units} = 64 \times 1,250 = \mathbf{₹80,000}$$

---

#### 📘 Standard Algebraic Approach:
- Let the Principal be $X$.
- Compound interest in the 3rd year alone $= A_3 - A_2$:
  $$CI_{\text{3rd yr}} = X\left(1 + \frac{1}{4}\right)^3 - X\left(1 + \frac{1}{4}\right)^2 = X\left(\frac{5}{4}\right)^2\left[\frac{5}{4} - 1\right] = X \times \frac{25}{16} \times \frac{1}{4} = \frac{25}{64}X$$
- Given: $\frac{25}{64}X = 31,250$
  $$X = \frac{31250 \times 64}{25} = 1250 \times 64 = \mathbf{₹80,000}$$

---

### 🔹 QUESTION 07
**Topic:** Consecutive Year CI Difference | **Concept:** $(a+1)$ Unit Tree Theorem

**English:**  
Aman lent ₹25,000 at 20% compound interest per annum for 3 years. Find the difference between the compound interest earned in the 3rd year and that in the 2nd year.

**हिन्दी:**  
अमन ने ₹25,000 को 20% वार्षिक चक्रवृद्धि ब्याज की दर से 3 वर्षों के लिए उधार दिया। तीसरे वर्ष में अर्जित चक्रवृद्धि ब्याज और दूसरे वर्ष में अर्जित चक्रवृद्धि ब्याज के बीच का अंतर ज्ञात कीजिए।

**Options:**  
a) ₹800  
b) ₹1000  
c) ₹1200  
d) ₹1400  
e) ₹1500  

**Correct Answer:** **c) ₹1200**

---

#### 🎯 Kaushik Sir's Speed Approach (Tree Shortcut for Consecutive Year Diff):
1. **Fraction of Rate:**
   $$R = 20\% = \frac{1}{5} \implies a = 5$$
2. **Set Principal Units:**
   $$P = a^3 = 5^3 = 125\text{ units}$$
   $$125\text{ units} = ₹25,000 \implies 1\text{ unit} = \frac{25000}{125} = ₹200$$
3. **Master Difference Theorem (Year 3 vs Year 2):**
   - Year 2 CI $= a^2 + a = 25 + 5 = 30\text{ units}$.
   - Year 3 CI $= (a + 1)^2 = 36\text{ units}$.
   $$\text{Difference } = 36 - 30 = 6\text{ units} \quad \text{[Direct formula: } a + 1 = 5 + 1 = 6\text{ units]}$$
4. **Calculate Value:**
   $$\text{Difference} = 6 \times 200 = \mathbf{₹1200}$$

---

#### 📘 Standard Algebraic Approach:
- Principal $P = ₹25,000$, Rate $R = 20\% = \frac{1}{5}$.
- Amount at the end of 1st year $A_1 = 25000 \times \frac{6}{5} = ₹30,000$.
- Interest in 2nd year $CI_2 = 20\% \text{ of } A_1 = 0.20 \times 30000 = ₹6,000$.
- Amount at the end of 2nd year $A_2 = 30000 + 6000 = ₹36,000$.
- Interest in 3rd year $CI_3 = 20\% \text{ of } A_2 = 0.20 \times 36000 = ₹7,200$.
- Difference $= CI_3 - CI_2 = 7200 - 6000 = \mathbf{₹1200}$.

---

### 🔹 QUESTION 08
**Topic:** Inverse Consecutive Year Difference | **Concept:** Finding Principal from $(a+1)$ Unit

**English:**  
The difference between the compound interest earned in the 3rd year and the 2nd year on a certain sum invested at 10% compound interest per annum is ₹132. Find the principal sum.

**हिन्दी:**  
किसी निश्चित धनराशि पर 10% वार्षिक चक्रवृद्धि ब्याज की दर से तीसरे वर्ष और दूसरे वर्ष में अर्जित चक्रवृद्धि ब्याज का अंतर ₹132 है। वह मूलधन ज्ञात कीजिए।

**Options:**  
a) ₹10,000  
b) ₹11,000  
c) ₹12,000  
d) ₹15,000  
e) ₹16,000  

**Correct Answer:** **c) ₹12,000**

---

#### 🎯 Kaushik Sir's Speed Approach (2-Second Direct Ratio):
1. **Fraction of Rate:**
   $$R = 10\% = \frac{1}{10} \implies a = 10$$
2. **Master Consecutive Year CI Gap:**
   $$\text{Difference (Year 3} - \text{Year 2)} = (a + 1) = 10 + 1 = 11\text{ units}$$
3. **Scale to Unit:**
   $$11\text{ units} = ₹132 \implies 1\text{ unit} = \frac{132}{11} = ₹12$$
4. **Calculate Principal ($P = a^3$):**
   $$P = 10^3 = 1000\text{ units} = 1000 \times 12 = \mathbf{₹12,000}$$

---

#### 📘 Standard Algebraic Approach:
- Let the principal sum be $P$.
- Rate $R = 10\% = 0.10$.
- Interest in 2nd year:
  $$CI_2 = P(1 + 0.10)^1 \times 0.10 = 0.11P$$
- Interest in 3rd year:
  $$CI_3 = P(1 + 0.10)^2 \times 0.10 = 1.21P \times 0.10 = 0.121P$$
- Difference:
  $$CI_3 - CI_2 = 0.121P - 0.110P = 0.011P$$
- Given: $0.011P = 132$
  $$P = \frac{132}{0.011} = \frac{132000}{11} = \mathbf{₹12,000}$$

## SET 2: SI-CI Differences & Multi-Stage Reinvestment Schemes (Q09 – Q17)

---

### 🔹 QUESTION 09
**Topic:** SI and CI Relationship | **Concept:** Interest on First Year's Interest & Rate Extraction

**English:**  
The simple interest and compound interest earned on a certain sum for 5 years and 2 years at the same rate of interest per annum are ₹15,000 and ₹6,750 respectively. Find the principal sum.

**हिन्दी:**  
किसी निश्चित धनराशि पर समान वार्षिक ब्याज दर से 5 वर्षों का साधारण ब्याज और 2 वर्षों का चक्रवृद्धि ब्याज क्रमशः ₹15,000 और ₹6,750 है। वह मूलधन ज्ञात कीजिए।

**Options:**  
a) ₹10,000  
b) ₹15,000  
c) ₹12,000  
d) ₹16,000  
e) ₹18,000  

**Correct Answer:** **c) ₹12,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Tree Logic & Interest on Interest):
1. **Find 1 Year Simple Interest:**
   - In SI, interest per year is identical:
     $$\text{SI for 1 year} = \frac{15000}{5} = ₹3,000$$
2. **Break Down 2 Years CI:**
   - Year 1 Interest $= ₹3,000$ (SI and CI are identical in Year 1).
   - Year 2 Total Interest $= CI_2 - \text{Year 1 Interest} = 6750 - 3000 = ₹3,750$.
3. **Identify Interest on Interest:**
   - The extra interest in Year 2 is earned purely on Year 1's ₹3,000:
     $$\text{Extra} = 3750 - 3000 = ₹750$$
     $$R = \frac{750}{3000} \times 100\% = 25\%$$
4. **Calculate Principal ($P$):**
   - 1 year's SI is $25\%$ of $P$:
     $$25\% \text{ of } P = ₹3,000 \implies P = 3000 \times 4 = \mathbf{₹12,000}$$

---

#### 📘 Standard Algebraic Approach:
- Let the Principal be $P$ and annual rate be $R\%$.
- From 5 years SI:
  $$15000 = \frac{P \times R \times 5}{100} \implies P \times R = \frac{15000 \times 100}{5} = 3,00,000 \quad \text{--- (1)}$$
- From 2 years CI:
  $$CI_2 = P\left[\left(1 + \frac{R}{100}\right)^2 - 1\right] = P\left[\frac{2R}{100} + \frac{R^2}{10000}\right] = \frac{2PR}{100} + \frac{PR \times R}{10000}$$
  $$6750 = \frac{2(300000)}{100} + \frac{300000 \times R}{10000}$$
  $$6750 = 6000 + 30R \implies 30R = 750 \implies R = 25\%$$
- Substitute $R = 25\%$ in equation (1):
  $$P \times 25 = 3,00,000 \implies P = \frac{300000}{25} = \mathbf{₹12,000}$$

---

### 🔹 QUESTION 10
**Topic:** 2-Year SI vs CI Difference | **Concept:** Difference Formula & Direct Rate Extraction

**English:**  
The difference between the compound interest and simple interest on ₹6400 for 2 years is ₹100. Find the rate of interest per annum.

**हिन्दी:**  
₹6400 की धनराशि पर 2 वर्षों के लिए चक्रवृद्धि ब्याज और साधारण ब्याज के बीच का अंतर ₹100 है। वार्षिक ब्याज दर ज्ञात कीजिए।

**Options:**  
a) 10%  
b) 15%  
c) 12.5%  
d) 16.66%  
e) 8%  

**Correct Answer:** **c) 12.5%**

---

#### 🎯 Kaushik Sir's Speed Approach (Direct $D_2$ Formula):
1. **Apply 2-Year Difference Theorem:**
   $$D_2 = P \left(\frac{R}{100}\right)^2$$
2. **Substitute Values:**
   $$100 = 6400 \times \left(\frac{R}{100}\right)^2$$
   $$\left(\frac{R}{100}\right)^2 = \frac{100}{6400} = \frac{1}{64}$$
3. **Take Square Root:**
   $$\frac{R}{100} = \frac{1}{8} \implies R = \frac{100}{8} = \mathbf{12.5\%}$$

---

#### 📘 Standard Algebraic Approach:
- Simple Interest for 2 years:
  $$SI = \frac{6400 \times R \times 2}{100} = 128R$$
- Compound Interest for 2 years:
  $$CI = 6400\left[\left(1 + \frac{R}{100}\right)^2 - 1\right] = 6400\left[\frac{2R}{100} + \frac{R^2}{10000}\right] = 128R + 0.64R^2$$
- Difference:
  $$CI - SI = 0.64R^2 = 100$$
  $$R^2 = \frac{100}{0.64} = \frac{10000}{64} = \frac{625}{4}$$
  $$R = \sqrt{\frac{625}{4}} = \frac{25}{2} = \mathbf{12.5\%}$$

---

### 🔹 QUESTION 11
**Topic:** 3-Year SI vs CI Difference | **Concept:** Tree Ratio Base $(3a + 1)$ Theorem

**English:**  
If the difference between the compound interest and simple interest on a certain sum of money for 3 years at 20% per annum is ₹640, find the sum.

**हिन्दी:**  
यदि किसी निश्चित धनराशि पर 20% वार्षिक दर से 3 वर्षों के चक्रवृद्धि ब्याज और साधारण ब्याज का अंतर ₹640 है, तो वह धनराशि ज्ञात कीजिए।

**Options:**  
a) ₹4000  
b) ₹5000  
c) ₹6000  
d) ₹8000  
e) ₹7500  

**Correct Answer:** **b) ₹5000**

---

#### 🎯 Kaushik Sir's Speed Approach (Tree Shortcut $(3a + 1)$):
1. **Convert Rate to Fraction:**
   $$R = 20\% = \frac{1}{5} \implies a = 5$$
2. **Master Difference Formula in Units:**
   $$\text{Difference for 3 Years } (D_3) = (3a + 1)\text{ units}$$
   $$D_3 = 3(5) + 1 = 16\text{ units}$$
3. **Scale Units to Real Value:**
   $$16\text{ units} = ₹640 \implies 1\text{ unit} = \frac{640}{16} = ₹40$$
4. **Calculate Principal ($P = a^3$):**
   $$P = 5^3 = 125\text{ units} = 125 \times 40 = \mathbf{₹5,000}$$

---

#### 📘 Standard Algebraic Approach:
- Master Formula for 3-year difference:
  $$D_3 = P \left(\frac{R}{100}\right)^2 \left(3 + \frac{R}{100}\right)$$
- Substitute $D_3 = 640$ and $R = 20$:
  $$640 = P \times \left(\frac{20}{100}\right)^2 \times \left(3 + \frac{20}{100}\right)$$
  $$640 = P \times \left(\frac{1}{5}\right)^2 \times \left(3 + \frac{1}{5}\right)$$
  $$640 = P \times \frac{1}{25} \times \frac{16}{5} = P \times \frac{16}{125}$$
  $$P = \frac{640 \times 125}{16} = 40 \times 125 = \mathbf{₹5,000}$$

---

### 🔹 QUESTION 12
**Topic:** Multi-Stage Reinvestment | **Concept:** Compounded Interest Reinvested in SI

**English:**  
A person invested a principal $P$ at 10% compound interest per annum for 2 years. The interest received was then invested in another scheme at 15% simple interest per annum for 4 years. If the total interest earned from both schemes together is ₹3360, find $P$.

**हिन्दी:**  
एक व्यक्ति ने मूलधन $P$ को 10% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया। प्राप्त ब्याज को फिर एक अन्य योजना में 15% वार्षिक साधारण ब्याज पर 4 वर्षों के लिए निवेश किया गया। यदि दोनों योजनाओं से अर्जित कुल ब्याज ₹3360 है, तो $P$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹8000  
b) ₹9000  
c) ₹10,000  
d) ₹12,000  
e) ₹15,000  

**Correct Answer:** **c) ₹10,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Successive Rate Tracking):
1. **Interest from Scheme 1 (CI):**
   - Rate $= 10\%$ for 2 years.
   $$\text{Effective CI } \% = 10 + 10 + 1 = 21\% \text{ of } P$$
   $$CI_1 = 0.21P$$
2. **Interest from Scheme 2 (SI on $CI_1$):**
   - Rate $= 15\%$, Time $= 4$ years $\implies$ Effective SI % $= 15 \times 4 = 60\%$.
   $$SI_2 = 60\% \text{ of } CI_1 = 0.60 \times 0.21P = 0.126P = 12.6\% \text{ of } P$$
3. **Combine Total Interest:**
   $$\text{Total Interest} = CI_1 + SI_2 = 21\%P + 12.6\%P = 33.6\%P$$
4. **Equate to ₹3360:**
   $$33.6\% \text{ of } P = 3360$$
   $$P = \frac{3360}{0.336} = \mathbf{₹10,000}$$

---

#### 📘 Standard Algebraic Approach:
- Let the initial principal be $P$.
- Interest from Scheme 1:
  $$I_1 = P\left[\left(1 + \frac{10}{100}\right)^2 - 1\right] = P[1.21 - 1] = 0.21P$$
- Interest from Scheme 2:
  $$I_2 = \frac{I_1 \times R_2 \times T_2}{100} = \frac{0.21P \times 15 \times 4}{100} = \frac{0.21P \times 60}{100} = 0.126P$$
- Total interest received:
  $$I_1 + I_2 = 0.21P + 0.126P = 0.336P$$
- Given $0.336P = 3360$:
  $$P = \frac{3360}{0.336} = \frac{3360000}{336} = \mathbf{₹10,000}$$

---

### 🔹 QUESTION 13
**Topic:** Reinvestment of Amount | **Concept:** Percentage Chain & Algebraic Scaling

**English:**  
Kaushik had ₹$(x + 10,000)$ with him. He invested the entire sum in Scheme A offering 25% simple interest per annum for 4 years. From the total amount received, he invested 60% in Scheme B offering 20% compound interest per annum for 2 years. If the total interest earned from Scheme B is ₹15,840, find $x$.

**हिन्दी:**  
कौशिक के पास ₹$(x + 10,000)$ थे। उसने पूरी धनराशि को योजना A में 25% वार्षिक साधारण ब्याज पर 4 वर्षों के लिए निवेश किया। प्राप्त कुल मिश्रधन में से 60% उसने योजना B में 20% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया। यदि योजना B से अर्जित चक्रवृद्धि ब्याज ₹15,840 है, तो $x$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹15,000  
b) ₹18,000  
c) ₹20,000  
d) ₹24,000  
e) ₹25,000  

**Correct Answer:** **c) ₹20,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Chain Multiplication):
1. **Let Total Sum in Scheme A be $S = (x + 10,000)$:**
   - In Scheme A: Rate $= 25\%$, Time $= 4$ yrs $\implies SI = 100\% \implies \text{Amount } A_1 = 200\% = 2S$.
2. **Investment in Scheme B:**
   $$P_B = 60\% \text{ of } A_1 = 0.60 \times 2S = 1.2S$$
3. **Interest from Scheme B (CI for 2 yrs at 20%):**
   $$\text{Effective CI } \% = 20 + 20 + 4 = 44\%$$
   $$CI_B = 44\% \text{ of } P_B = 0.44 \times 1.2S = 0.528S$$
4. **Solve for $S$ and $x$:**
   $$0.528S = 15840 \implies S = \frac{15840}{0.528} = ₹30,000$$
   $$x + 10,000 = 30,000 \implies x = 30,000 - 10,000 = \mathbf{₹20,000}$$

---

#### 📘 Standard Algebraic Approach:
- Initial Principal $P_A = x + 10,000$.
- Scheme A Amount:
  $$A_A = P_A\left(1 + \frac{25 \times 4}{100}\right) = P_A(1 + 1) = 2P_A$$
- Scheme B Principal:
  $$P_B = 60\% \text{ of } A_A = 0.60 \times 2P_A = 1.2P_A$$
- Scheme B Compound Interest:
  $$CI_B = P_B\left[\left(1 + \frac{20}{100}\right)^2 - 1\right] = 1.2P_A\left[\frac{36}{25} - 1\right] = 1.2P_A \times \frac{11}{25} = \frac{13.2}{25}P_A = 0.528P_A$$
- Given $0.528P_A = 15,840$:
  $$P_A = \frac{15840}{0.528} = 30,000$$
- Thus, $x + 10,000 = 30,000 \implies x = \mathbf{₹20,000}$.

---

### 🔹 QUESTION 14
**Topic:** Partial Interest Reinvestment | **Concept:** Fraction Balancing in Dual Systems

**English:**  
Mantu invested ₹$x$ in Scheme A, offering 20% simple interest per annum for 4 years. He then invested 75% of the interest earned from Scheme A in Scheme B offering 12.5% compound interest per annum for 2 years. If the interest earned from Scheme B is ₹2550, find $x$.

**हिन्दी:**  
मंटू ने योजना A में ₹$x$ को 20% वार्षिक साधारण ब्याज पर 4 वर्षों के लिए निवेश किया। उसने योजना A से प्राप्त ब्याज का 75% योजना B में 12.5% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया। यदि योजना B से अर्जित ब्याज ₹2550 है, तो $x$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹12,000  
b) ₹14,000  
c) ₹16,000  
d) ₹18,000  
e) ₹20,000  

**Correct Answer:** **c) ₹16,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Fraction Chain Method):
1. **Interest from Scheme A:**
   $$SI_A = 20\% \times 4 = 80\% \text{ of } x = \frac{4}{5}x$$
2. **Principal for Scheme B:**
   $$P_B = 75\% \text{ of } SI_A = \frac{3}{4} \times \frac{4}{5}x = \frac{3}{5}x$$
3. **Compound Interest in Scheme B ($R = 12.5\% = \frac{1}{8}, T = 2$ yrs):**
   $$P_B : A_B = 8^2 : 9^2 = 64 : 81 \implies CI_B = 81 - 64 = 17\text{ units}$$
   $$CI_B = \frac{17}{64} P_B$$
4. **Solve for $x$:**
   $$\frac{17}{64} \times \frac{3}{5}x = 2550$$
   $$\frac{51}{320}x = 2550 \implies x = \frac{2550 \times 320}{51} = 50 \times 320 = \mathbf{₹16,000}$$

---

#### 📘 Standard Algebraic Approach:
- In Scheme A:
  $$I_A = \frac{x \times 20 \times 4}{100} = 0.80x$$
- In Scheme B:
  $$P_B = 0.75 \times 0.80x = 0.60x$$
  $$CI_B = P_B\left[\left(1 + \frac{1}{8}\right)^2 - 1\right] = 0.60x\left[\frac{81}{64} - 1\right] = 0.60x \times \frac{17}{64} = \frac{10.2x}{64}$$
- Equating to ₹2550:
  $$\frac{10.2x}{64} = 2550 \implies x = \frac{2550 \times 64}{10.2} = \frac{25500 \times 64}{102} = 250 \times 64 = \mathbf{₹16,000}$$

---

### 🔹 QUESTION 15
**Topic:** Complex Multi-Stage Reinvestment | **Concept:** Split Sum, Partial Interest & Second Scheme Amount

**English:**  
Rihaan has a sum of ₹$6x$ with him. He invested 50% of the sum at 20% simple interest per annum for 4 years. Half of the interest received along with the remaining sum was invested at 25% compound interest per annum for 2 years. If the total amount received from the second scheme is ₹10,500, find the amount received if ₹$6x$ is invested at 12.5% simple interest per annum for 3 years.

**हिन्दी:**  
रिहान के पास ₹$6x$ की धनराशि है। उसने इस राशि का 50% भाग 20% वार्षिक साधारण ब्याज पर 4 वर्षों के लिए निवेश किया। प्राप्त ब्याज का आधा भाग तथा शेष मूलधन को मिलाकर 25% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया गया। यदि दूसरी योजना से प्राप्त कुल मिश्रधन ₹10,500 है, तो ज्ञात कीजिए कि ₹$6x$ को 12.5% वार्षिक साधारण ब्याज पर 3 वर्षों के लिए निवेश करने पर कितना मिश्रधन प्राप्त होगा?

**Options:**  
a) ₹12,000  
b) ₹13,200  
c) ₹14,400  
d) ₹15,000  
e) ₹16,500  

**Correct Answer:** **b) ₹13,200**

---

#### 🎯 Kaushik Sir's Speed Approach:
1. **First Investment:**
   - 50% of $6x = 3x$.
   - $SI_1 = 3x \times 20\% \times 4 = 2.4x$.
2. **Second Scheme Investment ($P_2$):**
   - Remaining initial sum $= 3x$.
   - Half of interest $= \frac{2.4x}{2} = 1.2x$.
   $$P_2 = 3x + 1.2x = 4.2x$$
3. **Compound Amount from Scheme 2 ($R = 25\% = \frac{1}{4}, 2$ yrs):**
   $$P_2 : A_2 = 4^2 : 5^2 = 16 : 25$$
   $$A_2 = 4.2x \times \frac{25}{16} = 10,500$$
   $$4.2x = 10500 \times \frac{16}{25} = 420 \times 16 = 6720 \implies x = \frac{6720}{4.2} = 1600$$
   $$\text{Total Sum } 6x = 6 \times 1600 = ₹9,600$$
4. **Calculate Target SI Amount on ₹9,600:**
   - Rate $= 12.5\% = \frac{1}{8}$, Time $= 3$ yrs $\implies$ Interest fraction $= \frac{3}{8}$.
   $$\text{Amount Multiplier} = 1 + \frac{3}{8} = \frac{11}{8}$$
   $$\text{Target Amount} = ₹9600 \times \frac{11}{8} = 1200 \times 11 = \mathbf{₹13,200}$$

---

#### 📘 Standard Algebraic Approach:
- Principal in Scheme 1 $= \frac{1}{2}(6x) = 3x$.
- Interest in Scheme 1:
  $$I_1 = \frac{3x \times 20 \times 4}{100} = 2.4x$$
- Principal for Scheme 2:
  $$P_2 = \text{Remaining Principal} + \frac{1}{2}I_1 = 3x + 1.2x = 4.2x$$
- Amount after 2 years at 25% CI:
  $$A_2 = 4.2x\left(1 + \frac{25}{100}\right)^2 = 4.2x\left(\frac{5}{4}\right)^2 = 4.2x \times \frac{25}{16} = \frac{105x}{16}$$
- Given $A_2 = 10,500$:
  $$\frac{105x}{16} = 10500 \implies x = \frac{10500 \times 16}{105} = 100 \times 16 = 1600$$
- Total sum $= 6x = 6 \times 1600 = 9600$.
- Simple interest for 3 years at 12.5%:
  $$SI = \frac{9600 \times 12.5 \times 3}{100} = 96 \times 37.5 = 3600$$
- Total Amount $= 9600 + 3600 = \mathbf{₹13,200}$.

---

### 🔹 QUESTION 16
**Topic:** Reinvestment of Amount + Remaining Principal | **Concept:** Balanced CI Extraction

**English:**  
Nikhil had ₹12,000 with him. He invested ₹$x$ at 12.5% simple interest per annum for 4 years. The total amount received along with the remaining initial sum was invested in a scheme offering 25% compound interest per annum for 2 years. If the compound interest earned is ₹9000, find $x$.

**हिन्दी:**  
निखिल के पास ₹12,000 थे। उसने ₹$x$ को 12.5% वार्षिक साधारण ब्याज पर 4 वर्षों के लिए निवेश किया। प्राप्त कुल मिश्रधन तथा शेष प्रारंभिक राशि को मिलाकर एक अन्य योजना में 25% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया गया। यदि अर्जित चक्रवृद्धि ब्याज ₹9000 है, तो $x$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹6000  
b) ₹7500  
c) ₹8000  
d) ₹9000  
e) ₹10,000  

**Correct Answer:** **c) ₹8000**

---

#### 🎯 Kaushik Sir's Speed Approach:
1. **Scheme 1 Amount on $x$:**
   - Effective SI % $= 12.5\% \times 4 = 50\%$.
   $$A_1 = x + 0.50x = 1.50x$$
2. **Combine for Scheme 2 Principal ($P_2$):**
   - Remaining initial sum $= 12,000 - x$.
   $$P_2 = A_1 + (12,000 - x) = 1.50x + 12000 - x = 12000 + 0.50x$$
3. **Compound Interest in Scheme 2 ($R = 25\% = \frac{1}{4}, 2$ yrs):**
   $$P : A = 4^2 : 5^2 = 16 : 25 \implies CI = 25 - 16 = 9\text{ units}$$
   $$CI = \frac{9}{16} P_2 = ₹9000$$
   $$P_2 = \frac{9000 \times 16}{9} = ₹16,000$$
4. **Solve for $x$:**
   $$12,000 + 0.50x = 16,000$$
   $$0.50x = 4,000 \implies x = \mathbf{₹8000}$$

---

#### 📘 Standard Algebraic Approach:
- From Scheme 1:
  $$SI_1 = \frac{x \times 12.5 \times 4}{100} = 0.5x \implies A_1 = x + 0.5x = 1.5x$$
- Principal for Scheme 2:
  $$P_2 = A_1 + (12000 - x) = 1.5x + 12000 - x = 12000 + 0.5x$$
- In Scheme 2, Rate $= 25\%$, Time $= 2$ years:
  $$CI_2 = P_2\left[\left(1 + \frac{25}{100}\right)^2 - 1\right] = P_2\left[\frac{25}{16} - 1\right] = \frac{9}{16}P_2$$
- Given $CI_2 = 9000$:
  $$\frac{9}{16}P_2 = 9000 \implies P_2 = 16,000$$
  $$12000 + 0.5x = 16000 \implies 0.5x = 4000 \implies x = \mathbf{₹8000}$$

---

### 🔹 QUESTION 17
**Topic:** Reverse Rate Calculation | **Concept:** Successive Scheme Unwinding

**English:**  
A sum of ₹18,000 is invested at $r\%$ compound interest per annum for 2 years. The total amount received is then reinvested at 8% simple interest per annum for 5 years. If the final amount received is ₹39,375, find the value of $r$.

**हिन्दी:**  
₹18,000 की धनराशि को 2 वर्षों के लिए $r\%$ वार्षिक चक्रवृद्धि ब्याज पर निवेश किया जाता है। प्राप्त कुल मिश्रधन को फिर 8% वार्षिक साधारण ब्याज पर 5 वर्षों के लिए पुनः निवेश किया जाता है। यदि अंतिम प्राप्त मिश्रधन ₹39,375 है, तो $r$ का मान ज्ञात कीजिए।

**Options:**  
a) 15%  
b) 20%  
c) 22.5%  
d) 25%  
e) 30%  

**Correct Answer:** **d) 25%**

---

#### 🎯 Kaushik Sir's Speed Approach (Reverse Backward Tracking):
1. **Unwind Scheme 2 (SI):**
   - Rate $= 8\%$, Time $= 5$ years $\implies$ Effective SI % $= 8 \times 5 = 40\%$.
   - Final Amount $= 140\% = \frac{7}{5}$ of Intermediate Amount $A_1$.
   $$\frac{7}{5} A_1 = 39,375 \implies A_1 = \frac{39375 \times 5}{7} = 5625 \times 5 = ₹28,125$$
2. **Find Rate $r\%$ from Scheme 1 (CI for 2 yrs):**
   $$\frac{P}{A_1} = \frac{18000}{28125} = \frac{720}{1125} = \frac{144}{225} = \frac{16}{25}$$
   - For 2 years, take square root:
     $$\sqrt{\frac{16}{25}} = \frac{4}{5}$$
   - Rate $= \frac{5 - 4}{4} \times 100\% = \frac{1}{4} \times 100\% = \mathbf{25\%}$$

---

#### 📘 Standard Algebraic Approach:
- Let the intermediate amount after 2 years of CI be $A_1$.
- In the SI scheme:
  $$A_2 = A_1\left(1 + \frac{8 \times 5}{100}\right) = A_1(1 + 0.40) = 1.4A_1$$
- Given $A_2 = 39,375$:
  $$1.4A_1 = 39375 \implies A_1 = \frac{39375}{1.4} = ₹28,125$$
- In the CI scheme:
  $$A_1 = P\left(1 + \frac{r}{100}\right)^2$$
  $$28125 = 18000\left(1 + \frac{r}{100}\right)^2 \implies \left(1 + \frac{r}{100}\right)^2 = \frac{28125}{18000} = \frac{25}{16}$$
  $$1 + \frac{r}{100} = \frac{5}{4} \implies \frac{r}{100} = \frac{1}{4} \implies r = \mathbf{25\%}$$

## SET 3: Comparative Investments, Two Schemes & Alligation Dynamics (Q18 – Q24)

---

### 🔹 QUESTION 18
**Topic:** Dual Scheme Interest Comparison | **Concept:** Equal Principal Percentage Differential

**English:**  
A man invested an equal amount in two schemes, A and B. Scheme A offers 20% simple interest per annum for 3 years, and Scheme B offers 10% compound interest per annum for 3 years. If the difference between the interests received from both schemes is ₹10,760, find the total sum invested in both schemes together.

**हिन्दी:**  
एक व्यक्ति ने दो योजनाओं, A और B में समान धनराशि निवेश की। योजना A 20% वार्षिक साधारण ब्याज 3 वर्षों के लिए देती है, और योजना B 10% वार्षिक चक्रवृद्धि ब्याज 3 वर्षों के लिए देती है। यदि दोनों योजनाओं से प्राप्त ब्याजों के बीच का अंतर ₹10,760 है, तो दोनों योजनाओं में मिलाकर निवेश की गई कुल धनराशि ज्ञात कीजिए।

**Options:**  
a) ₹60,000  
b) ₹70,000  
c) ₹75,000  
d) ₹80,000  
e) ₹90,000  

**Correct Answer:** **d) ₹80,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Net Percentage Difference):
1. **Calculate Effective Percentage for Scheme A (SI):**
   $$\text{Effective SI } \% = 20\% \times 3 = 60\%$$
2. **Calculate Effective Percentage for Scheme B (CI at 10% for 3 yrs):**
   - 2-year CI at 10% $= 21\%$.
   - 3-year CI at 10% $= 21 + 10 + \frac{21 \times 10}{100} = 33.1\%$.
3. **Find Percentage Gap:**
   $$\Delta \% = 60\% - 33.1\% = 26.9\%$$
4. **Scale to Real Value:**
   $$26.9\% \text{ of } P = ₹10,760$$
   $$1\% \text{ of } P = \frac{10760}{26.9} = ₹400 \implies P = ₹40,000$$
5. **Total Sum in Both Schemes Together:**
   $$\text{Total Sum} = P + P = 2P = 2 \times 40,000 = \mathbf{₹80,000}$$

---

#### 📘 Standard Algebraic Approach:
- Let the sum invested in each scheme be $P$.
- Interest from Scheme A:
  $$I_A = \frac{P \times 20 \times 3}{100} = 0.60P$$
- Interest from Scheme B:
  $$I_B = P\left[\left(1 + \frac{10}{100}\right)^3 - 1\right] = P\left[\frac{1331}{1000} - 1\right] = 0.331P$$
- Difference between the two interests:
  $$I_A - I_B = 0.60P - 0.331P = 0.269P$$
- Given $0.269P = 10,760$:
  $$P = \frac{10760}{0.269} = 40,000$$
- Total sum invested in both schemes $= 2 \times 40,000 = \mathbf{₹80,000}$.

---

### 🔹 QUESTION 19
**Topic:** Unequal Principals in Dual Schemes | **Concept:** Fractional Unit Base Matching

**English:**  
Ankit invested in two schemes, A and B, for 3 years at 12.5% per annum. The amount invested in B is twice the amount invested in A. Scheme A offers simple interest and Scheme B offers compound interest. If the difference between the interest earned from Scheme B and Scheme A is ₹6050, find the amount invested in Scheme A.

**हिन्दी:**  
अंकित ने 12.5% वार्षिक दर से 3 वर्षों के लिए दो योजनाओं, A और B में निवेश किया। B में निवेश की गई धनराशि A में निवेश की गई धनराशि की दोगुनी है। योजना A साधारण ब्याज तथा योजना B चक्रवृद्धि ब्याज प्रदान करती है। यदि योजना B और योजना A से अर्जित ब्याज का अंतर ₹6050 है, तो योजना A में निवेश की गई धनराशि ज्ञात कीजिए।

**Options:**  
a) ₹10,000  
b) ₹12,000  
c) ₹12,800  
d) ₹15,000  
e) ₹16,000  

**Correct Answer:** **c) ₹12,800**

---

#### 🎯 Kaushik Sir's Speed Approach (LCM Unit Framework):
1. **Fraction of Rate:**
   $$R = 12.5\% = \frac{1}{8} \implies \text{Base cube} = 8^3 = 512$$
2. **Assign Units based on Principal Ratio ($P_B = 2P_A$):**
   - Let $P_B = 512\text{ units} \implies P_A = \frac{512}{2} = 256\text{ units}$.
3. **Calculate Interests in Units:**
   - In Scheme B (CI for 3 yrs at $\frac{1}{8}$ on 512 units):
     $$P_B : A_B = 8^3 : 9^3 = 512 : 729 \implies CI_B = 729 - 512 = 217\text{ units}$$
   - In Scheme A (SI for 3 yrs at $\frac{1}{8}$ on 256 units):
     $$SI_A = 256 \times \frac{1}{8} \times 3 = 96\text{ units}$$
4. **Find Difference in Units:**
   $$CI_B - SI_A = 217 - 96 = 121\text{ units}$$
5. **Solve for Real Value:**
   $$121\text{ units} = ₹6050 \implies 1\text{ unit} = \frac{6050}{121} = ₹50$$
   $$P_A = 256\text{ units} = 256 \times 50 = \mathbf{₹12,800}$$

---

#### 📘 Standard Algebraic Approach:
- Let the investment in Scheme A be $x$, then investment in Scheme B is $2x$.
- In Scheme A (SI at 12.5% for 3 years):
  $$SI_A = \frac{x \times 12.5 \times 3}{100} = \frac{37.5x}{100} = \frac{3}{8}x$$
- In Scheme B (CI at 12.5% = 1/8 for 3 years):
  $$CI_B = 2x\left[\left(1 + \frac{1}{8}\right)^3 - 1\right] = 2x\left[\frac{729}{512} - 1\right] = 2x \times \frac{217}{512} = \frac{217}{256}x$$
- Difference $CI_B - SI_A = 6050$:
  $$\frac{217}{256}x - \frac{3}{8}x = 6050$$
  $$\frac{217x - 96x}{256} = 6050 \implies \frac{121x}{256} = 6050$$
  $$x = \frac{6050 \times 256}{121} = 50 \times 256 = \mathbf{₹12,800}$$

---

### 🔹 QUESTION 20
**Topic:** Mixed Portfolio Allocation | **Concept:** Alligation on Effective Interest Rates

**English:**  
Sneha had ₹6,000 with her. She invested a part of it at 12.5% simple interest per annum for 4 years and the remaining at 20% compound interest per annum for 2 years. If the total interest received from both investments is ₹2784, find the amount invested at simple interest.

**हिन्दी:**  
स्नेहा के पास ₹6,000 थे। उसने इसका एक भाग 12.5% वार्षिक साधारण ब्याज पर 4 वर्षों के लिए और शेष भाग 20% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया। यदि दोनों निवेशों से प्राप्त कुल ब्याज ₹2784 है, तो साधारण ब्याज पर निवेश की गई धनराशि ज्ञात कीजिए।

**Options:**  
a) ₹2000  
b) ₹3000  
c) ₹3600  
d) ₹2400  
e) ₹2800  

**Correct Answer:** **d) ₹2400**

---

#### 🎯 Kaushik Sir's Speed Approach (Rule of Alligation):
1. **Find Effective Rate of Scheme 1 (SI):**
   $$R_{\text{SI}} = 12.5\% \times 4 = 50\%$$
2. **Find Effective Rate of Scheme 2 (CI):**
   $$R_{\text{CI}} = 20 + 20 + \frac{20 \times 20}{100} = 44\%$$
3. **Find Mean Interest Percentage on Total Principal (₹6,000):**
   $$R_{\text{mean}} = \frac{2784}{6000} \times 100\% = \frac{278.4}{6}\% = 46.4\%$$
4. **Set Up Alligation Cross:**
   ```
          SI Part (50%)              CI Part (44%)
                    \                  /
                     \                /
                      Mean = 46.4%
                     /                                    /                           (46.4 - 44) = 2.4       (50 - 46.4) = 3.6
   ```
   $$\text{Ratio of Investments} = 2.4 : 3.6 = 2 : 3$$
5. **Divide Total Principal (₹6,000) in 2 : 3:**
   $$\text{Total Parts} = 2 + 3 = 5\text{ parts} = ₹6,000 \implies 1\text{ part} = ₹1,200$$
   $$\text{Amount at SI} = 2 \times 1200 = \mathbf{₹2,400}$$

---

#### 📘 Standard Algebraic Approach:
- Let the amount invested at simple interest be $S$, then amount at compound interest is $(6000 - S)$.
- Interest from SI scheme:
  $$I_{\text{SI}} = \frac{S \times 12.5 \times 4}{100} = 0.50S$$
- Interest from CI scheme:
  $$I_{\text{CI}} = (6000 - S)\left[\left(1 + \frac{20}{100}\right)^2 - 1\right] = (6000 - S)(1.44 - 1) = 0.44(6000 - S) = 2640 - 0.44S$$
- Total Interest:
  $$0.50S + 2640 - 0.44S = 2784$$
  $$0.06S = 2784 - 2640 = 144$$
  $$S = \frac{144}{0.06} = \mathbf{₹2,400}$$

---

### 🔹 QUESTION 21
**Topic:** Unequal Investments in Dual Schemes | **Concept:** Linear Combination & Variable Solving

**English:**  
A person invests ₹$x$ in Scheme A at 20% compound interest per annum for 2 years and ₹$(x + 2500)$ in Scheme B at 15% simple interest per annum for 3 years. If the total interest earned from both schemes is ₹5575, find the amount invested in Scheme B.

**हिन्दी:**  
एक व्यक्ति योजना A में 20% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए ₹$x$ और योजना B में 15% वार्षिक साधारण ब्याज पर 3 वर्षों के लिए ₹$(x + 2500)$ निवेश करता है। यदि दोनों योजनाओं से अर्जित कुल ब्याज ₹5575 है, तो योजना B में निवेश की गई धनराशि ज्ञात कीजिए।

**Options:**  
a) ₹5000  
b) ₹6500  
c) ₹7500  
d) ₹8000  
e) ₹8500  

**Correct Answer:** **c) ₹7500**

---

#### 🎯 Kaushik Sir's Speed Approach (Effective Rate Summation):
1. **Effective Rates:**
   - Scheme A (CI at 20% for 2 yrs): $20 + 20 + 4 = 44\% \implies 0.44x$.
   - Scheme B (SI at 15% for 3 yrs): $15 \times 3 = 45\% \implies 0.45(x + 2500)$.
2. **Combine Interests:**
   $$0.44x + 0.45x + 0.45(2500) = 5575$$
   $$0.89x + 1125 = 5575$$
   $$0.89x = 4450$$
3. **Solve for $x$:**
   $$x = \frac{4450}{0.89} = \frac{445000}{89} = ₹5,000$$
4. **Find Investment in Scheme B:**
   $$\text{Scheme B Sum} = x + 2500 = 5000 + 2500 = \mathbf{₹7,500}$$

---

#### 📘 Standard Algebraic Approach:
- In Scheme A:
  $$CI_A = x\left[\left(1 + \frac{20}{100}\right)^2 - 1\right] = 0.44x$$
- In Scheme B:
  $$SI_B = \frac{(x + 2500) \times 15 \times 3}{100} = \frac{45(x + 2500)}{100} = 0.45x + 1125$$
- Total Interest:
  $$CI_A + SI_B = 5575$$
  $$0.44x + 0.45x + 1125 = 5575 \implies 0.89x = 4450 \implies x = 5000$$
- Investment in Scheme B $= x + 2500 = 5000 + 2500 = \mathbf{₹7,500}$.

---

### 🔹 QUESTION 22
**Topic:** Rate Determination with Dual Investments | **Concept:** Annual Rate Linear Combination

**English:**  
Tushar invested ₹50,000 at simple interest of $x\%$ per annum for 2 years and ₹80,000 at compound interest of $(x + 8)\%$ per annum for 1 year. If the total amount received from both schemes together is ₹1,58,000, find the rate of interest for compound interest.

**हिन्दी:**  
तुषार ने ₹50,000 को $x\%$ वार्षिक साधारण ब्याज पर 2 वर्षों के लिए और ₹80,000 को $(x + 8)\%$ वार्षिक चक्रवृद्धि ब्याज पर 1 वर्ष के लिए निवेश किया। यदि दोनों योजनाओं से प्राप्त कुल मिश्रधन ₹1,58,000 है, तो चक्रवृद्धि ब्याज की दर ज्ञात कीजिए।

**Options:**  
a) 12%  
b) 16%  
c) 20%  
d) 24%  
e) 18%  

**Correct Answer:** **c) 20%**

---

#### 🎯 Kaushik Sir's Speed Approach:
1. **Find Total Interest Earned:**
   - Total Principal $= 50,000 + 80,000 = ₹1,30,000$.
   - Total Amount $= ₹1,58,000$.
   $$\text{Total Interest} = 1,58,000 - 1,30,000 = ₹28,000$$
2. **Express Interest in Terms of $x$ (Note: For 1 yr, CI = SI):**
   - Interest from Scheme 1: $50000 \times \frac{2x}{100} = 1000x$.
   - Interest from Scheme 2: $80000 \times \frac{x + 8}{100} = 800(x + 8) = 800x + 6400$.
3. **Solve for $x$:**
   $$1000x + 800x + 6400 = 28000$$
   $$1800x = 21600 \implies x = \frac{21600}{1800} = 12\%$$
4. **Find CI Rate:**
   $$\text{CI Rate} = x + 8 = 12 + 8 = \mathbf{20\%}$$

---

#### 📘 Standard Algebraic Approach:
- For Scheme 1 (SI):
  $$I_1 = \frac{50000 \times x \times 2}{100} = 1000x$$
- For Scheme 2 (CI for 1 year):
  $$I_2 = 80000 \times \frac{x + 8}{100} = 800x + 6400$$
- Total Amount $= P_1 + P_2 + I_1 + I_2 = 1,58,000$:
  $$130000 + 1000x + 800x + 6400 = 158000$$
  $$1800x + 136400 = 158000$$
  $$1800x = 21600 \implies x = 12\%$$
- Therefore, the compound interest rate is $x + 8 = 12 + 8 = \mathbf{20\%}$.

---

### 🔹 QUESTION 23
**Topic:** Allocation with Known Interest Gap | **Concept:** Opposing Balance Equation

**English:**  
Rakesh invested ₹20,000 in scheme A offering 20% compound interest per annum for 2 years and the rest in scheme B offering 15% simple interest per annum for 2 years. If the difference between the compound interest and simple interest earned is ₹1400, find the sum invested in scheme A.

**हिन्दी:**  
राकेश ने कुल ₹20,000 में से कुछ धनराशि योजना A में 20% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए और शेष धनराशि योजना B में 15% वार्षिक साधारण ब्याज पर 2 वर्षों के लिए निवेश की। यदि अर्जित चक्रवृद्धि ब्याज और साधारण ब्याज के बीच का अंतर ₹1400 है, तो योजना A में निवेश की गई धनराशि ज्ञात कीजिए।

**Options:**  
a) ₹8000  
b) ₹10,000  
c) ₹12,000  
d) ₹14,000  
e) ₹15,000  

**Correct Answer:** **b) ₹10,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Deviation / Direct Equation):
1. **Rates:**
   - Scheme A (CI at 20% for 2 yrs): $20 + 20 + 4 = 44\%$.
   - Scheme B (SI at 15% for 2 yrs): $15 \times 2 = 30\%$.
2. **Let Investment in Scheme A be $y$, then in Scheme B is $(20,000 - y)$:**
   $$CI_A - SI_B = 1400$$
   $$0.44y - 0.30(20000 - y) = 1400$$
   $$0.44y - 6000 + 0.30y = 1400$$
   $$0.74y = 7400 \implies y = \frac{7400}{0.74} = \mathbf{₹10,000}$$

---

#### 📘 Standard Algebraic Approach:
- Let the investment in Scheme A be $P_A$ and in Scheme B be $P_B = 20000 - P_A$.
- In Scheme A:
  $$CI_A = P_A\left[\left(1 + \frac{20}{100}\right)^2 - 1\right] = 0.44P_A$$
- In Scheme B:
  $$SI_B = \frac{(20000 - P_A) \times 15 \times 2}{100} = 0.30(20000 - P_A) = 6000 - 0.30P_A$$
- Given $CI_A - SI_B = 1400$:
  $$0.44P_A - (6000 - 0.30P_A) = 1400$$
  $$0.74P_A = 7400 \implies P_A = \mathbf{₹10,000}$$

---

### 🔹 QUESTION 24
**Topic:** Multi-Variable Interest Matching | **Concept:** SI Principal Unwinding & CI Duration Finding

**English:**  
A person invests ₹$(X - 1500)$ at 15% simple interest per annum for 4 years and receives ₹7500 as interest. If he invests ₹$(X - 6000)$ at 20% compound interest per annum for $T$ years, he gets ₹5824 as compound interest. Find the value of $T$.

**हिन्दी:**  
एक व्यक्ति ₹$(X - 1500)$ को 15% वार्षिक साधारण ब्याज पर 4 वर्षों के लिए निवेश करता है और ब्याज के रूप में ₹7500 प्राप्त करता है। यदि वह ₹$(X - 6000)$ को 20% वार्षिक चक्रवृद्धि ब्याज पर $T$ वर्षों के लिए निवेश करता है, तो उसे ₹5824 चक्रवृद्धि ब्याज प्राप्त होता है। $T$ का मान ज्ञात कीजिए।

**Options:**  
a) 1 year  
b) 2 years  
c) 3 years  
d) 4 years  
e) 2.5 years  

**Correct Answer:** **c) 3 years**

---

#### 🎯 Kaushik Sir's Speed Approach (Effective SI & Base Ratio Matching):
1. **Find $X$ from Scheme 1 (SI):**
   - Effective SI % $= 15\% \times 4 = 60\%$.
   $$60\% \text{ of } (X - 1500) = 7500$$
   $$X - 1500 = \frac{7500}{0.60} = 12,500 \implies X = 12500 + 1500 = ₹14,000$$
2. **Find Principal for Scheme 2 (CI):**
   $$P_2 = X - 6000 = 14000 - 6000 = ₹8,000$$
3. **Calculate Amount in Scheme 2:**
   $$A_2 = P_2 + CI = 8000 + 5824 = ₹13,824$$
4. **Compare Ratio to 1-Year Multiplier:**
   - Rate $= 20\% = \frac{1}{5} \implies \text{Base ratio} = \frac{5}{6}$.
   $$\frac{P_2}{A_2} = \frac{8000}{13824} = \frac{1000}{1728} = \frac{125}{216} = \left(\frac{5}{6}\right)^3$$
   - Since the power is 3:
     $$T = \mathbf{3\text{ years}}$$

---

#### 📘 Standard Algebraic Approach:
- In Scheme 1:
  $$SI = \frac{(X - 1500) \times 15 \times 4}{100} \implies 7500 = \frac{(X - 1500) \times 60}{100}$$
  $$X - 1500 = \frac{7500 \times 100}{60} = 12,500 \implies X = 14,000$$
- In Scheme 2:
  - Principal $P_2 = 14000 - 6000 = 8000$.
  - Rate $R = 20\%$.
  $$A_2 = P_2 + CI = 8000 + 5824 = 13,824$$
  $$13824 = 8000\left(1 + \frac{20}{100}\right)^T = 8000\left(\frac{6}{5}\right)^T$$
  $$\left(\frac{6}{5}\right)^T = \frac{13824}{8000} = \frac{1728}{1000} = \frac{216}{125} = \left(\frac{6}{5}\right)^3 \implies T = \mathbf{3\text{ years}}$$

## SET 4: Advanced Scenarios, Variable Rates & Ratio of Differences (Q25 – Q36)

---

### 🔹 QUESTION 25
**Topic:** Borrowed and Re-lent Arbitrage | **Concept:** Rate Spread Profit & Scaled CI

**English:**  
Aman borrowed ₹$(8x + 2000)$ from a bank at 15% simple interest per annum for 2 years. He immediately invested the borrowed amount at 20% simple interest per annum for 2 years and earned a profit of ₹$(x - 200)$ per year. Find the compound interest if the borrowed sum is invested at 25% compound interest per annum for 2 years.

**हिन्दी:**  
अमन ने एक बैंक से 15% वार्षिक साधारण ब्याज पर 2 वर्षों के लिए ₹$(8x + 2000)$ उधार लिए। उसने तुरंत इस उधार ली गई धनराशि को 20% वार्षिक साधारण ब्याज पर 2 वर्षों के लिए निवेश कर दिया और प्रति वर्ष ₹$(x - 200)$ का लाभ अर्जित किया। यदि उधार ली गई धनराशि को 25% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया जाए, तो चक्रवृद्धि ब्याज ज्ञात कीजिए।

**Options:**  
a) ₹2800  
b) ₹3000  
c) ₹3250  
d) ₹3375  
e) ₹3600  

**Correct Answer:** **d) ₹3375**

---

#### 🎯 Kaushik Sir's Speed Approach (Rate Margin Method):
1. **Calculate Annual Net Gain Rate:**
   $$\text{Rate Spread} = 20\% - 15\% = 5\% \text{ per annum}$$
2. **Equate Annual Profit:**
   $$5\% \text{ of } (8x + 2000) = (x - 200)$$
   $$\frac{1}{20}(8x + 2000) = x - 200$$
   $$8x + 2000 = 20x - 4000$$
   $$12x = 6000 \implies x = 500$$
3. **Find the Borrowed Sum:**
   $$\text{Principal } P = 8(500) + 2000 = 4000 + 2000 = ₹6,000$$
4. **Calculate CI at 25% for 2 Years:**
   - Rate $= 25\% = \frac{1}{4} \implies P : A = 4^2 : 5^2 = 16 : 25$.
   - Compound Interest Fraction $= \frac{25 - 16}{16} = \frac{9}{16}$.
   $$CI = \frac{9}{16} \times ₹6,000 = 9 \times 375 = \mathbf{₹3,375}$$

---

#### 📘 Standard Algebraic Approach:
- Principal borrowed $P = 8x + 2000$.
- Interest paid to bank per year $= \frac{P \times 15}{100}$.
- Interest received from lending per year $= \frac{P \times 20}{100}$.
- Net annual gain $= \frac{P \times (20 - 15)}{100} = 0.05(8x + 2000) = 0.40x + 100$.
- Given net gain per year $= x - 200$:
  $$0.40x + 100 = x - 200 \implies 0.60x = 300 \implies x = \frac{300}{0.60} = 500$$
- Principal sum $P = 8(500) + 2000 = 6000$.
- Compound interest for 2 years at 25%:
  $$CI = 6000\left[\left(1 + \frac{25}{100}\right)^2 - 1\right] = 6000\left[\frac{25}{16} - 1\right] = 6000 \times \frac{9}{16} = \mathbf{₹3,375}$$

---

### 🔹 QUESTION 26
**Topic:** Equal Simple Interest Matching | **Concept:** Product Equality $P_1 R_1 T_1 = P_2 R_2 T_2$

**English:**  
Rita invested ₹$(x + 3000)$ in a simple-interest scheme for $n$ years at 24% per annum. Sita invested ₹$x$ in another simple-interest scheme for $2n$ years at 18% per annum. If both of them received the same interest, find the value of $x$.

**हिन्दी:**  
रीता ने ₹$(x + 3000)$ को $n$ वर्षों के लिए 24% वार्षिक साधारण ब्याज की योजना में निवेश किया। सीता ने ₹$x$ को $2n$ वर्षों के लिए 18% वार्षिक साधारण ब्याज की अन्य योजना में निवेश किया। यदि उन दोनों को समान ब्याज प्राप्त हुआ, तो $x$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹4500  
b) ₹5000  
c) ₹6000  
d) ₹7500  
e) ₹8000  

**Correct Answer:** **c) ₹6000**

---

#### 🎯 Kaushik Sir's Speed Approach (Effective Rate Balancing):
1. **Compare Effective Multipliers:**
   - Rita's interest factor $= (x + 3000) \times 24 \times n$.
   - Sita's interest factor $= x \times 18 \times 2n = 36nx$.
2. **Equate and Cancel $n$:**
   $$24(x + 3000) = 36x$$
   $$2(x + 3000) = 3x \quad (\text{dividing both sides by 12})$$
   $$2x + 6000 = 3x$$
   $$x = \mathbf{₹6,000}$$

---

#### 📘 Standard Algebraic Approach:
- Simple interest earned by Rita:
  $$SI_{\text{Rita}} = \frac{(x + 3000) \times 24 \times n}{100}$$
- Simple interest earned by Sita:
  $$SI_{\text{Sita}} = \frac{x \times 18 \times 2n}{100} = \frac{36nx}{100}$$
- Since both interests are equal:
  $$\frac{(x + 3000) \times 24n}{100} = \frac{36nx}{100}$$
  $$24(x + 3000) = 36x \implies 24x + 72000 = 36x$$
  $$12x = 72000 \implies x = \mathbf{₹6,000}$$

---

### 🔹 QUESTION 27
**Topic:** Quadratic SI Rate Solving & CI Reinvestment | **Concept:** Factorization and Amount Comparison

**English:**  
A invested ₹320 in Scheme B at $p\%$ annual simple interest for $(p + 5)$ years and earned ₹480 as simple interest. The total amount received was then reinvested in Scheme C at 25% compound interest per annum for 2 years. Find the difference between the amount received from Scheme C and Scheme B.

**हिन्दी:**  
A ने योजना B में ₹320 को $p\%$ वार्षिक साधारण ब्याज पर $(p + 5)$ वर्षों के लिए निवेश किया और ब्याज के रूप में ₹480 अर्जित किए। प्राप्त कुल मिश्रधन को फिर योजना C में 25% वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए पुनः निवेश किया गया। योजना C और योजना B से प्राप्त मिश्रधनों के बीच का अंतर ज्ञात कीजिए।

**Options:**  
a) ₹400  
b) ₹450  
c) ₹500  
d) ₹550  
e) ₹600  

**Correct Answer:** **b) ₹450**

---

#### 🎯 Kaushik Sir's Speed Approach:
1. **Solve for $p$ via Inspection:**
   $$SI = \frac{320 \times p \times (p + 5)}{100} = 480$$
   $$3.2 \times p(p + 5) = 480 \implies p(p + 5) = \frac{480}{3.2} = 150$$
   - Since the two factors differ by 5: $10 \times 15 = 150 \implies p = 10\%$.
2. **Find Amount from Scheme B ($A_B$):**
   $$A_B = 320 + 480 = ₹800$$
3. **Reinvest ₹800 in Scheme C ($R = 25\% = \frac{1}{4}, 2$ yrs):**
   $$P : A = 4^2 : 5^2 = 16 : 25$$
   $$A_C = 800 \times \frac{25}{16} = 50 \times 25 = ₹1,250$$
4. **Find Difference Between Amounts:**
   $$\Delta A = A_C - A_B = 1250 - 800 = \mathbf{₹450}$$

---

#### 📘 Standard Algebraic Approach:
- Step 1: In Scheme B:
  $$480 = \frac{320 \cdot p(p + 5)}{100} \implies p^2 + 5p - 150 = 0$$
  $$(p + 15)(p - 10) = 0 \implies p = 10 \quad (\text{since } p > 0)$$
- Step 2: Amount from Scheme B:
  $$A_B = 320 + 480 = 800$$
- Step 3: Amount from Scheme C:
  $$A_C = 800\left(1 + \frac{25}{100}\right)^2 = 800\left(\frac{5}{4}\right)^2 = 800 \times \frac{25}{16} = 1250$$
- Step 4: Difference:
  $$A_C - A_B = 1250 - 800 = \mathbf{₹450}$$

---

### 🔹 QUESTION 28
**Topic:** SI to CI Relation with Rate Multiplier | **Concept:** Double Rate CI Decomposition

**English:**  
Mahesh invested a certain sum at $x\%$ per annum simple interest for 4 years and earned ₹8000 as interest. If he had invested the same sum at $2x\%$ per annum compound interest for 2 years, he would have earned ₹8640 as interest. Find the principal sum invested.

**हिन्दी:**  
महेश ने एक निश्चित धनराशि को $x\%$ वार्षिक साधारण ब्याज पर 4 वर्षों के लिए निवेश किया और ब्याज के रूप में ₹8000 अर्जित किए। यदि उसने उसी धनराशि को $2x\%$ वार्षिक चक्रवृद्धि ब्याज पर 2 वर्षों के लिए निवेश किया होता, तो उसे ब्याज के रूप में ₹8640 प्राप्त होते। निवेश की गई मूलधन राशि ज्ञात कीजिए।

**Options:**  
a) ₹20,000  
b) ₹25,000  
c) ₹30,000  
d) ₹32,000  
e) ₹40,000  

**Correct Answer:** **b) ₹25,000**

---

#### 🎯 Kaushik Sir's Speed Approach (Interest Decomposition):
1. **Analyze SI Scheme:**
   - 4 years SI at $x\% = ₹8000$.
   - Therefore: $1\text{ year SI at } x\% = \frac{8000}{4} = ₹2000$.
2. **Analyze CI Scheme (Rate is $2x\%$ for 2 Years):**
   - 1 year interest at $2x\% = 2 \times ₹2000 = ₹4000$.
   - In 2-year CI, the total interest is composed of:
     $$CI = \text{Year 1 Interest} + \text{Year 2 Interest} = 4000 + (4000 + \text{Interest on 4000})$$
     $$CI = 8000 + \text{Extra Interest} = ₹8640$$
     $$\text{Extra Interest} = 8640 - 8000 = ₹640$$
3. **Find Rate $2x\%$:**
   - The extra ₹640 is the interest on ₹4000:
     $$2x\% = \frac{640}{4000} \times 100\% = 16\% \implies x = 8\%$$
4. **Calculate Principal ($P$):**
   - Since 1 year interest at $8\%$ is ₹2000:
     $$8\% \text{ of } P = 2000 \implies P = \frac{2000 \times 100}{8} = \mathbf{₹25,000}$$

---

#### 📘 Standard Algebraic Approach:
- From SI:
  $$SI = \frac{P \cdot x \cdot 4}{100} = 8000 \implies \frac{Px}{100} = 2000 \implies Px = 2,00,000 \quad \text{--- (1)}$$
- From CI at rate $2x\%$ for 2 years:
  $$CI = P\left[\left(1 + \frac{2x}{100}\right)^2 - 1\right] = P\left[\frac{4x}{100} + \frac{4x^2}{10000}\right] = \frac{4Px}{100} + \frac{4(Px)x}{10000}$$
  $$8640 = \frac{4(200000)}{100} + \frac{4(200000)x}{10000}$$
  $$8640 = 8000 + 80x$$
  $$80x = 640 \implies x = 8\%$$
- Substitute $x = 8$ in (1):
  $$P = \frac{200000}{8} = \mathbf{₹25,000}$$

---

### 🔹 QUESTION 29
**Topic:** Staggered SI Investments with Equal Amounts | **Concept:** Equal Interest % Duration Equation

**English:**  
A certain sum was invested by a person at 5% simple interest per annum. After 6 months, he invested the same sum at 6% simple interest per annum. If the amount received from each investment at the end of a certain period is ₹4600, find the principal sum invested.

**हिन्दी:**  
एक व्यक्ति द्वारा एक निश्चित धनराशि 5% वार्षिक साधारण ब्याज पर निवेश की गई। 6 महीने बाद, उसने उतनी ही धनराशि 6% वार्षिक साधारण ब्याज पर निवेश की। यदि एक निश्चित समय के बाद प्रत्येक निवेश से प्राप्त मिश्रधन ₹4600 है, तो निवेश किया गया मूलधन ज्ञात कीजिए।

**Options:**  
a) ₹3200  
b) ₹3500  
c) ₹3600  
d) ₹3800  
e) None of these (₹4000)  

**Correct Answer:** **e) None of these (₹4000)**

---

#### 🎯 Kaushik Sir's Speed Approach (Equal Percentage Matching):
1. **Identify Fundamental Condition:**
   - Both investments have the same Principal $P$ and yield the same Amount ₹4600.
   - Therefore, the simple interest earned by both must be identical:
     $$\text{Rate}_1 \times T_1 = \text{Rate}_2 \times T_2$$
2. **Solve for Time Duration ($T$):**
   - Let first duration be $t$ years $\implies$ second duration is $\left(t - \frac{1}{2}\right)$ years.
   $$5 \times t = 6 \times \left(t - 0.5\right)$$
   $$5t = 6t - 3 \implies t = 3\text{ years}$$
3. **Find Effective Interest Percentage:**
   $$\text{Total Interest } \% = 5\% \times 3 = 15\%$$
   $$\text{Total Amount } \% = 100\% + 15\% = 115\%$$
4. **Calculate Principal ($P$):**
   $$115\% \text{ of } P = ₹4600$$
   $$P = \frac{4600}{1.15} = \mathbf{₹4,000}$$
   *(Since ₹4000 is not listed in options a–d, the correct choice is None of these).*

---

#### 📘 Standard Algebraic Approach:
- Let the principal be $P$.
- Amount from first investment:
  $$A_1 = P\left(1 + \frac{5t}{100}\right)$$
- Amount from second investment:
  $$A_2 = P\left(1 + \frac{6(t - 0.5)}{100}\right)$$
- Since $A_1 = A_2 = 4600$:
  $$1 + \frac{5t}{100} = 1 + \frac{6t - 3}{100} \implies 5t = 6t - 3 \implies t = 3\text{ years}$$
- Substitute $t = 3$ in $A_1 = 4600$:
  $$P\left(1 + \frac{15}{100}\right) = 4600 \implies 1.15P = 4600 \implies P = \frac{4600}{1.15} = \mathbf{₹4,000}$$

---

### 🔹 QUESTION 30
**Topic:** Split Sum with Variable Annual CI Rates | **Concept:** Successive Compounding Rates

**English:**  
Rahul invests ₹10,000 in Scheme A, which offers 15% simple interest per annum for 2 years, and ₹8,000 in Scheme B, which offers compound interest at 10% for the first year and 20% for the second year. Find the difference between the interests earned from Scheme A and Scheme B.

**हिन्दी:**  
राहुल योजना A में ₹10,000 निवेश करता है, जो 2 वर्षों के लिए 15% वार्षिक साधारण ब्याज देती है, और योजना B में ₹8,000 निवेश करता है, जो पहले वर्ष के लिए 10% और दूसरे वर्ष के लिए 20% की दर से चक्रवृद्धि ब्याज देती है। योजना A और योजना B से अर्जित ब्याजों के बीच का अंतर ज्ञात कीजिए।

**Options:**  
a) ₹360  
b) ₹400  
c) ₹440  
d) ₹480  
e) ₹520  

**Correct Answer:** **c) ₹440**

---

#### 🎯 Kaushik Sir's Speed Approach (Successive Rate Method):
1. **Interest from Scheme A (SI):**
   - Rate $= 15\%$, Time $= 2$ years $\implies$ Effective SI % $= 30\%$.
   $$SI_A = 30\% \text{ of } ₹10,000 = ₹3,000$$
2. **Interest from Scheme B (CI with $R_1 = 10\%, R_2 = 20\%$):**
   $$\text{Net CI } \% = 10 + 20 + \frac{10 \times 20}{100} = 30 + 2 = 32\%$$
   $$CI_B = 32\% \text{ of } ₹8,000 = 0.32 \times 8000 = ₹2,560$$
3. **Calculate Difference:**
   $$\Delta I = 3000 - 2560 = \mathbf{₹440}$$

---

#### 📘 Standard Algebraic Approach:
- Scheme A:
  $$SI_A = \frac{10000 \times 15 \times 2}{100} = ₹3,000$$
- Scheme B:
  $$A_B = 8000 \times \left(1 + \frac{10}{100}\right) \times \left(1 + \frac{20}{100}\right) = 8000 \times \frac{11}{10} \times \frac{6}{5} = 8000 \times \frac{66}{50} = 160 \times 66 = ₹10,560$$
  $$CI_B = A_B - P_B = 10,560 - 8,000 = ₹2,560$$
- Difference:
  $$SI_A - CI_B = 3000 - 2560 = \mathbf{₹440}$$

---

### 🔹 QUESTION 31
**Topic:** Hybrid Compounding Frequency | **Concept:** Alternating Annual and Semi-Annual Compounding

**English:**  
Rohan invested ₹12,500 for three years at 20% compound interest per annum. In the first year, interest is compounded annually; in the second year, it is compounded half-yearly; and in the third year, it is compounded annually. Find the total compound interest earned.

**हिन्दी:**  
रोहन ने 20% वार्षिक चक्रवृद्धि ब्याज की दर से 3 वर्षों के लिए ₹12,500 का निवेश किया। पहले वर्ष में ब्याज वार्षिक संयोजित होता है; दूसरे वर्ष में यह अर्धवार्षिक रूप से संयोजित होता है; और तीसरे वर्ष में यह पुनः वार्षिक रूप से संयोजित होता है। अर्जित कुल चक्रवृद्धि ब्याज ज्ञात कीजिए।

**Options:**  
a) ₹8,840  
b) ₹9,280  
c) ₹9,500  
d) ₹9,820  
e) ₹10,120  

**Correct Answer:** **b) ₹9,280**

---

#### 🎯 Kaushik Sir's Speed Approach (Chain Ratio Multipliers):
1. **Break Down Compounding Cycles:**
   - **Year 1 (Annual, 20%):** Multiplier $= 1 + \frac{1}{5} = \frac{6}{5}$.
   - **Year 2 (Half-yearly, 20% p.a. $\implies 10\%$ per cycle, 2 cycles):**
     $$\text{Multiplier} = \left(1 + \frac{1}{10}\right)^2 = \left(\frac{11}{10}\right)^2 = \frac{121}{100}$$
   - **Year 3 (Annual, 20%):** Multiplier $= \frac{6}{5}$.
2. **Combine Total Amount Multiplier:**
   $$\frac{A}{P} = \frac{6}{5} \times \frac{121}{100} \times \frac{6}{5} = \frac{36 \times 121}{2500} = \frac{4356}{2500} = \frac{1089}{625}$$
3. **Find CI Units:**
   $$P : A = 625 : 1089 \implies CI = 1089 - 625 = 464\text{ units}$$
4. **Scale to Real Value ($P = ₹12,500$):**
   $$625\text{ units} = ₹12,500 \implies 1\text{ unit} = \frac{12500}{625} = ₹20$$
   $$CI = 464 \times 20 = \mathbf{₹9,280}$$

---

#### 📘 Standard Algebraic Approach:
- Initial Principal $P_0 = ₹12,500$.
- Amount at end of Year 1:
  $$A_1 = 12500 \times 1.20 = ₹15,000$$
- Amount at end of Year 2 (Compounded half-yearly at $10\%$ per half-year):
  $$A_2 = 15000 \times (1.10)^2 = 15000 \times 1.21 = ₹18,150$$
- Amount at end of Year 3 (Compounded annually at $20\%$):
  $$A_3 = 18150 \times 1.20 = ₹21,780$$
- Total Compound Interest:
  $$CI = A_3 - P_0 = 21,780 - 12,500 = \mathbf{₹9,280}$$

---

### 🔹 QUESTION 32
**Topic:** Mid-Term Loan Addition | **Concept:** Forward Compounding Unwinding

**English:**  
Aman borrowed ₹10,000 from Rohit at 10% compound interest per annum. At the end of the first year, he borrowed an additional sum of ₹$X$ from Rohit at the same rate of compound interest. If at the end of the second year he cleared the entire debt by paying ₹16,500, find the value of $X$.

**हिन्दी:**  
अमन ने रोहित से 10% वार्षिक चक्रवृद्धि ब्याज पर ₹10,000 उधार लिए। पहले वर्ष के अंत में, उसने रोहित से समान चक्रवृद्धि ब्याज दर पर ₹$X$ की अतिरिक्त राशि उधार ली। यदि दूसरे वर्ष के अंत में उसने ₹16,500 का भुगतान करके पूरा ऋण चुका दिया, तो $X$ का मान ज्ञात कीजिए।

**Options:**  
a) ₹3000  
b) ₹3500  
c) ₹4000  
d) ₹4500  
e) ₹5000  

**Correct Answer:** **c) ₹4000**

---

#### 🎯 Kaushik Sir's Speed Approach (Backward Unwinding):
1. **Unwind from the Final Repayment of ₹16,500:**
   - At the end of Year 2, debt was multiplied by $1.10$ ($10\%$ CI):
     $$\text{Debt at start of Year 2} = \frac{16500}{1.10} = ₹15,000$$
2. **Calculate Accumulated Debt from Initial Loan at End of Year 1:**
   $$\text{Debt from ₹10,000} = 10000 \times 1.10 = ₹11,000$$
3. **Find Additional Borrowed Sum ($X$):**
   $$X = \text{Total debt at start of Year 2} - \text{Debt from first loan}$$
   $$X = 15,000 - 11,000 = \mathbf{₹4,000}$$

---

#### 📘 Standard Algebraic Approach:
- End of Year 1 debt before borrowing $X$:
  $$D_1 = 10000\left(1 + \frac{10}{100}\right) = 11,000$$
- Total debt at beginning of Year 2:
  $$P_2 = 11,000 + X$$
- Debt accumulated by end of Year 2:
  $$D_2 = (11,000 + X)\left(1 + \frac{10}{100}\right) = 1.10(11000 + X) = 12100 + 1.10X$$
- Given $D_2 = 16,500$:
  $$12100 + 1.10X = 16500 \implies 1.10X = 4400 \implies X = \frac{4400}{1.10} = \mathbf{₹4,000}$$

---

### 🔹 QUESTION 33
**Topic:** High Rate Half-Yearly Compounding & SI Matching | **Concept:** Fractional Balancing & Rate Equation

**English:**  
Abhay invested a certain sum at 50% compound interest per annum compounded half-yearly for 1 year and received ₹1350 as interest. If the same sum is invested at $(5 + R)\%$ simple interest per annum for 2 years, the interest received is ₹1440. Find the value of $R$.

**हिन्दी:**  
अभय ने एक निश्चित धनराशि को 50% वार्षिक चक्रवृद्धि ब्याज पर 1 वर्ष के लिए अर्धवार्षिक रूप से संयोजित करके निवेश किया और ब्याज के रूप में ₹1350 प्राप्त किए। यदि वही धनराशि $(5 + R)\%$ वार्षिक साधारण ब्याज पर 2 वर्षों के लिए निवेश की जाए, तो प्राप्त ब्याज ₹1440 है। $R$ का मान ज्ञात कीजिए।

**Options:**  
a) 15  
b) 20  
c) 22.5  
d) 25  
e) 30  

**Correct Answer:** **d) 25**

---

#### 🎯 Kaushik Sir's Speed Approach:
1. **Decode CI Scheme (Half-Yearly Compounding):**
   - Annual Rate $= 50\% \implies$ Half-year Rate $= 25\% = \frac{1}{4}$.
   - Time $= 1$ year $= 2$ half-years.
   $$P : A = 4^2 : 5^2 = 16 : 25 \implies CI = 25 - 16 = 9\text{ units}$$
2. **Find Principal ($P$):**
   $$9\text{ units} = ₹1350 \implies 1\text{ unit} = ₹150$$
   $$P = 16 \times 150 = ₹2,400$$
3. **Solve for $R$ in SI Scheme:**
   - $SI = ₹1440$ on ₹2400 for 2 years.
   - Total SI % $= \frac{1440}{2400} \times 100\% = 60\%$.
   - Annual SI Rate $= \frac{60\%}{2} = 30\%$.
   $$5 + R = 30 \implies R = 30 - 5 = \mathbf{25}$$

---

#### 📘 Standard Algebraic Approach:
- In CI: Rate per half-year $r = 25\%$, Number of periods $n = 2$.
  $$CI = P\left[\left(1 + \frac{25}{100}\right)^2 - 1\right] = P\left[\frac{25}{16} - 1\right] = \frac{9}{16}P$$
  $$\frac{9}{16}P = 1350 \implies P = \frac{1350 \times 16}{9} = 150 \times 16 = 2400$$
- In SI:
  $$SI = \frac{P \times (5 + R) \times 2}{100} \implies 1440 = \frac{2400 \times (5 + R) \times 2}{100}$$
  $$1440 = 48(5 + R) \implies 5 + R = \frac{1440}{48} = 30 \implies R = \mathbf{25}$$

---

### 🔹 QUESTION 34
**Topic:** Partial Borrowing Reinvestment Deficit | **Concept:** Base Ratio Multiplier Matching

**English:**  
A man borrowed ₹20,000 from his friend at 12% simple interest per annum for 3 years. He invested 75% of this borrowed money in a scheme offering $R\%$ compound interest per annum for 3 years. If he had to pay ₹1280 more to clear his loan than the total amount he received from the scheme, find $R$.

**हिन्दी:**  
एक व्यक्ति ने अपने मित्र से 12% वार्षिक साधारण ब्याज पर 3 वर्षों के लिए ₹20,000 उधार लिए। उसने इस उधार ली गई राशि का 75% भाग $R\%$ वार्षिक चक्रवृद्धि ब्याज की योजना में 3 वर्षों के लिए निवेश किया। यदि ऋण चुकाने के लिए उसे योजना से प्राप्त कुल मिश्रधन से ₹1280 अधिक का भुगतान करना पड़ा, तो $R$ का मान ज्ञात कीजिए।

**Options:**  
a) 15%  
b) 18%  
c) 20%  
d) 25%  
e) 12.5%  

**Correct Answer:** **c) 20%**

---

#### 🎯 Kaushik Sir's Speed Approach (Ratio Base Inspection):
1. **Total Repayment on Borrowed Loan (SI):**
   - Rate $= 12\%$, Time $= 3$ years $\implies SI = 36\%$.
   $$\text{Total Loan Repayment} = 20,000 \times 1.36 = ₹27,200$$
2. **Find Amount Received from CI Scheme:**
   - Deficit $= ₹1280$.
   $$\text{Amount Received } (A_{\text{CI}}) = 27,200 - 1280 = ₹25,920$$
3. **Principal Invested in CI Scheme:**
   $$P_{\text{CI}} = 75\% \text{ of } 20,000 = ₹15,000$$
4. **Inspect Ratio for 3 Years:**
   $$\frac{P_{\text{CI}}}{A_{\text{CI}}} = \frac{15000}{25920} = \frac{1500}{2592} = \frac{125}{216} = \left(\frac{5}{6}\right)^3$$
   - Since the cube base is $\frac{5}{6}$:
     $$R = \frac{6 - 5}{5} \times 100\% = \frac{1}{5} \times 100\% = \mathbf{20\%}$$

---

#### 📘 Standard Algebraic Approach:
- Loan repayment to friend:
  $$A_{\text{loan}} = 20000 + \frac{20000 \times 12 \times 3}{100} = 20000 + 7200 = 27,200$$
- Principal invested in CI scheme $P' = 0.75 \times 20000 = 15,000$.
- Amount received from CI scheme $A' = A_{\text{loan}} - 1280 = 27200 - 1280 = 25,920$.
- Using CI formula:
  $$A' = P'\left(1 + \frac{R}{100}\right)^3 \implies 25920 = 15000\left(1 + \frac{R}{100}\right)^3$$
  $$\left(1 + \frac{R}{100}\right)^3 = \frac{25920}{15000} = \frac{216}{125} = \left(\frac{6}{5}\right)^3$$
  $$1 + \frac{R}{100} = \frac{6}{5} \implies \frac{R}{100} = \frac{1}{5} \implies R = \mathbf{20\%}$$

---

### 🔹 QUESTION 35
**Topic:** Successive Varied Compounding Rates | **Concept:** Step-by-Step Principal Roll-Forward

**English:**  
A certain amount is invested at simple interest for 3 years at 8% per annum and yields ₹600 as interest. If the same amount is invested at compound interest for 2 years such that the rate of interest for the first year is 12% and for the second year is $R\%$, and the total interest earned is ₹720, find $R$.

**हिन्दी:**  
एक निश्चित धनराशि 8% वार्षिक साधारण ब्याज की दर से 3 वर्षों के लिए निवेश की जाती है और ₹600 ब्याज देती है। यदि वही धनराशि 2 वर्षों के लिए चक्रवृद्धि ब्याज पर इस प्रकार निवेश की जाए कि पहले वर्ष ब्याज दर 12% और दूसरे वर्ष $R\%$ हो, तथा अर्जित कुल चक्रवृद्धि ब्याज ₹720 हो, तो $R$ का मान ज्ञात कीजिए।

**Options:**  
a) 10%  
b) 12%  
c) 15%  
d) 18%  
e) 20%  

**Correct Answer:** **c) 15%**

---

#### 🎯 Kaushik Sir's Speed Approach (Step-by-Step Roll-Forward):
1. **Find Principal ($P$) from SI:**
   - Effective SI % $= 8\% \times 3 = 24\%$.
   $$24\% \text{ of } P = ₹600 \implies P = \frac{600}{0.24} = ₹2,500$$
2. **Year 1 CI at 12%:**
   $$I_1 = 12\% \text{ of } 2500 = ₹300$$
   $$\text{Principal for Year 2} = 2500 + 300 = ₹2,800$$
3. **Year 2 CI Alone:**
   $$\text{Total CI} = ₹720 \implies I_2 = 720 - 300 = ₹420$$
4. **Find $R\%$:**
   $$R = \frac{I_2}{\text{Principal for Year 2}} \times 100\% = \frac{420}{2800} \times 100\% = \frac{42}{2.8}\% = \mathbf{15\%}$$

---

#### 📘 Standard Algebraic Approach:
- Principal $P$:
  $$600 = \frac{P \times 8 \times 3}{100} = \frac{24P}{100} \implies P = \frac{60000}{24} = 2500$$
- Compound interest for 2 years with rates $12\%$ and $R\%$:
  $$A = 2500 \times \left(1 + \frac{12}{100}\right) \times \left(1 + \frac{R}{100}\right) = 2500 \times 1.12 \times \left(1 + \frac{R}{100}\right) = 2800\left(1 + \frac{R}{100}\right)$$
  $$CI = A - P = 2800 + 28R - 2500 = 300 + 28R$$
- Given $CI = 720$:
  $$300 + 28R = 720 \implies 28R = 420 \implies R = \frac{420}{28} = \mathbf{15\%}$$

---

### 🔹 QUESTION 36
**Topic:** Ratio of 3-Year to 2-Year Differences | **Concept:** Master Formula $\frac{D_3}{D_2} = \frac{300 + R}{100}$

**English:**  
A person lent a certain sum at simple interest and compound interest for 3 years and 2 years respectively. If the ratio of the difference between CI and SI for 3 years to that for 2 years is $13 : 4$, find the annual rate of interest.

**हिन्दी:**  
एक व्यक्ति ने एक निश्चित धनराशि साधारण ब्याज और चक्रवृद्धि ब्याज पर क्रमशः 3 वर्षों और 2 वर्षों के लिए उधार दी। यदि 3 वर्षों के CI और SI के अंतर तथा 2 वर्षों के CI और SI के अंतर का अनुपात $13 : 4$ है, तो वार्षिक ब्याज दर ज्ञात कीजिए।

**Options:**  
a) 15%  
b) 20%  
c) 22.5%  
d) 25%  
e) 30%  

**Correct Answer:** **d) 25%**

---

#### 🎯 Kaushik Sir's Speed Approach (2-Second Direct Ratio Strike):
1. **Master Difference Ratio Theorem:**
   $$\frac{D_3}{D_2} = \frac{CI_3 - SI_3}{CI_2 - SI_2} = 3 + \frac{R}{100} = \frac{300 + R}{100}$$
2. **Substitute Given Ratio:**
   $$\frac{13}{4} = 3.25$$
3. **Direct Calculation:**
   $$3 + \frac{R}{100} = 3.25$$
   $$\frac{R}{100} = 0.25 \implies R = \mathbf{25\%}$$

---

#### 📘 Standard Algebraic Approach:
- Recall the individual difference formulas:
  $$D_2 = P\left(\frac{R}{100}\right)^2$$
  $$D_3 = P\left(\frac{R}{100}\right)^2\left(3 + \frac{R}{100}\right)$$
- Dividing $D_3$ by $D_2$:
  $$\frac{D_3}{D_2} = \frac{P\left(\frac{R}{100}\right)^2\left(3 + \frac{R}{100}\right)}{P\left(\frac{R}{100}\right)^2} = 3 + \frac{R}{100} = \frac{300 + R}{100}$$
- Given $\frac{D_3}{D_2} = \frac{13}{4}$:
  $$\frac{300 + R}{100} = \frac{13}{4}$$
  $$4(300 + R) = 1300$$
  $$1200 + 4R = 1300 \implies 4R = 100 \implies R = \mathbf{25\%}$$

# 3. MASTER ANSWER KEY & QUICK REVISION MATRIX

| Q# | Topic / Core Scenario | Key Given Values | Kaushik Sir Speed Shortcut | Correct Option & Value |
| :---: | :--- | :--- | :--- | :---: |
| **Q01** | SI Times to Half-Yearly CI | $17\times$ in 40 yrs; ₹75k at $r\%$ half-yearly | $r = \frac{16}{40} = 40\% \implies 20\% \times 2 \text{ cycles} = 44\%$ | **d) ₹33,000** |
| **Q02** | CI Duration to SI Rate | ₹6250 to ₹10,800 at 20% CI; $1.75\times$ SI | $\frac{125}{216} = (5/6)^3 \implies T=3\text{y}; R = \frac{75\%}{3}$ | **c) 25%** |
| **Q03** | 2-Yr CI Ratio to SI | ₹3200 to ₹5000 in 2y; ₹2400 at $(R-10)\%$ | $\sqrt{16/25} = 4/5 \implies R=25\%; SI = 75\% \text{ of } 2400$ | **c) ₹1800** |
| **Q04** | CI Power Scale to SI | ₹12k, CI ₹6750 at 25%; ₹8k at 12.5% for $n^3$y | $16:25 = (4/5)^2 \implies n=2; T=8\text{y} \implies 100\%$ | **c) ₹8000** |
| **Q05** | SI Period to Scaled CI | $5P \to 8P$ in $t$y at 12%; 20% CI for $(t-3)$y | $60\%/12\% \implies t=5\text{y}; 44\%(5P) = 1760 \implies 5P=4000$ | **d) ₹800** |
| **Q06** | 3rd Year CI Alone | Shivam $X$ at 25% for 3y; Yr 3 CI = ₹31,250 | Base $a^3 = 64$; Yr 3 units $= (a+1)^2 = 25 \implies 25u = 31250$ | **d) ₹80,000** |
| **Q07** | Consecutive Year CI Diff | ₹25k at 20% for 3y; Diff between Yr 3 & Yr 2 | Direct diff $= (a+1) = 6\text{ units}; 125u = 25000 \implies 1u=200$ | **c) ₹1200** |
| **Q08** | Inverse Year Diff | Diff between Yr 3 & Yr 2 CI at 10% is ₹132 | $(a+1) = 11\text{ units} = 132 \implies 1u=12; P=1000u$ | **c) ₹12,000** |
| **Q09** | SI-CI Rate Extraction | 5y SI = ₹15k, 2y CI = ₹6750 | $1\text{y SI} = 3000; \text{Extra in CI} = 750 \implies R = 25\%$ | **c) ₹12,000** |
| **Q10** | 2-Year SI-CI Diff | Diff on ₹6400 for 2y is ₹100 | $D_2 = P(R/100)^2 \implies 100/6400 = (1/8)^2 \implies R=12.5\%$ | **c) 12.5%** |
| **Q11** | 3-Year SI-CI Diff | Diff for 3y at 20% is ₹640 | $D_3 = (3a+1) = 16\text{ units} = 640 \implies P = 125u$ | **b) ₹5000** |
| **Q12** | CI Interest Reinvested | $P$ at 10% CI 2y $\to$ SI at 15% 4y; Tot = ₹3360 | $CI = 21\%P; SI = 60\%(21\%) = 12.6\% \implies 33.6\%P = 3360$ | **c) ₹10,000** |
| **Q13** | SI Amount Reinvested | $(x+10k)$ SI 25% 4y $\to$ 60% at 20% CI 2y | $A_1 = 2S; P_B = 1.2S; CI_B = 44\%(1.2S) = 0.528S = 15840$ | **c) ₹20,000** |
| **Q14** | Partial SI Reinvested | $x$ SI 20% 4y $\to$ 75% at 12.5% CI 2y | $SI_A = 0.8x; P_B = 0.6x; CI_B = \frac{17}{64}(0.6x) = 2550$ | **c) ₹16,000** |
| **Q15** | Split Sum & Interest | $6x$ split: 50% SI $\to$ Half Int + Rest at 25% CI | $P_2 = 4.2x; A_2 = 4.2x(25/16) = 10500 \implies 6x = 9600$ | **b) ₹13,200** |
| **Q16** | Reinvestment + Initial | ₹12k split: $x$ at 12.5% SI 4y $\to$ Reinvest all | $P_2 = 12000 + 0.5x; CI_2 = \frac{9}{16}P_2 = 9000 \implies P_2 = 16k$ | **c) ₹8000** |
| **Q17** | Backward Rate Finding | ₹18k at $r\%$ CI 2y $\to$ 8% SI 5y = ₹39,375 | $A_2 = 1.4A_1 = 39375 \implies A_1 = 28125; 18k:28125 = 16:25$ | **d) 25%** |
| **Q18** | Dual Equal Investment | Equal $P$: A (20% SI 3y), B (10% CI 3y) | $\Delta \% = 60\% - 33.1\% = 26.9\% = 10760 \implies 2P = 80,000$ | **d) ₹80,000** |
| **Q19** | Unequal Dual Schemes | $P_B = 2P_A$; A (12.5% SI 3y), B (12.5% CI 3y) | Unit tree: $CI_B(217u) - SI_A(96u) = 121u = 6050 \implies P_A = 256u$ | **c) ₹12,800** |
| **Q20** | Mixed Portfolio Split | ₹6000 split: 12.5% SI 4y & 20% CI 2y | Alligation: SI 50%, CI 44%, Mean 46.4% $\implies 2 : 3$ | **d) ₹2400** |
| **Q21** | Unequal Dual Sums | $x$ at 20% CI 2y & $(x+2500)$ at 15% SI 3y | $0.44x + 0.45x + 1125 = 5575 \implies 0.89x = 4450 \implies x=5k$ | **c) ₹7500** |
| **Q22** | Rate Determination | ₹50k at $x\%$ SI 2y & ₹80k at $(x+8)\%$ CI 1y | Tot Int $= 28000 = 1000x + 800(x+8) \implies x=12\%; CI=20\%$ | **c) 20%** |
| **Q23** | Allocation with Gap | ₹20k split: 20% CI 2y & 15% SI 2y; Diff ₹1400 | $0.44y - 0.30(20000-y) = 1400 \implies 0.74y = 7400 \implies y=10k$ | **b) ₹10,000** |
| **Q24** | Multi-Variable Match | $(X-1500)$ SI 15% 4y = 7500 $\to (X-6000)$ CI 20% | $X = 14000 \implies P_2 = 8000, A_2 = 13824 \implies (5/6)^3$ | **c) 3 years** |
| **Q25** | Arbitrage Loan Profit | Borrow $(8x+2000)$ at 15%, lend at 20% | Spread $5\% = x - 200 \implies x=500; P=6000; CI = \frac{9}{16}(6000)$ | **d) ₹3375** |
| **Q26** | Equal SI Matching | Rita $(x+3000)$ at 24% $n$y; Sita $x$ at 18% $2n$y | $24(x+3000) = 36x \implies 2x+6000 = 3x \implies x=6000$ | **c) ₹6000** |
| **Q27** | Quadratic SI Rate | ₹320 at $p\%$ for $(p+5)$y = ₹480 $\to$ 25% CI 2y | $p(p+5)=150 \implies p=10; A_B=800; A_C=1250; \Delta A = 450$ | **b) ₹450** |
| **Q28** | SI to CI Multiplier | $x\%$ SI 4y = 8000 $\to 2x\%$ CI 2y = 8640 | Yr 1 Int $= 4000; \text{Extra } 640 \implies 2x=16\%, x=8\%, P=25k$ | **b) ₹25,000** |
| **Q29** | Staggered SI Equal Amt | 5% for $t$y & 6% for $(t-0.5)$y; Amount ₹4600 | $5t = 6t - 3 \implies t=3\text{y}; P = 4600 / 1.15 = ₹4,000$ | **e) None (₹4000)** |
| **Q30** | Split Sum Variable Rates | ₹10k SI 15% 2y & ₹8k CI (10%, 20%) | $SI = 3000; CI = 32\%(8000) = 2560 \implies \Delta = 440$ | **c) ₹440** |
| **Q31** | Hybrid Compounding | ₹12,500 at 20%: Annual $\to$ Half-Yr $\to$ Annual | $\frac{6}{5} \times \frac{121}{100} \times \frac{6}{5} = \frac{1089}{625} \implies CI = 464 \times 20$ | **b) ₹9,280** |
| **Q32** | Mid-Term Loan Addition | ₹10k at 10% CI; borrow $X$ at Yr 1; pay ₹16.5k | Unwind: $16500/1.1 = 15000; 10000(1.1) = 11000 \implies X=4000$ | **c) ₹4000** |
| **Q33** | Half-Yearly CI to SI | 50% CI half-yr 1y = 1350 $\to (5+R)\%$ SI 2y = 1440 | $9u = 1350 \implies P=2400; 48(5+R) = 1440 \implies R=25$ | **d) 25** |
| **Q34** | Borrow Reinvestment Deficit | Borrow ₹20k at 12% 3y; 75% at $R\%$ CI 3y | Loan $= 27200; A_{\text{CI}} = 25920; 15k:25920 = 125:216 \implies 20\%$ | **c) 20%** |
| **Q35** | Roll-Forward Variable CI | 8% SI 3y = 600 $\to$ CI 2y (Yr 1: 12%, Yr 2: $R\%$) | $P=2500; I_1=300; A_1=2800; I_2=420 \implies R=420/2800=15\%$ | **c) 15%** |
| **Q36** | Ratio of Differences | Ratio $(CI_3 - SI_3) / (CI_2 - SI_2) = 13 : 4$ | $\frac{300+R}{100} = 3.25 \implies R = 25\%$ | **d) 25%** |

---

# 4. SPEED DRILL & EXAM CHEATSHEET

### ⚡ 10 Golden Speed Mantras for Bank Exams:
1. **The Linear Nature of SI:**  
   $$\text{Effective SI } \% = R \times T\%$$
   No powers, no compound steps. If time doubles, interest doubles. If principal splits, interest splits proportionally.

2. **The 2-Second Ratio Strike for Difference Ratio:**  
   $$\frac{D_3}{D_2} = 3 + \frac{R}{100}$$
   Take the ratio, subtract 3, multiply by 100. That's your rate!  
   *Example:* $\frac{13}{4} = 3.25 \implies 3.25 - 3 = 0.25 \implies 25\%$.

3. **Consecutive Year CI Gap is $(a+1)$ Units:**  
   When rate is $\frac{1}{a}$ and $P = a^3$:
   - $\text{Year 1 CI} = a^2$
   - $\text{Year 2 CI} = a^2 + a$
   - $\text{Year 3 CI} = (a+1)^2 = a^2 + 2a + 1$
   - **Difference between 3rd Year CI and 2nd Year CI is always $(a+1)$ units!**

4. **Tree Method Unit Assignment:**
   - For 2 years at $\frac{1}{a}$: Assume $P = a^2$.
   - For 3 years at $\frac{1}{a}$: Assume $P = a^3$.
   - For 3 years: $SI_3 = 3a^2$, $CI_3 = 3a^2 + 3a + 1$, $D_3 = 3a + 1$.

5. **The 2-Year Difference Direct Formula:**  
   $$D_2 = P\left(\frac{R}{100}\right)^2 = \frac{SI \times R}{200}$$
   If given $SI$ for 2 years and difference $D_2$:
   $$R = \frac{200 \times D_2}{SI_2}$$

6. **Alligation on Mixed Interest Rates:**  
   When a lump sum $P$ is divided into two schemes yielding overall rate $R_m$:
   $$\frac{P_1}{P_2} = \frac{|R_2 - R_m|}{|R_1 - R_m|}$$
   Always verify that $R_1, R_2, R_m$ are all evaluated over the same time horizon or converted to total effective percentage!

7. **Equal Interval Multiplier Rule (GP of Amounts):**  
   If an amount grows from $P$ to $A_1$ in $T$ years, and to $A_2$ in $2T$ years:
   $$P = \frac{A_1^2}{A_2}, \quad A_3 = \frac{A_2^2}{A_1}$$

8. **Compounding Frequency Mental Adjustment:**  
   - Half-Yearly: Rate $\to \frac{R}{2}$, Time $\to 2T$.
   - Quarterly: Rate $\to \frac{R}{4}$, Time $\to 4T$.
   - 8-Monthly: Rate $\to \frac{R \times 8}{12} = \frac{2R}{3}$, Cycles $\to \frac{12T}{8}$.

9. **Successive Compounding of Dissimilar Rates:**  
   For two consecutive years with rates $R_1\%$ and $R_2\%$:
   $$\text{Net CI } \% = R_1 + R_2 + \frac{R_1 R_2}{100}$$
   *Example:* $10\%$ and $20\% \implies 10 + 20 + 2 = 32\%$.

10. **Backward Unwinding in Loan Repayments:**  
    When a debt is cleared after additions/deductions:  
    Start from the final repayment and divide by $(1 + R\%)$ step-by-step backwards rather than setting up complex multi-degree polynomials.
