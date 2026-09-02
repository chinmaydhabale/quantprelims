# 📊 AVERAGE & AGES (औसत एवं आयु संबंधी प्रश्न) — ONE SHOT MASTER NOTES

> **Source:** Kaushik Mohanty Sir (Career Definer / Ex-Banker RRB)  
> **Target Exams:** IBPS PO/Clerk, SBI PO/Clerk, RRB PO/Clerk, RBI Assistant, LIC AAO, NIACL, SSC CGL & All Banking/Insurance Prelims + Mains  
> **Note Architecture:** Dual-Approach Pedagogy (🎯 Kaushik Sir's Exam Shortcut / Deviation / Ratio Method + 📘 Standard Algebraic / Detailed Method) with Bilingual Statements (Hindi + English).

---

## 📑 TABLE OF CONTENTS
1. [Master Formula Sheet & Core Theory](#1-master-formula-sheet--core-theory)
   - 1.1 Fundamentals of Average & Total Sum
   - 1.2 The Net Deviation Method ($\sum \Delta = 0$) & Assumed Mean
   - 1.3 Arithmetic Progression (AP) & Consecutive Number Properties
   - 1.4 Group Dynamics: Inclusion, Exclusion & Replacement Shortcuts
   - 1.5 Cricket Averages (Batting & Bowling Average Nuances)
   - 1.6 Weighted Average & Alligation Rule in Averages
   - 1.7 Ages Concepts: Invariant Difference, Ratio Scaling & Cross-Multiplication
   - 1.8 Quick Revision Summary Table
2. [Complete Question Bank — All 36 Questions Solved](#2-complete-question-bank--all-36-questions-solved)
   - **Set 1: Basic & Deviation-Based Averages (Q01 – Q09)**
   - **Set 2: Weighted Average, Replacement & Alligation (Q10 – Q12)**
   - **Set 3: Consecutive Numbers & AP Series (Q13 – Q18)**
   - **Set 4: Advanced Averages, Income/Savings & Heights (Q19 – Q22)**
   - **Set 5: Ages — Basic Ratios, Multi-person & Invariant Difference (Q23 – Q29)**
   - **Set 6: Ages — Complex Systems, Birth Timelines & Non-linear Relations (Q30 – Q36)**
3. [Speed Drill & Exam Cheatsheet](#3-speed-drill--exam-cheatsheet)

---

# 1. MASTER FORMULA SHEET & CORE THEORY

## 1.1 Fundamentals of Average & Total Sum
$$\text{Average } (\bar{X}) = \frac{\text{Sum of all Observations } (\sum X)}{\text{Total Number of Observations } (n)}$$
$$\text{Sum of Observations } (\sum X) = \text{Average } (\bar{X}) \times \text{Number of Observations } (n)$$

### Core Properties of Average:
1. **Linear Shift ($+k$ or $-k$):** If every observation is increased or decreased by $k$, the new average increases or decreases by $k$.
   $$\text{New Average} = \bar{X}_{\text{old}} \pm k$$
2. **Scaling ($\times k$ or $\div k$):** If every observation is multiplied or divided by $k$, the new average is multiplied or divided by $k$.
   $$\text{New Average} = \bar{X}_{\text{old}} \times k \quad \text{or} \quad \frac{\bar{X}_{\text{old}}}{k}$$
3. **Internal Balancing Property:** Average is always bounded strictly between the minimum and maximum observation:
   $$X_{\min} \le \bar{X} \le X_{\max}$$

---

## 1.2 The Net Deviation Method ($\sum \Delta = 0$) & Assumed Mean
Instead of calculating large multi-digit sums, Kaushik Sir heavily emphasizes the **Deviation Method**:
$$\text{Deviation } (\Delta_i) = X_i - \text{Assumed Mean } (A)$$
$$\text{Actual Average} = A + \frac{\sum \Delta_i}{n}$$
- **Golden Rule:** The algebraic sum of deviations of all observations about their true average is **always ZERO**:
  $$\sum_{i=1}^n (X_i - \bar{X}) = 0$$
- If a subset of items has a net deviation of $+D$, the remaining items must have a net deviation of $-D$ to balance the system to zero.

---

## 1.3 Arithmetic Progression (AP) & Consecutive Number Properties
When terms are in Arithmetic Progression (common difference $d$ is constant):
$$\text{Average} = \frac{\text{First Term } (T_1) + \text{Last Term } (T_n)}{2} = \frac{T_2 + T_{n-1}}{2} = \dots$$

### Middle Term Properties:
- **Odd number of terms ($n = 3, 5, 7, \dots$):**
  $$\text{Average} = \text{Middle Term } \left(T_{\frac{n+1}{2}}\right)$$
  *Example:* For 5 consecutive even numbers $a, a+2, a+4, a+6, a+8$, Average $= a+4$ (3rd term).
- **Even number of terms ($n = 4, 6, 8, \dots$):**
  $$\text{Average} = \frac{\text{Sum of the Two Middle Terms}}{2}$$
  *Example:* For 6 consecutive odd numbers $b, b+2, b+4, b+6, b+8, b+10$, Average $= \frac{(b+4) + (b+6)}{2} = b+5$.

### Types of Consecutive Series:
| Series Type | Common Difference ($d$) | Formula for $k^{\text{th}}$ term |
| :--- | :---: | :--- |
| **Consecutive Natural Numbers** | $1$ | $T_k = a + (k-1)$ |
| **Consecutive Even Numbers** | $2$ | $T_k = a + 2(k-1)$ |
| **Consecutive Odd Numbers** | $2$ | $T_k = a + 2(k-1)$ |
| **Consecutive Multiples of $m$** | $m$ | $T_k = a + m(k-1)$ |

---

## 1.4 Group Dynamics: Inclusion, Exclusion & Replacement Shortcuts

### 1. Inclusion (New Member Joins Group):
$$\text{Value of New Member} = \text{Old Average} + (\text{New Total Count} \times \Delta\text{Avg})$$
- If average increases: $\Delta\text{Avg} > 0$ (New member brought extra value).
- If average decreases: $\Delta\text{Avg} < 0$ (New member fell short of old average).

### 2. Exclusion (Member Leaves Group):
$$\text{Value of Leaving Member} = \text{Old Average} - (\text{New Total Count} \times \Delta\text{Avg})$$

### 3. Replacement (1 or more replaced, count $n$ stays constant):
$$\text{Sum of New Members} - \text{Sum of Replaced Members} = n \times \Delta\text{Avg}$$
$$\text{Sum of New} = \text{Sum of Old} + n \times (\text{New Avg} - \text{Old Avg})$$

---

## 1.5 Cricket Averages
### Batting Average:
$$\text{Batting Average} = \frac{\text{Total Runs Scored}}{\text{Total Number of Innings in which Batsman got OUT}}$$
*(In standard aptitude problems unless not-outs are specified, Innings $=$ Dismissals).*

### Bowling Average:
$$\text{Bowling Average} = \frac{\text{Total Runs Conceded}}{\text{Total Wickets Taken}}$$
> ⚠️ **CRITICAL EXAM TRAP ON BOWLING AVERAGE:**  
> A bowler's performance **improves** when bowling average **decreases** (giving fewer runs per wicket).  
> If bowler's average *improves by 0.5 runs/wicket*, New Average = $\text{Old Average} - 0.5$.

---

## 1.6 Weighted Average & Alligation Rule in Averages
When two groups of sizes $n_1, n_2$ with averages $A_1, A_2$ are combined:
$$A_{\text{avg}} = \frac{n_1 A_1 + n_2 A_2}{n_1 + n_2}$$
By the Alligation Rule:
$$\frac{n_1}{n_2} = \frac{|A_2 - A_{\text{avg}}|}{|A_{\text{avg}} - A_1|}$$

```
    Group 1 Avg (A1)           Group 2 Avg (A2)
                 \               /
                  \             /
                Combined Avg (A_avg)
                  /             \
                 /               \
            |A2 - A_avg|  :  |A_avg - A1|
                  = n1    :    = n2
```

---

## 1.7 Ages Concepts: Invariant Difference & Ratio Scaling

### 1. The Invariant Difference Rule (अपरिवर्तनीय आयु अंतर):
The difference between the ages of two persons **never changes** with time:
$$(A_{\text{future}} - B_{\text{future}}) = (A_{\text{present}} - B_{\text{present}}) = (A_{\text{past}} - B_{\text{past}})$$

### 2. Ratio Balancing Method:
If the ratio of ages of $A$ and $B$ is given at two different times $T_1$ and $T_2$:
- **Step 1:** Calculate ratio difference in both ratios: $d_1 = |a_1 - b_1|$ and $d_2 = |a_2 - b_2|$.
- **Step 2:** Equalize the ratio differences by multiplying Ratio 1 by $d_2$ and Ratio 2 by $d_1$.
- **Step 3:** The vertical unit change $\Delta u$ now directly represents the elapsed time $\Delta T$ years:
  $$1\text{ ratio unit} = \frac{\Delta T}{\Delta u}\text{ years}$$

### 3. Cross-Multiplication Method:
If present ratio is $a : b$ and after $T$ years ratio becomes $c : d$:
$$\frac{ax + T}{bx + T} = \frac{c}{d} \implies x = \frac{T(c - d)}{ad - bc}$$

---

## 1.8 Quick Revision Summary Table

| Concept | Direct Formula / Rule | Kaushik Sir's Mental Trick |
| :--- | :--- | :--- |
| **Assumed Mean** | $\bar{X} = A + \frac{\sum \Delta_i}{n}$ | Balance $+ \Delta$ and $- \Delta$ to 0 |
| **Middle Term of AP** | $\text{Avg} = T_{\text{middle}}$ or $\frac{T_1+T_n}{2}$ | Symmetry around center |
| **Replacement** | $\text{New} - \text{Old} = n \times \Delta\text{Avg}$ | Count $n$ remains unchanged |
| **Inclusion** | $\text{New} = \text{Old Avg} + n_{\text{new}} \times \Delta\text{Avg}$ | Distribute surplus across $(n+1)$ |
| **Exclusion** | $\text{Left} = \text{Old Avg} - n_{\text{new}} \times \Delta\text{Avg}$ | Pull deficit from remaining $(n-1)$ |
| **Age Difference** | $\Delta \text{Age} = \text{Constant}$ | Equalize ratio differences across timeline |
| **Alligation in Avg** | $\frac{n_1}{n_2} = \frac{A_2 - A_{\text{avg}}}{A_{\text{avg}} - A_1}$ | Cross difference equals quantity ratio |

---


# 2. COMPLETE QUESTION BANK — ALL 36 QUESTIONS SOLVED

---

## 📌 SET 1: BASIC & DEVIATION-BASED AVERAGES (Q01 – Q09)

---

### 🔹 QUESTION 01
**Topic:** Replacement in Groups | **Concept:** Net Increase in Total Sum

**English:**  
The average weight of 10 people increases by 2 kg when two people weighing 62 kg and 68 kg are replaced by two new people. If the ratio of the weights of the two new people is $3 : 2$, find the weight of the heavier new person.

**हिन्दी:**  
10 व्यक्तियों का औसत वजन 2 kg बढ़ जाता है जब 62 kg और 68 kg वजन वाले दो व्यक्तियों को दो नए व्यक्तियों द्वारा बदल दिया जाता है। यदि दो नए व्यक्तियों के वजन का अनुपात $3 : 2$ है, तो भारी नए व्यक्ति का वजन ज्ञात कीजिए।

**Options:**  
a) 75 kg  
b) 80 kg  
c) 90 kg  
d) 85 kg  
e) None of these  

**Correct Answer:** **c) 90 kg**

---

#### 🎯 Kaushik Sir's Approach (Replacement Shortcut):
1. **Total Increase in Group Weight:**
   $$\text{Total Increase} = \text{Total Members} \times \text{Increase in Average} = 10 \times 2 = 20\text{ kg}$$
2. **Sum of Weights of Leaving Members:**
   $$\text{Sum}_{\text{old}} = 62 + 68 = 130\text{ kg}$$
3. **Sum of Weights of 2 New Incoming Members:**
   $$\text{Sum}_{\text{new}} = \text{Sum}_{\text{old}} + \text{Total Increase} = 130 + 20 = 150\text{ kg}$$
4. **Dividing into Given Ratio ($3 : 2$):**
   $$\text{Total Ratio Units} = 3 + 2 = 5\text{ units}$$
   $$5\text{ units} = 150\text{ kg} \implies 1\text{ unit} = 30\text{ kg}$$
   $$\text{Weight of Heavier Person} = 3 \times 30 = \mathbf{90\text{ kg}}$$

---

#### 📘 Basic / Algebraic Approach:
- Let the initial average weight of 10 people be $A\text{ kg}$.
- Initial Total Weight $= 10A\text{ kg}$.
- Let the weights of the two new people be $3x$ and $2x$.
- When replaced, the new total weight is:
  $$\text{New Total} = 10A - (62 + 68) + (3x + 2x) = 10A - 130 + 5x$$
- Given new average $= A + 2$:
  $$\frac{10A - 130 + 5x}{10} = A + 2$$
  $$10A - 130 + 5x = 10A + 20 \implies 5x = 150 \implies x = 30$$
- Heavier new person $= 3x = 3(30) = \mathbf{90\text{ kg}}$.

> 💡 **Takeaway:** In replacement problems, the number of persons remains constant. $\text{Sum}_{\text{new}} = \text{Sum}_{\text{old}} + n \times \Delta\text{Avg}$.

---

### 🔹 QUESTION 02
**Topic:** Average of Subsets | **Concept:** Net Deviation Balancing ($\sum \Delta = 0$)

**English:**  
The average of 12 numbers is 40. The average of the first 6 numbers is 32 and that of the last 4 numbers is 45. Find the average of the remaining two numbers.

**हिन्दी:**  
12 संख्याओं का औसत 40 है। पहली 6 संख्याओं का औसत 32 है और अंतिम 4 संख्याओं का औसत 45 है। शेष दो संख्याओं का औसत ज्ञात कीजिए।

**Options:**  
a) 48  
b) 50  
c) 52  
d) 54  
e) None of these  

**Correct Answer:** **d) 54**

---

#### 🎯 Kaushik Sir's Approach (Net Deviation Method):
1. **Take Overall Average as Baseline:** Base $= 40$.
2. **Calculate Deviations of Known Subsets:**
   - First 6 numbers: Each is $32$, so deviation $= 32 - 40 = -8$.
     $$\text{Net Deviation} = 6 \times (-8) = -48$$
   - Last 4 numbers: Each is $45$, so deviation $= 45 - 40 = +5$.
     $$\text{Net Deviation} = 4 \times (+5) = +20$$
   - Total known deviation $= -48 + 20 = -28$.
3. **Balancing the Remaining 2 Numbers:**
   - To make $\sum \Delta = 0$, the remaining 2 numbers must have a deviation of $+28$.
   - Deviation per remaining number $= \frac{+28}{2} = +14$.
4. **Average of Remaining 2 Numbers:**
   $$\text{Average} = \text{Base} + \text{Deviation per number} = 40 + 14 = \mathbf{54}$$

---

#### 📘 Basic / Algebraic Approach:
- Total sum of 12 numbers $= 12 \times 40 = 480$.
- Sum of first 6 numbers $= 6 \times 32 = 192$.
- Sum of last 4 numbers $= 4 \times 45 = 180$.
- Sum of known 10 numbers $= 192 + 180 = 372$.
- Sum of remaining 2 numbers $= 480 - 372 = 108$.
- Average of remaining 2 numbers $= \frac{108}{2} = \mathbf{54}$.

---

### 🔹 QUESTION 03
**Topic:** Arithmetic Shifts | **Concept:** Net Effect on Average

**English:**  
The average of 10 numbers is 95. If 14 is added to each of the first four numbers and 12 is subtracted from each of the next three numbers, what will be the new average of the 10 numbers?

**हिन्दी:**  
10 संख्याओं का औसत 95 है। यदि पहली चार संख्याओं में से प्रत्येक में 14 जोड़ा जाता है और अगली तीन संख्याओं में से प्रत्येक से 12 घटाया जाता है, तो 10 संख्याओं का नया औसत क्या होगा?

**Options:**  
a) 96  
b) 98  
c) 95.5  
d) 97  
e) None of these  

**Correct Answer:** **d) 97**

---

#### 🎯 Kaushik Sir's Approach (Net Sum Shift):
1. **Net Change in Total Sum:**
   $$\Delta\text{Sum} = [4 \times (+14)] + [3 \times (-12)] = +56 - 36 = +20$$
2. **Net Change in Average across all 10 numbers:**
   $$\Delta\text{Avg} = \frac{\Delta\text{Sum}}{n} = \frac{+20}{10} = +2$$
3. **New Average:**
   $$\text{New Average} = \text{Old Average} + \Delta\text{Avg} = 95 + 2 = \mathbf{97}$$

---

#### 📘 Basic / Algebraic Approach:
- Initial Total Sum $= 10 \times 95 = 950$.
- New Total Sum $= 950 + (4 \times 14) - (3 \times 12) = 950 + 56 - 36 = 970$.
- New Average $= \frac{970}{10} = \mathbf{97}$.

---

### 🔹 QUESTION 04
**Topic:** Algebra in Averages | **Concept:** Elimination & Total Count

**English:**  
The sum of a set of numbers is $S$. If the number 3 is removed from the set, the sum of the remaining numbers is 105. If the number 7 is removed from the set, the sum of the remaining numbers is 45. What was the average of the original set of numbers?

**हिन्दी:**  
संख्याओं के एक सेट का योग $S$ है। यदि सेट से संख्या 3 हटा दी जाती है, तो शेष संख्याओं का योग 105 हो जाता है। यदि सेट से संख्या 7 हटा दी जाती है, तो शेष संख्याओं का योग 45 हो जाता है। मूल सेट की संख्याओं का औसत क्या था?

**Options:**  
a) 8  
b) 9  
c) 10  
d) 12  
e) None of these  

**Correct Answer:** **c) 10**

---

#### 🎯 Kaushik Sir's Approach:
1. **Translate the Problem into Direct Linear Equations:**
   - When all 3s are removed: $S - 3N = 105$
   - When all 7s are removed: $S - 7N = 45$
2. **Subtract Equation (2) from Equation (1):**
   $$(S - 3N) - (S - 7N) = 105 - 45$$
   $$4N = 60 \implies N = 15\text{ (Count of each element)}$$
3. **Find Total Sum $S$:**
   $$S = 105 + 3(15) = 105 + 45 = 150$$
4. **Calculate Original Average:**
   $$\text{Original Average} = \frac{\text{Total Sum}}{\text{Total Elements}} = \frac{150}{15} = \mathbf{10}$$

---

#### 📘 Basic / Algebraic Approach:
- Let the total number of terms be $N$, and total sum be $S$.
- Removing $N$ instances of 3 leaves sum $= S - 3N = 105$.
- Removing $N$ instances of 7 leaves sum $= S - 7N = 45$.
- Solving simultaneously:
  $$4N = 60 \implies N = 15$$
  $$S = 105 + 45 = 150$$
- $\text{Average} = \frac{S}{N} = \frac{150}{15} = \mathbf{10}$.

---

### 🔹 QUESTION 05
**Topic:** Multiple Inclusions & Exclusions | **Concept:** Invariant Average Condition

**English:**  
In a company of 10 employees, the average salary is $X\text{ k}$. Three employees whose salaries are 14k, 16k and 20k left the company, while two new employees joined whose salaries are 19k and 21k. If the new average salary of the remaining 9 employees is still $X\text{ k}$, find the value of $X$.

**हिन्दी:**  
10 कर्मचारियों वाली एक कंपनी में, औसत वेतन $X\text{ k}$ है। तीन कर्मचारी जिनका वेतन 14k, 16k और 20k है कंपनी छोड़ देते हैं, जबकि दो नए कर्मचारी शामिल होते हैं जिनका वेतन 19k और 21k है। यदि शेष 9 कर्मचारियों का नया औसत वेतन अभी भी $X\text{ k}$ है, तो $X$ का मान ज्ञात कीजिए।

**Options:**  
a) 10  
b) 12  
c) 15  
d) 18  
e) None of these  

**Correct Answer:** **a) 10**

---

#### 🎯 Kaushik Sir's Approach (Net Sum Balancing):
1. **Sum of 3 Leaving Employees:**
   $$\text{Leaving Sum} = 14 + 16 + 20 = 50\text{ k}$$
2. **Sum of 2 Joining Employees:**
   $$\text{Joining Sum} = 19 + 21 = 40\text{ k}$$
3. **Net Outflow in Total Salary:**
   $$\text{Net Change} = 40 - 50 = -10\text{ k}$$
4. **Equation for New Average ($n = 10 - 3 + 2 = 9$):**
   $$\text{New Sum} = 9 \times X$$
   $$\text{Old Sum} + \text{Net Change} = \text{New Sum}$$
   $$10X - 10 = 9X \implies X = \mathbf{10}$$

---

#### 📘 Basic / Algebraic Approach:
- Total initial salary $= 10 \times X = 10X\text{ k}$.
- Salary after 3 left and 2 joined:
  $$\text{New Total} = 10X - (14 + 16 + 20) + (19 + 21) = 10X - 50 + 40 = 10X - 10$$
- Total employees now $= 10 - 3 + 2 = 9$.
- Given new average is $X$:
  $$\frac{10X - 10}{9} = X \implies 10X - 10 = 9X \implies X = \mathbf{10}$$

---

### 🔹 QUESTION 06
**Topic:** Cricket Batsman Average | **Concept:** Alligation / Group Average Shift

**English:**  
The average runs of $N$ batsmen in a local cricket league is $(N+5)$ runs. If 3 new batsmen join the team, the overall average runs increase by 2 runs. If the total runs scored by these 3 new batsmen combined is 81 runs, then find the value of $N$.

**हिन्दी:**  
एक स्थानीय क्रिकेट लीग में $N$ बल्लेबाजों का औसत रन $(N+5)$ रन है। यदि 3 नए बल्लेबाज टीम में शामिल होते हैं, तो कुल औसत रन में 2 रन की वृद्धि होती है। यदि इन 3 नए बल्लेबाजों द्वारा बनाए गए कुल रन 81 हैं, तो $N$ का मान ज्ञात कीजिए।

**Options:**  
a) 10  
b) 12  
c) 15  
d) 18  
e) None of these  

**Correct Answer:** **b) 12**

---

#### 🎯 Kaushik Sir's Approach (Method 1: Alligation):
1. **Group 1 ($N$ batsmen):** Average $= N + 5$.
2. **Group 2 (3 new batsmen):** Average $= \frac{81}{3} = 27$.
3. **Combined Average:** $(N + 5) + 2 = N + 7$.
4. **Alligation Setup:**
   ```
       N Batsmen Avg (N+5)          3 Batsmen Avg (27)
                        \              /
                         \            /
                      Combined Avg (N+7)
                         /            \
                        /              \
                 |27 - (N+7)|    :   |(N+7) - (N+5)|
                   = 20 - N      :         = 2
   ```
5. **Ratio of Batsmen = $N : 3$:**
   $$\frac{N}{3} = \frac{20 - N}{2} \implies 2N = 60 - 3N \implies 5N = 60 \implies N = \mathbf{12}$$

---

#### 📘 Basic / Algebraic Approach (Total Sum Equivalence):
- Total runs of $N$ batsmen $= N(N+5) = N^2 + 5N$.
- When 3 new batsmen join, total batsmen $= N + 3$.
- New total runs $= (N^2 + 5N) + 81$.
- New overall average $= (N + 5) + 2 = N + 7$.
- Total runs also $= (N + 3)(N + 7) = N^2 + 10N + 21$.
- Equating total runs:
  $$N^2 + 5N + 81 = N^2 + 10N + 21$$
  $$5N + 81 = 10N + 21 \implies 5N = 60 \implies N = \mathbf{12}$$

---

### 🔹 QUESTION 07
**Topic:** Equal Distribution / Inverse Proportion | **Concept:** Absence & Surplus

**English:**  
For a school picnic, a box of chocolates was bought to be distributed equally among all 60 students of a class. However, on the day of the picnic, 15 students were absent; as a result, each student who was present received 2 additional chocolates. If all 60 students had been present, how many chocolates would each student have received?

**हिन्दी:**  
एक स्कूल पिकनिक के लिए, एक कक्षा के सभी 60 छात्रों के बीच समान रूप से वितरित करने के लिए चॉकलेट का एक डिब्बा खरीदा गया था। हालाँकि, पिकनिक के दिन 15 छात्र अनुपस्थित थे, जिसके परिणामस्वरूप उपस्थित प्रत्येक छात्र को 2 अतिरिक्त चॉकलेट मिलीं। यदि सभी 60 छात्र उपस्थित होते तो प्रत्येक छात्र को कितनी चॉकलेट मिलती?

**Options:**  
a) 5  
b) 6  
c) 8  
d) 10  
e) None of these  

**Correct Answer:** **b) 6**

---

#### 🎯 Kaushik Sir's Approach (Surplus Redistribution Logic):
1. **Total Students:** $60$. Present students $= 60 - 15 = 45$.
2. **Surplus Chocolates Distributed:**
   - 45 students received 2 extra chocolates each.
   - Total surplus chocolates from 15 absent students $= 45 \times 2 = 90\text{ chocolates}$.
3. **Original Share per Absent Student:**
   - Those 90 chocolates originally belonged to the 15 absent students.
   - Original share per student $= \frac{90}{15} = \mathbf{6\text{ chocolates}}$.

---

#### 📘 Basic / Algebraic Approach:
- Let the intended number of chocolates per student be $x$.
- Total chocolates in the box $= 60x$.
- When 15 students are absent, remaining students $= 45$.
- Each present student gets $(x + 2)$ chocolates:
  $$45(x + 2) = 60x$$
  $$45x + 90 = 60x \implies 15x = 90 \implies x = \mathbf{6}$$

---

### 🔹 QUESTION 08
**Topic:** System of Equations in Averages | **Concept:** Dual Inclusion Conditions

**English:**  
The average age of a class with $X$ students is $Y$ years. If 5 new students join with a total age of 135 years, the class average increases by 5. If 2 new students join with a total age of 60 years, the class average increases by 6. Find the value of $X$.

**हिन्दी:**  
$X$ छात्रों वाली एक कक्षा की औसत आयु $Y$ वर्ष है। यदि 135 वर्ष की कुल आयु वाले 5 नए छात्र शामिल होते हैं तो कक्षा के औसत में 5 की वृद्धि होती है। यदि 60 वर्ष की कुल आयु वाले 2 नए छात्र शामिल होते हैं तो कक्षा के औसत में 6 की वृद्धि होती है। $X$ का मान ज्ञात कीजिए।

**Options:**  
a) 2  
b) 3  
c) 1  
d) 4  
e) None of these  

**Correct Answer:** **c) 1**

---

#### 🎯 Kaushik Sir's Approach (Surplus Equation Formulation):
1. **Inclusion Formula:**
   $$\text{Sum of Incoming} = (\text{Incoming Count} \times \text{Old Avg}) + (\text{New Total Count} \times \Delta\text{Avg})$$
2. **Case 1 (5 students join, sum = 135, $\Delta\text{Avg} = +5$):**
   $$135 = 5Y + (X + 5) \times 5$$
   $$135 = 5Y + 5X + 25 \implies 5(X + Y) = 110 \implies X + Y = 22 \quad \text{--- (1)}$$
3. **Case 2 (2 students join, sum = 60, $\Delta\text{Avg} = +6$):**
   $$60 = 2Y + (X + 2) \times 6$$
   $$60 = 2Y + 6X + 12 \implies 2Y + 6X = 48 \implies Y + 3X = 24 \quad \text{--- (2)}$$
4. **Subtract Equation (1) from Equation (2):**
   $$(Y + 3X) - (Y + X) = 24 - 22$$
   $$2X = 2 \implies X = \mathbf{1}$$

---

#### 📘 Basic / Algebraic Approach:
- Case 1: Total age of $(X+5)$ students $= X \cdot Y + 135 = (X+5)(Y+5)$.
  $$XY + 135 = XY + 5X + 5Y + 25 \implies 5X + 5Y = 110 \implies X + Y = 22$$
- Case 2: Total age of $(X+2)$ students $= X \cdot Y + 60 = (X+2)(Y+6)$.
  $$XY + 60 = XY + 6X + 2Y + 12 \implies 6X + 2Y = 48 \implies 3X + Y = 24$$
- Subtracting gives $2X = 2 \implies X = \mathbf{1}$ (and $Y = 21$).

---

### 🔹 QUESTION 09
**Topic:** Class Weight Alligation | **Concept:** Missing Group Average

**English:**  
The average weight of all the boys in a class is 54 kg and the average weight of all the girls in the class is $X\text{ kg}$. If the ratio between boys and girls in the class is $5 : 4$ and the average weight of the whole class is 46 kg, then find the value of $X$.

**हिन्दी:**  
एक कक्षा में सभी लड़कों का औसत वजन 54 kg है और कक्षा में सभी लड़कियों का औसत वजन $X\text{ kg}$ है। यदि कक्षा में लड़कों और लड़कियों का अनुपात $5 : 4$ है और पूरी कक्षा का औसत वजन 46 kg है, तो $X$ का मान ज्ञात कीजिए।

**Options:**  
a) 32 kg  
b) 34 kg  
c) 36 kg  
d) 38 kg  
e) None of these  

**Correct Answer:** **c) 36 kg**

---

#### 🎯 Kaushik Sir's Approach (Alligation Rule):
1. **Setup Alligation Diagram:**
   ```
         Boys (54 kg)             Girls (X kg)
                 \               /
                  \             /
                 Class Avg (46 kg)
                  /             \
                 /               \
              (46 - X)     :    (54 - 46) = 8
   ```
2. **Equate to Ratio of Quantities ($5 : 4$):**
   $$\frac{46 - X}{8} = \frac{5}{4}$$
   $$46 - X = \frac{5 \times 8}{4} = 10$$
   $$X = 46 - 10 = \mathbf{36\text{ kg}}$$

---

#### 📘 Basic / Algebraic Approach (Weighted Average Formula):
- Ratio of Boys : Girls $= 5 : 4 \implies \text{Boys} = 5k, \text{Girls} = 4k$.
- Total Weight $= (5k \times 54) + (4k \times X) = 270k + 4kX$.
- Class Average $= \frac{270k + 4kX}{5k + 4k} = 46$.
  $$\frac{270 + 4X}{9} = 46$$
  $$270 + 4X = 414 \implies 4X = 144 \implies X = \mathbf{36\text{ kg}}$$

---

## 📌 SET 2: WEIGHTED AVERAGE, REPLACEMENT & ALLIGATION (Q10 – Q12)

---

### 🔹 QUESTION 10
**Topic:** Multi-Department Salaries | **Concept:** Alligation & Weighted Deviation

**English:**  
The number of employees in department A and department B of a company are 4.5k and 1.5k respectively. The average salary of an employee in department A is $(s+400)$ and the average salary in department B is $(s-y)$. If the average salary of the entire company is $(s)$, find the value of $y$.

**हिन्दी:**  
एक कंपनी के डिपार्टमेंट A और डिपार्टमेंट B में कर्मचारियों की संख्या क्रमशः 4.5k और 1.5k है। डिपार्टमेंट A में कर्मचारी की औसत सैलरी $(s+400)$ है और डिपार्टमेंट B में औसत सैलरी $(s-y)$ है। अगर पूरी कंपनी की औसत सैलरी $(s)$ है, तो $y$ का मान ज्ञात कीजिए।

**Options:**  
a) 1400  
b) 1200  
c) 1350  
d) 1500  
e) None of these  

**Correct Answer:** **b) 1200**

---

#### 🎯 Kaushik Sir's Approach (Ratio & Net Deviation):
1. **Employee Ratio:**
   $$\text{Ratio } A : B = 4.5k : 1.5k = 3 : 1$$
2. **Deviations from Overall Mean $(s)$:**
   - Dept A deviation $= (s + 400) - s = +400$
   - Dept B deviation $= (s - y) - s = -y$
3. **Net Deviation Balancing ($\sum \Delta = 0$):**
   $$3 \times (+400) + 1 \times (-y) = 0$$
   $$1200 - y = 0 \implies y = \mathbf{1200}$$

---

#### 📘 Basic / Algebraic Approach:
- Total salary in Dept A $= 4.5k \times (s + 400)$.
- Total salary in Dept B $= 1.5k \times (s - y)$.
- Total employees $= 4.5k + 1.5k = 6k$.
- Overall company average $= s$:
  $$\frac{4.5k(s + 400) + 1.5k(s - y)}{6k} = s$$
  Divide numerator and denominator by $1.5k$:
  $$\frac{3(s + 400) + 1(s - y)}{4} = s$$
  $$3s + 1200 + s - y = 4s$$
  $$4s + 1200 - y = 4s \implies y = \mathbf{1200}$$

---

### 🔹 QUESTION 11
**Topic:** Team Gaming Score Replacement | **Concept:** Group Size from Deficit

**English:**  
The average score of a team of $N$ gamers is $S$ points. If one player is replaced by a new player whose score is $(S-32)$ points, the new average score of the team drops to $(S-4)$ points. If every player in the original team had the exact same score, find the value of $N$.

**हिन्दी:**  
$N$ गेमर्स की एक टीम का औसत स्कोर $S$ पॉइंट है। अगर एक खिलाड़ी को एक नए खिलाड़ी से बदल दिया जाए जिसका स्कोर $(S-32)$ पॉइंट्स है, तो टीम का नया औसत स्कोर घटकर $(S-4)$ पॉइंट्स हो जाता है। अगर ओरिजिनल टीम के सभी खिलाड़ियों का स्कोर बिल्कुल एक जैसा था, तो $N$ का मान ज्ञात कीजिए।

**Options:**  
a) 7  
b) 11  
c) 8  
d) 10  
e) None of these  

**Correct Answer:** **c) 8**

---

#### 🎯 Kaushik Sir's Approach (Replacement Deficit Shortcut):
1. **Identify the Individual Change:**
   - Replaced player score $= S$ (since everyone scored $S$).
   - New player score $= S - 32$.
   - Net loss to total team score $= S - (S - 32) = 32\text{ points}$.
2. **Identify the Per-Player Drop in Average:**
   - Old average $= S$, New average $= S - 4 \implies \text{Drop per player} = 4\text{ points}$.
3. **Number of Gamers ($N$):**
   $$N = \frac{\text{Total Score Drop}}{\text{Drop per Player}} = \frac{32}{4} = \mathbf{8}$$

---

#### 📘 Basic / Algebraic Approach:
- Total initial score of $N$ gamers $= N \times S$.
- When one player (score $S$) is replaced by new player (score $S - 32$):
  $$\text{New Total Score} = N \cdot S - S + (S - 32) = N \cdot S - 32$$
- New average is $(S - 4)$:
  $$\frac{N \cdot S - 32}{N} = S - 4$$
  $$N \cdot S - 32 = N(S - 4) = N \cdot S - 4N$$
  $$-32 = -4N \implies N = \frac{32}{4} = \mathbf{8}$$

---

### 🔹 QUESTION 12
**Topic:** Dual-Constraint Alligation | **Concept:** Cross-Referenced Counts & Ratings

**English:**  
The average rating score given by all female reviewers is $(Y+20)$ and the average rating score given by all male reviewers for the same product is $(Y-10)$. The average rating score across the entire group of reviewers is $(Y+2)$. If the number of male and female reviewers is equal to the average rating score given by female and male reviewers respectively, find the value of $Y$.

**हिन्दी:**  
सभी महिला रिव्यूअर्स द्वारा दिए गए औसत रेटिंग स्कोर $(Y+20)$ है और उसी प्रोडक्ट के लिए सभी पुरुष रिव्यूअर्स द्वारा दिए गए औसत रेटिंग स्कोर $(Y-10)$ हैं। रिव्यूअर्स के पूरे ग्रुप का औसत रेटिंग स्कोर $(Y+2)$ है। अगर पुरुष और महिला रिव्यूअर्स की संख्या क्रमशः महिला और पुरुष रिव्यूअर्स द्वारा दिए गए औसत रेटिंग स्कोर के बराबर हैं, तो $Y$ का मान ज्ञात कीजिए।

**Options:**  
a) 50  
b) 60  
c) 65  
d) 70  
e) None of these  

**Correct Answer:** **d) 70**

---

#### 🎯 Kaushik Sir's Approach (Alligation + Proportion):
1. **Alligation on Ratings:**
   ```
        Female Avg (Y+20)           Male Avg (Y-10)
                      \               /
                       \             /
                      Overall Avg (Y+2)
                       /             \
                      /               \
         |(Y-10) - (Y+2)|      :     |(Y+20) - (Y+2)|
               = 12            :           = 18
   ```
   $$\text{Ratio of Female : Male Reviewers} = 12 : 18 = 2 : 3$$

2. **Connecting Counts to Ratings:**
   - Number of Female Reviewers $=$ Male Average Score $= Y - 10$
   - Number of Male Reviewers $=$ Female Average Score $= Y + 20$

3. **Equate the Ratio:**
   $$\frac{\text{Female Reviewers}}{\text{Male Reviewers}} = \frac{Y - 10}{Y + 20} = \frac{2}{3}$$
   $$3(Y - 10) = 2(Y + 20)$$
   $$3Y - 30 = 2Y + 40 \implies Y = \mathbf{70}$$

---

#### 📘 Basic / Algebraic Approach:
- Let $F = \text{Female count}$, $M = \text{Male count}$.
- Given $F = Y - 10$ and $M = Y + 20$.
- Total rating $= F(Y + 20) + M(Y - 10) = (Y - 10)(Y + 20) + (Y + 20)(Y - 10) = 2(Y - 10)(Y + 20)$.
- Total reviewers $= F + M = (Y - 10) + (Y + 20) = 2Y + 10$.
- Overall average $= Y + 2$:
  $$\frac{2(Y - 10)(Y + 20)}{2Y + 10} = Y + 2$$
  $$2(Y^2 + 10Y - 200) = (2Y + 10)(Y + 2)$$
  $$2Y^2 + 20Y - 400 = 2Y^2 + 14Y + 20$$
  $$6Y = 420 \implies Y = \mathbf{70}$$

---


## 📌 SET 3: CONSECUTIVE NUMBERS & AP SERIES (Q13 – Q18)

---

### 🔹 QUESTION 13
**Topic:** Consecutive Series & Multiples | **Concept:** AP Middle Term & Symmetry

**English:**  
Set A consists of 7 consecutive even numbers, while Set B consists of 5 consecutive multiples of 5. If the average of the first 4 terms of Set A is 37 and the $4^{\text{th}}$ term of Set B is equal to the average of Set A, then find the sum of the largest term of Set A and the smallest term of Set B.

**हिन्दी:**  
सेट A में लगातार 7 सम संख्याएँ हैं, जबकि सेट B में 5 लगातार 5 के गुणज हैं। अगर सेट A के पहले 4 पदों का औसत 37 है और सेट B का चौथा पद सेट A के औसत के बराबर है, तो सेट A के सबसे बड़े पद और सेट B के सबसे छोटे पद का योग ज्ञात कीजिए।

**Options:**  
a) 73  
b) 77  
c) 71  
d) 79  
e) None of these  

**Correct Answer:** **c) 71**

---

#### 🎯 Kaushik Sir's Approach (AP Symmetry Shortcut):
1. **Analyze Set A (7 consecutive even numbers):**
   - First 4 terms have average $= 37$.
   - For 4 consecutive even numbers, average lies exactly between the $2^{\text{nd}}$ and $3^{\text{rd}}$ term.
   - Hence, $2^{\text{nd}}\text{ term} = 36$ and $3^{\text{rd}}\text{ term} = 38$.
   - Full Set A: $34, 36, 38, 40, 42, 44, 46$.
   - **Largest term of Set A** $= 46$.
   - **Average of Set A (Middle / $4^{\text{th}}$ term)** $= 40$.
2. **Analyze Set B (5 consecutive multiples of 5, common difference = 5):**
   - $4^{\text{th}}\text{ term of B} = \text{Average of Set A} = 40$.
   - To get to the $1^{\text{st}}$ (smallest) term, subtract $3 \times 5 = 15$:
     $$\text{Smallest term of Set B} = 40 - 15 = 25$$
3. **Required Sum:**
   $$\text{Sum} = 46 + 25 = \mathbf{71}$$

---

#### 📘 Basic / Algebraic Approach:
- Let the first term of Set A be $a$.
  - First 4 terms: $a, a+2, a+4, a+6$.
  - Average $= \frac{4a + 12}{4} = a + 3 = 37 \implies a = 34$.
  - Largest term of Set A ($7^{\text{th}}$ term) $= a + 12 = 34 + 12 = 46$.
  - Average of all 7 terms $= a + 6 = 34 + 6 = 40$.
- Let the first term of Set B be $b$.
  - $4^{\text{th}}$ term of Set B $= b + 3(5) = b + 15$.
  - Given $b + 15 = 40 \implies b = 25$ (Smallest term of B).
- $\text{Required Sum} = 46 + 25 = \mathbf{71}$.

---

### 🔹 QUESTION 14
**Topic:** Consecutive Odd & Even Series | **Concept:** Boundary Average Invariance

**English:**  
The average of series M1 having 5 consecutive even numbers is 26. Find the sum of three consecutive odd numbers of series M2 whose largest number is 7 more than the average of the largest and smallest numbers of series M1.

**हिन्दी:**  
M1 सीरीज़, जिसमें लगातार 5 सम संख्याएँ हैं, का औसत 26 है। M2 सीरीज़ की लगातार तीन विषम संख्याओं का योग ज्ञात कीजिए, जिनकी सबसे बड़ी संख्या M1 सीरीज़ की सबसे बड़ी और सबसे छोटी संख्या के औसत से 7 ज़्यादा है।

**Options:**  
a) 83  
b) 93  
c) 95  
d) 75  
e) None of these  

**Correct Answer:** **b) 93**

---

#### 🎯 Kaushik Sir's Approach:
1. **Symmetry Property of Series M1:**
   - For ANY AP series, $\frac{\text{Smallest} + \text{Largest}}{2} = \text{Average of the Series} = 26$.
   - *No need to calculate individual terms of M1!*
2. **Find Terms of Series M2 (3 consecutive odd numbers):**
   - Largest odd number $= 26 + 7 = 33$.
   - The three consecutive odd numbers ending at 33 are: $29, 31, 33$.
3. **Calculate Sum of M2:**
   - In 3 consecutive odd numbers, $\text{Sum} = 3 \times \text{Middle Term} = 3 \times 31 = \mathbf{93}$.

---

#### 📘 Basic / Algebraic Approach:
- M1 Series: $a-4, a-2, a, a+2, a+4$ with average $a = 26$.
  - Smallest $= 22$, Largest $= 30$.
  - Average of smallest and largest $= \frac{22 + 30}{2} = 26$.
- M2 Series: Largest number $L = 26 + 7 = 33$.
  - Three consecutive odd numbers: $L - 4, L - 2, L \implies 29, 31, 33$.
  - $\text{Sum} = 29 + 31 + 33 = \mathbf{93}$.

---

### 🔹 QUESTION 15
**Topic:** Dual Series & Squares | **Concept:** Even/Odd Series Properties

**English:**  
There is a Set A of 6 consecutive even numbers and a Set B of 6 consecutive odd numbers. The square of the sum of the lowest and highest even numbers is 900, while the average of the given 6 odd numbers is 16. Find the sum of the highest odd number and lowest even number.

**हिन्दी:**  
लगातार 6 सम संख्याओं का एक सेट A है और लगातार 6 विषम संख्याओं का एक सेट B है। सबसे छोटी और सबसे बड़ी सम संख्याओं के योग का वर्ग 900 है, जबकि दी गई 6 विषम संख्याओं का औसत 16 है। सबसे बड़ी विषम संख्या और सबसे छोटी सम संख्या का योग ज्ञात कीजिए।

**Options:**  
a) 19  
b) 29  
c) 39  
d) 49  
e) None of these (31)  

**Correct Answer:** **e) None of these (31)**

---

#### 🎯 Kaushik Sir's Approach:
1. **Analyze Set A (6 consecutive even numbers):**
   - Let terms be $x, x+2, x+4, x+6, x+8, x+10$.
   - Lowest $= x$, Highest $= x+10$.
   - Sum $= x + (x+10) = 2x + 10$.
   - Given $(2x + 10)^2 = 900 \implies 2x + 10 = 30 \implies 2x = 20 \implies x = 10$.
   - **Lowest even number** $= 10$.
2. **Analyze Set B (6 consecutive odd numbers):**
   - Average $= 16$ (lies between $3^{\text{rd}}$ and $4^{\text{th}}$ terms: 15 and 17).
   - Set B terms: $11, 13, 15, 17, 19, 21$.
   - **Highest odd number** $= 21$.
3. **Required Sum:**
   $$\text{Sum} = 21 + 10 = \mathbf{31}$$

---

#### 📘 Basic / Algebraic Approach:
- Set A: $x, x+2, \dots, x+10$.
  - Sum of extremes $= 2x + 10$.
  - $(2x + 10)^2 = 900 \implies 2x + 10 = 30 \implies x = 10$.
- Set B: $y, y+2, y+4, y+6, y+8, y+10$.
  - Average $= \frac{6y + 30}{6} = y + 5 = 16 \implies y = 11$.
  - Highest odd number $= y + 10 = 11 + 10 = 21$.
- $\text{Sum} = 21 + 10 = \mathbf{31}$.

---

### 🔹 QUESTION 16
**Topic:** Series Difference Invariance | **Concept:** Constant Gap Property

**English:**  
Series S1 contains 5 consecutive odd numbers and series S2 contains 5 consecutive even numbers. The largest number of series S1 is three more than the smallest number of series S2. What is the difference between the sum of the largest numbers of S1 and S2 and the sum of the second smallest numbers of S1 and S2 together?

**हिन्दी:**  
सीरीज़ S1 में लगातार 5 विषम संख्याएँ हैं और सीरीज़ S2 में लगातार 5 सम संख्याएँ हैं। सीरीज़ S1 की सबसे बड़ी संख्या, सीरीज़ S2 की सबसे छोटी संख्या से 3 ज़्यादा है। S1 और S2 की सबसे बड़ी संख्याओं के योग और S1 और S2 की दूसरी सबसे छोटी संख्याओं के योग के बीच क्या अंतर है?

**Options:**  
a) 4  
b) 6  
c) 8  
d) 12  
e) Can't be determined  

**Correct Answer:** **d) 12**

---

#### 🎯 Kaushik Sir's Approach (Direct Index Distance Shortcut):
1. **Notice the Invariant Structure:**
   - In ANY 5-term consecutive series (odd or even, common difference $d=2$):
     $$\text{Largest term} = T_5$$
     $$\text{Second smallest term} = T_2$$
     $$\text{Difference } (T_5 - T_2) = (5 - 2) \times 2 = 3 \times 2 = 6$$
2. **Apply to Both Series:**
   - For S1: $\text{Largest}(S_1) - 2^{\text{nd}}\text{Smallest}(S_1) = 6$
   - For S2: $\text{Largest}(S_2) - 2^{\text{nd}}\text{Smallest}(S_2) = 6$
3. **Combined Difference:**
   $$\text{Required Difference} = 6 + 6 = \mathbf{12}$$
   *(Note: The connecting condition "largest of S1 is 3 more..." is extra redundant data!).*

---

#### 📘 Basic / Algebraic Approach:
- Let S1 be $a, a+2, a+4, a+6, a+8$.
  - Largest of S1 $= a+8$, $2^{\text{nd}}$ smallest of S1 $= a+2$.
- Let S2 be $b, b+2, b+4, b+6, b+8$.
  - Largest of S2 $= b+8$, $2^{\text{nd}}$ smallest of S2 $= b+2$.
- $\text{Difference} = [(a+8) + (b+8)] - [(a+2) + (b+2)] = (a+b+16) - (a+b+4) = \mathbf{12}$.

---

### 🔹 QUESTION 17
**Topic:** Cross-Series Linking | **Concept:** Reverse AP Reconstruction

**English:**  
The sum of 5 consecutive even numbers is 230. Another set of 6 consecutive odd numbers has its largest term 7 less than the smallest term of the even number series. Find the sum of all these odd numbers.

**हिन्दी:**  
लगातार 5 सम संख्याओं का योग 230 है। लगातार 6 विषम संख्याओं के एक और सेट में, सबसे बड़ी संख्या, सम संख्याओं की सीरीज़ की सबसे छोटी संख्या से 7 कम है। इन सभी विषम संख्याओं का योग ज्ञात कीजिए।

**Options:**  
a) 192  
b) 180  
c) 207  
d) 216  
e) None of these  

**Correct Answer:** **b) 180**

---

#### 🎯 Kaushik Sir's Approach:
1. **Find Even Series (5 terms):**
   - Average (Middle / $3^{\text{rd}}$ term) $= \frac{230}{5} = 46$.
   - Terms: $42, 44, \mathbf{46}, 48, 50$.
   - Smallest even number $= 42$.
2. **Find Odd Series (6 terms):**
   - Largest odd number $= 42 - 7 = 35$.
   - 6 consecutive odd numbers ending at 35: $25, 27, 29, 31, 33, 35$.
3. **Sum of 6 Odd Numbers:**
   - Average of the 6 odd numbers $= \frac{29 + 31}{2} = 30$.
   - $\text{Sum} = 6 \times 30 = \mathbf{180}$.

---

#### 📘 Basic / Algebraic Approach:
- Let even numbers be $x, x+2, x+4, x+6, x+8$.
  $$5x + 20 = 230 \implies 5x = 210 \implies x = 42\text{ (Smallest)}$$
- Largest odd number $= 42 - 7 = 35$.
- Let 6 odd numbers ending at 35 be $y-10, y-8, y-6, y-4, y-2, y$ where $y = 35$.
  - Sum $= 6y - 30 = 6(35) - 30 = 210 - 30 = \mathbf{180}$.

---

### 🔹 QUESTION 18 (RRB PO 2023)
**Topic:** Subset Sum Decomposition | **Concept:** Complementary Pairs

**English:**  
The average of 4 even numbers is 45 and the average of 4 odd numbers is 38. If the average of the smallest and second smallest even numbers is 41 and the average of the smallest and second smallest odd numbers is 34, find the difference between the sum of the largest two even numbers and the sum of the largest two odd numbers.

**हिन्दी:**  
4 सम संख्याओं का औसत 45 है और 4 विषम संख्याओं का औसत 38 है। अगर सबसे छोटी और दूसरी सबसे छोटी सम संख्या का औसत 41 है और सबसे छोटी और दूसरी सबसे छोटी विषम संख्या का औसत 34 है, तो दो सबसे बड़ी सम संख्याओं के योग और दो सबसे बड़ी विषम संख्याओं के योग के बीच का अंतर ज्ञात कीजिए।

**Options:**  
a) 12  
b) 14  
c) 15  
d) 19  
e) None of these  

**Correct Answer:** **b) 14**

---

#### 🎯 Kaushik Sir's Approach:
1. **Even Group Analysis (4 numbers):**
   - Total Sum $= 4 \times 45 = 180$.
   - Sum of smallest 2 even numbers $= 2 \times 41 = 82$.
   - Sum of largest 2 even numbers $= 180 - 82 = 98$.
2. **Odd Group Analysis (4 numbers):**
   - Total Sum $= 4 \times 38 = 152$.
   - Sum of smallest 2 odd numbers $= 2 \times 34 = 68$.
   - Sum of largest 2 odd numbers $= 152 - 68 = 84$.
3. **Required Difference:**
   $$\text{Difference} = 98 - 84 = \mathbf{14}$$

---

#### 📘 Basic / Algebraic Approach:
- Let the 4 even numbers be $E_1, E_2, E_3, E_4$:
  $$E_1 + E_2 + E_3 + E_4 = 4 \times 45 = 180$$
  $$E_1 + E_2 = 2 \times 41 = 82 \implies E_3 + E_4 = 180 - 82 = 98$$
- Let the 4 odd numbers be $O_1, O_2, O_3, O_4$:
  $$O_1 + O_2 + O_3 + O_4 = 4 \times 38 = 152$$
  $$O_1 + O_2 = 2 \times 34 = 68 \implies O_3 + O_4 = 152 - 68 = 84$$
- $(E_3 + E_4) - (O_3 + O_4) = 98 - 84 = \mathbf{14}$.

---

## 📌 SET 4: ADVANCED AVERAGES, INCOME/SAVINGS & HEIGHTS (Q19 – Q22)

---

### 🔹 QUESTION 19
**Topic:** Annual Income & Expenditure | **Concept:** Monthly Weighted Average

**English:**  
The average monthly income of a person for the first 4 months of the year is ₹25,000, for the next 5 months is ₹22,000 and for the remaining 3 months is ₹30,000. If the average monthly expenditure of the person throughout the year is ₹13,000, find the average monthly savings of the person that year.

**हिन्दी:**  
साल के पहले 4 महीनों में एक व्यक्ति की औसत मासिक आय ₹25,000 रुपये है, अगले 5 महीनों में ₹22,000 रुपये है और बाकी 3 महीनों में ₹30,000 रुपये है। अगर पूरे साल उस व्यक्ति का औसत मासिक खर्च ₹13,000 रुपये है, तो उस साल उसकी औसत मासिक बचत क्या होगी?

**Options:**  
a) ₹12,000  
b) ₹15,000  
c) ₹11,500  
d) ₹13,500  
e) None of these  

**Correct Answer:** **a) ₹12,000**

---

#### 🎯 Kaushik Sir's Approach (Assumed Mean Deviation):
1. **Find Average Monthly Income:**
   - Let Assumed Base Income $= 25,000$.
   - First 4 months (25k): Deviation $= 0 \times 4 = 0$
   - Next 5 months (22k): Deviation $= -3,000 \times 5 = -15,000$
   - Next 3 months (30k): Deviation $= +5,000 \times 3 = +15,000$
   - Net annual deviation $= 0 - 15000 + 15000 = 0$.
   - $\text{Average Monthly Income} = 25,000 + \frac{0}{12} = ₹25,000$.
2. **Calculate Average Monthly Savings:**
   $$\text{Avg Monthly Savings} = \text{Avg Monthly Income} - \text{Avg Monthly Expenditure}$$
   $$\text{Avg Monthly Savings} = 25,000 - 13,000 = \mathbf{₹12,000}$$

---

#### 📘 Basic / Algebraic Approach:
- Total Annual Income $= (4 \times 25000) + (5 \times 22000) + (3 \times 30000)$
  $$= 100000 + 110000 + 90000 = ₹300,000$$
- Average Monthly Income $= \frac{300,000}{12} = ₹25,000$.
- Total Annual Expenditure $= 12 \times 13,000 = ₹156,000$.
- Total Annual Savings $= 300,000 - 156,000 = ₹144,000$.
- Average Monthly Savings $= \frac{144,000}{12} = \mathbf{₹12,000}$.

---

### 🔹 QUESTION 20
**Topic:** Multi-Variable Averages | **Concept:** Algebraic Difference Extraction

**English:**  
The average of the third and second number is equal to the first number. The average of the third and second number is 8 more than the average of the first and third number. What is the difference between the second and third number?

**हिन्दी:**  
तीसरी और दूसरी संख्या का औसत पहली संख्या के बराबर है; तीसरी और दूसरी संख्या का औसत, पहली और तीसरी संख्या के औसत से 8 ज़्यादा है। दूसरी और तीसरी संख्या के बीच का अंतर क्या है?

**Options:**  
a) 8  
b) 16  
c) 24  
d) 32  
e) None of these  

**Correct Answer:** **d) 32**

---

#### 🎯 Kaushik Sir's Approach (Even-Factor Substitution):
1. **Represent 2nd and 3rd numbers as $2a$ and $2b$ to avoid fractions:**
   - First Number $N_1 = \text{Avg}(2a, 2b) = a + b$.
2. **Use Second Condition:**
   $$\text{Avg}(N_2, N_3) = \text{Avg}(N_1, N_3) + 8$$
   $$a + b = \frac{(a + b) + 2b}{2} + 8$$
   $$2(a + b) = a + 3b + 16$$
   $$2a + 2b = a + 3b + 16 \implies a - b = 16$$
3. **Difference between Second and Third Number:**
   $$\text{Difference} = |2a - 2b| = 2(a - b) = 2 \times 16 = \mathbf{32}$$

---

#### 📘 Basic / Algebraic Approach:
- Let the numbers be $x, y, z$.
- Condition 1: $\frac{y + z}{2} = x \implies y + z = 2x$.
- Condition 2: $\frac{y + z}{2} = \frac{x + z}{2} + 8 \implies y + z = x + z + 16 \implies y - x = 16$.
- Substitute $x = \frac{y + z}{2}$ into $y - x = 16$:
  $$y - \frac{y + z}{2} = 16 \implies \frac{2y - (y + z)}{2} = 16 \implies \frac{y - z}{2} = 16 \implies y - z = \mathbf{32}$$.

---

### 🔹 QUESTION 21
**Topic:** Percentage Increment in Average | **Concept:** Quadratic Modeling

**English:**  
The average marks scored by a student in the first four exams of a five-exam series is $5x$. If they score 100 marks in the next exam, their average in the series increases by $2x\%$. Find the overall average of the series.

**हिन्दी:**  
पाँच परीक्षाओं की एक सीरीज़ में, एक छात्र द्वारा पहली चार परीक्षाओं में प्राप्त औसत अंक $5x$ हैं। यदि वह अगली परीक्षा में 100 अंक प्राप्त करता है, तो सीरीज़ में उसका औसत $2x\%$ बढ़ जाता है। सीरीज़ का कुल औसत ज्ञात कीजिए।

**Options:**  
a) 50  
b) 72  
c) 60  
d) 80  
e) None of these  

**Correct Answer:** **c) 60**

---

#### 🎯 Kaushik Sir's Approach:
1. **Total Marks in First 4 Exams:** $4 \times 5x = 20x$.
2. **New Total after 5th Exam (score = 100):** $20x + 100$.
3. **New Average:**
   $$\text{New Avg} = \frac{20x + 100}{5} = 4x + 20$$
4. **Percentage Increase Condition:**
   $$\text{New Avg} = 5x \times \left(1 + \frac{2x}{100}\right) = 5x + \frac{10x^2}{100} = 5x + \frac{x^2}{10}$$
5. **Equating Expressions:**
   $$4x + 20 = 5x + \frac{x^2}{10}$$
   $$20 = x + \frac{x^2}{10} \implies x^2 + 10x - 200 = 0$$
   $$(x + 20)(x - 10) = 0 \implies x = 10\text{ (since } x > 0)$$
6. **Overall Average of the 5 Exams:**
   $$\text{Overall Average} = 4x + 20 = 4(10) + 20 = \mathbf{60}$$

---

#### 📘 Basic / Algebraic Approach:
- Initial Average $= 5x \implies \text{Sum of 4 exams} = 20x$.
- 5th exam score $= 100 \implies \text{Total sum} = 20x + 100$.
- Actual new average $= \frac{20x + 100}{5} = 4x + 20$.
- Given increase in average is $2x\%$ of $5x$:
  $$\Delta\text{Avg} = 5x \cdot \frac{2x}{100} = \frac{x^2}{10}$$
  $$\text{New Avg} - \text{Old Avg} = \frac{x^2}{10} \implies (4x + 20) - 5x = \frac{x^2}{10} \implies 20 - x = \frac{x^2}{10}$$
  $$x^2 + 10x - 200 = 0 \implies x = 10$$
- $\text{Overall Average} = 5(10) + \frac{10^2}{10} = 50 + 10 = \mathbf{60}$.

---

### 🔹 QUESTION 22
**Topic:** 3-Person Height System | **Concept:** Pairwise Averages & Offset Matching

**English:**  
The average height of David, Ethan and Finn is $Y\text{ cm}$. The average height of David and Ethan is $(Y+10)\text{ cm}$, while the average height of Ethan and Finn is $(Y-5)\text{ cm}$. If David's height is 165 cm less than twice Ethan's height, find the total height of David and Finn.

**हिन्दी:**  
डेविड, ईथन और फिन की औसत लंबाई $Y\text{ cm}$ है; डेविड और ईथन की औसत लंबाई $(Y+10)\text{ cm}$ है, जबकि ईथन और फिन की औसत लंबाई $(Y-5)\text{ cm}$ है। अगर डेविड की लंबाई ईथन की लंबाई के दोगुने से 165 cm कम है, तो डेविड और फिन की कुल लंबाई ज्ञात करें।

**Options:**  
a) 360 cm  
b) 330 cm  
c) 310 cm  
d) 300 cm  
e) None of these  

**Correct Answer:** **d) 300 cm**

---

#### 🎯 Kaushik Sir's Approach:
1. **Total Height of All Three:**
   $$D + E + F = 3Y$$
2. **Pairwise Heights & Individual Isolation:**
   - $D + E = 2(Y + 10) = 2Y + 20 \implies F = 3Y - (2Y + 20) = Y - 20$
   - $E + F = 2(Y - 5) = 2Y - 10 \implies D = 3Y - (2Y - 10) = Y + 10$
   - Since $D = Y + 10$ and $D + E = 2Y + 20 \implies E = (2Y + 20) - (Y + 10) = Y + 10$.
3. **Apply David & Ethan's Height Condition:**
   $$D = 2E - 165$$
   $$Y + 10 = 2(Y + 10) - 165 = 2Y + 20 - 165 = 2Y - 145$$
   $$Y = 155\text{ cm}$$
4. **Find Heights and Required Sum $(D + F)$:**
   - $D = 155 + 10 = 165\text{ cm}$
   - $F = 155 - 20 = 135\text{ cm}$
   $$\text{Total Height of David and Finn} = 165 + 135 = \mathbf{300\text{ cm}}$$

---

#### 📘 Basic / Algebraic Approach:
- $D + E + F = 3Y$
- $D + E = 2Y + 20 \implies F = Y - 20$
- $E + F = 2Y - 10 \implies D = Y + 10$
- $E = 3Y - D - F = 3Y - (Y + 10) - (Y - 20) = Y + 10$
- $D = 2E - 165 \implies Y + 10 = 2Y + 20 - 165 \implies Y = 155$
- $D + F = (Y + 10) + (Y - 20) = 2Y - 10 = 2(155) - 10 = 310 - 10 = \mathbf{300\text{ cm}}$.

---


## 📌 SET 5: AGES — BASIC RATIOS, MULTI-PERSON & INVARIANT DIFFERENCE (Q23 – Q29)

---

### 🔹 QUESTION 23
**Topic:** Multi-Person Ages & Average | **Concept:** Sum-Substitution & Shift

**English:**  
The average age of Rohan, Kunal and Meera is 58 years. The sum of the ages of Kunal and Meera is equal to the age of Tanya. Meera is 8 years older than Rohan. Find the average age of Meera and Tanya after 4 years.

**हिन्दी:**  
रोहन, कुणाल और मीरा की औसत उम्र 58 साल है। कुणाल और मीरा की उम्र का जोड़ तान्या की उम्र के बराबर है। मीरा, रोहन से 8 साल बड़ी है। 4 साल बाद मीरा और तान्या की औसत उम्र पता करें।

**Options:**  
a) 83  
b) 87  
c) 91  
d) 95  
e) 99  

**Correct Answer:** **d) 95**

---

#### 🎯 Kaushik Sir's Approach (Direct Algebraic Substitution):
1. **Total Sum of Rohan, Kunal and Meera:**
   $$R + K + M = 3 \times 58 = 174\text{ years}$$
2. **Substitute Known Relations:**
   - Given $K + M = T$
   - Given $M = R + 8 \implies R = M - 8$
   - Replace $R$ and $(K + M)$ in the total sum equation:
     $$(M - 8) + T = 174 \implies M + T = 174 + 8 = 182\text{ years}$$
3. **Present & Future Average of Meera and Tanya:**
   $$\text{Present Average} = \frac{M + T}{2} = \frac{182}{2} = 91\text{ years}$$
   $$\text{Average after 4 years} = 91 + 4 = \mathbf{95\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $R + K + M = 174$
- $K + M = T \implies R + T = 174$
- $R = M - 8 \implies (M - 8) + T = 174 \implies M + T = 182$
- Present average of Meera and Tanya $= \frac{182}{2} = 91$.
- In 4 years, both ages increase by 4, so average increases by 4:
  $$\text{Future Average} = 91 + 4 = \mathbf{95\text{ years}}$$.

---

### 🔹 QUESTION 24
**Topic:** Compound Age Ratios | **Concept:** Ratio Merging & Percentage Excess

**English:**  
The ratio of the present ages of Rohan and Karan is $2 : 5$, while the ratio of the present ages of Rohan and Mohit is $3 : 4$. If 9 years ago, the age of Karan was 140% more than that of Mohit, find the sum of the ages of all three, 12 years hence.

**हिन्दी:**  
रोहन और करण की वर्तमान उम्र का अनुपात $2 : 5$ है, जबकि रोहन और मोहित की वर्तमान उम्र का अनुपात $3 : 4$ है। अगर 9 साल पहले करण की उम्र मोहित की उम्र से 140% ज़्यादा थी, तो 12 साल बाद तीनों की उम्र का योग क्या होगा?

**Options:**  
a) 87  
b) 96  
c) 114  
d) 123  
e) 132  

**Correct Answer:** **d) 123**

---

#### 🎯 Kaushik Sir's Approach:
1. **Combine Ratios for Rohan (R), Karan (K), Mohit (M):**
   - $R : K = 2 : 5 = 6 : 15$
   - $R : M = 3 : 4 = 6 : 8$
   - Combined Present Ratio: $R : K : M = 6 : 15 : 8$.
   - Let present ages be $6x, 15x, 8x$.
2. **Setup 9 Years Ago Equation:**
   - Karan was $140\%$ more than Mohit $\implies K_{-9} = (100 + 140)\% \times M_{-9} = 240\% \times M_{-9} = \frac{12}{5} M_{-9}$.
   $$15x - 9 = \frac{12}{5}(8x - 9)$$
   $$5(15x - 9) = 12(8x - 9)$$
   $$75x - 45 = 96x - 108 \implies 21x = 63 \implies x = 3$$
3. **Calculate Sums:**
   - Present Total Sum $= (6 + 15 + 8) \times 3 = 29 \times 3 = 87\text{ years}$.
   - Sum 12 years hence (each increases by 12):
     $$\text{Future Sum} = 87 + (3 \times 12) = 87 + 36 = \mathbf{123\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $R = 6x, K = 15x, M = 8x$.
- $K - 9 = 2.4(M - 9) \implies 15x - 9 = 19.2x - 21.6 \implies 4.2x = 12.6 \implies x = 3$.
- Present ages: Rohan $= 18$, Karan $= 45$, Mohit $= 24$.
- Ages after 12 years: Rohan $= 30$, Karan $= 57$, Mohit $= 36$.
- $\text{Total Sum} = 30 + 57 + 36 = \mathbf{123\text{ years}}$.

---

### 🔹 QUESTION 25 (IBPS / SBI PO Prelims 2024)
**Topic:** Fractional Multipliers & Shifting Ratio | **Concept:** Step-by-Step Age Reconstruction

**English:**  
The ratio between the age of Rohan 8 years ago and the age of Kunal after 9 years is $4 : y$. The average present age of Rohan and Kunal is 32 years, while the average present age of Rohan and Meera is 31 years. If, after 9 years, Kunal will be $5/4$ times his present age, find Meera's age after $(y)$ years.

**हिन्दी:**  
8 वर्ष पहले रोहन की आयु और 9 वर्ष बाद कुणाल की आयु के बीच का अनुपात $4 : y$ है। रोहन और कुणाल की औसत वर्तमान आयु 32 वर्ष है, जबकि रोहन और मीरा की औसत वर्तमान आयु 31 वर्ष है। यदि, 9 वर्ष बाद, कुणाल अपनी वर्तमान आयु का $5/4$ गुना हो जाएगा, तो $(y)$ वर्ष के बाद मीरा की आयु ज्ञात कीजिए।

**Options:**  
a) 36 years  
b) 39 years  
c) 43 years  
d) 45 years  
e) 48 years  

**Correct Answer:** **c) 43 years**

---

#### 🎯 Kaushik Sir's Approach:
1. **Find Kunal's Present Age ($K$):**
   $$K + 9 = \frac{5}{4}K \implies 9 = \frac{1}{4}K \implies K = 36\text{ years}$$
2. **Find Rohan's Present Age ($R$):**
   $$R + K = 2 \times 32 = 64 \implies R = 64 - 36 = 28\text{ years}$$
3. **Find Meera's Present Age ($M$):**
   $$R + M = 2 \times 31 = 62 \implies M = 62 - 28 = 34\text{ years}$$
4. **Find $y$ from the Ratio Condition:**
   - Rohan 8 years ago $= 28 - 8 = 20\text{ years}$.
   - Kunal after 9 years $= 36 + 9 = 45\text{ years}$.
   $$\frac{\text{Rohan}_{-8}}{\text{Kunal}_{+9}} = \frac{20}{45} = \frac{4}{9} = \frac{4}{y} \implies y = 9$$
5. **Meera's Age after $y$ ($=9$) Years:**
   $$\text{Meera's Future Age} = 34 + 9 = \mathbf{43\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $K + 9 = 1.25K \implies 0.25K = 9 \implies K = 36$.
- $R = 64 - 36 = 28$.
- $M = 62 - 28 = 34$.
- $\frac{R - 8}{K + 9} = \frac{28 - 8}{36 + 9} = \frac{20}{45} = \frac{4}{9} \implies y = 9$.
- Meera's age after $y$ years $= M + y = 34 + 9 = \mathbf{43\text{ years}}$.

---

### 🔹 QUESTION 26
**Topic:** Multi-Period Ages Puzzle | **Concept:** Base Shifting & Mean Offsets

**English:**  
The age of Rohan 10 years ago was three times the age of Kunal at that time. Rohan's age after 6 years will be twice Kunal's age after 8 years. If Meera's present age is 7 years less than the average present age of Rohan and Kunal, find Meera's present age.

**हिन्दी:**  
10 साल पहले रोहन की उम्र, उस समय कुणाल की उम्र की तीन गुनी थी। 6 साल बाद रोहन की उम्र, 8 साल बाद कुणाल की उम्र की दोगुनी होगी। अगर मीरा की वर्तमान उम्र, रोहन और कुणाल की वर्तमान औसत उम्र से 7 साल कम है, तो मीरा की वर्तमान उम्र पता करें।

**Options:**  
a) 33 years  
b) 43 years  
c) 53 years  
d) 63 years  
e) None of these  

**Correct Answer:** **b) 43 years**

---

#### 🎯 Kaushik Sir's Approach:
1. **Define Timeline from 10 Years Ago:**
   - 10 years ago: Let Kunal $= x$, Rohan $= 3x$.
   - Present ages: Kunal $= x + 10$, Rohan $= 3x + 10$.
2. **Apply Future Condition:**
   - Rohan after 6 years $= (3x + 10) + 6 = 3x + 16$.
   - Kunal after 8 years $= (x + 10) + 8 = x + 18$.
   $$3x + 16 = 2(x + 18)$$
   $$3x + 16 = 2x + 36 \implies x = 20$$
3. **Calculate Present Ages:**
   - Rohan $= 3(20) + 10 = 70\text{ years}$.
   - Kunal $= 20 + 10 = 30\text{ years}$.
4. **Find Meera's Present Age:**
   $$\text{Average of Rohan & Kunal} = \frac{70 + 30}{2} = 50\text{ years}$$
   $$\text{Meera's Age} = 50 - 7 = \mathbf{43\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $(R - 10) = 3(K - 10) \implies R - 3K = -20 \quad \text{--- (1)}$
- $(R + 6) = 2(K + 8) \implies R - 2K = 10 \quad \text{--- (2)}$
- Subtracting (1) from (2): $K = 30\text{ years}$.
- From (2): $R = 2(30) + 10 = 70\text{ years}$.
- $M = \frac{R + K}{2} - 7 = \frac{70 + 30}{2} - 7 = 50 - 7 = \mathbf{43\text{ years}}$.

---

### 🔹 QUESTION 27
**Topic:** 3-Person Ratio System | **Concept:** Linear Ratio Expansion

**English:**  
The ratio of the present ages of Rohan and Kunal is $5 : 9$. The average age of Rohan and Meera is equal to Kunal's present age. If Rohan's age 5 years ago was 25% of Meera's age after 8 years, then find Kunal's age after 9 years.

**हिन्दी:**  
रोहन और कुणाल की वर्तमान उम्र का अनुपात $5 : 9$ है। रोहन और मीरा की औसत उम्र कुणाल की वर्तमान उम्र के बराबर है। अगर 5 साल पहले रोहन की उम्र, 8 साल बाद मीरा की उम्र का 25% थी, तो 9 साल बाद कुणाल की उम्र क्या होगी?

**Options:**  
a) 27 years  
b) 36 years  
c) 45 years  
d) 54 years  
e) None of these  

**Correct Answer:** **c) 45 years**

---

#### 🎯 Kaushik Sir's Approach:
1. **Express Ages in terms of $x$:**
   - Rohan $= 5x$, Kunal $= 9x$.
   - $\text{Avg}(R, M) = K \implies \frac{5x + M}{2} = 9x \implies 5x + M = 18x \implies M = 13x$.
   - Ratio $R : K : M = 5 : 9 : 13$.
2. **Apply Percentage Condition ($25\% = \frac{1}{4}$):**
   $$R - 5 = \frac{1}{4}(M + 8)$$
   $$5x - 5 = \frac{1}{4}(13x + 8)$$
   $$4(5x - 5) = 13x + 8$$
   $$20x - 20 = 13x + 8 \implies 7x = 28 \implies x = 4$$
3. **Kunal's Age After 9 Years:**
   $$\text{Present Kunal} = 9x = 9(4) = 36\text{ years}$$
   $$\text{Kunal after 9 years} = 36 + 9 = \mathbf{45\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $R = 5x, K = 9x \implies M = 2(9x) - 5x = 13x$.
- $5x - 5 = 0.25(13x + 8) = 3.25x + 2$.
- $1.75x = 7 \implies \frac{7}{4}x = 7 \implies x = 4$.
- Kunal's future age $= 9(4) + 9 = 36 + 9 = \mathbf{45\text{ years}}$.

---

### 🔹 QUESTION 28
**Topic:** Forward/Backward Time Walking | **Concept:** Unit Scaling Across Time

**English:**  
Rohan's age after 10 years will be 68 years. The ratio of the ages of Rohan and Kunal 6 years ago was $13 : 8$. If Kunal's age after 4 years will be 10 years less than Meera's age 4 years ago, then find Meera's present age.

**हिन्दी:**  
10 साल बाद रोहन की उम्र 68 साल होगी। 6 साल पहले रोहन और कुणाल की उम्र का अनुपात $13 : 8$ था। अगर 4 साल बाद कुणाल की उम्र, 4 साल पहले मीरा की उम्र से 10 साल कम होगी, तो मीरा की वर्तमान उम्र पता करें।

**Options:**  
a) 46 years  
b) 50 years  
c) 52 years  
d) 56 years  
e) None of these  

**Correct Answer:** **d) 56 years**

---

#### 🎯 Kaushik Sir's Approach:
1. **Find Rohan's Timeline:**
   - Rohan Present Age $= 68 - 10 = 58\text{ years}$.
   - Rohan 6 years ago $= 58 - 6 = 52\text{ years}$.
2. **Find Kunal's Age from Ratio 6 Years Ago ($13 : 8$):**
   $$13\text{ units} = 52\text{ years} \implies 1\text{ unit} = 4\text{ years}$$
   $$\text{Kunal 6 years ago} = 8 \times 4 = 32\text{ years}$$
   $$\text{Kunal Present Age} = 32 + 6 = 38\text{ years}$$
3. **Apply Meera's Condition:**
   - Kunal after 4 years $= 38 + 4 = 42\text{ years}$.
   $$\text{Kunal}_{+4} = \text{Meera}_{-4} - 10$$
   $$42 = (M - 4) - 10 \implies M - 4 = 52 \implies M = \mathbf{56\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $R = 68 - 10 = 58$.
- $\frac{R - 6}{K - 6} = \frac{13}{8} \implies \frac{52}{K - 6} = \frac{13}{8} \implies K - 6 = 32 \implies K = 38$.
- $K + 4 = 42$.
- $42 = (M - 4) - 10 \implies M = 42 + 14 = \mathbf{56\text{ years}}$.

---

### 🔹 QUESTION 29
**Topic:** Fractional Ratio Scaling | **Concept:** Clearing Decimal Ratios

**English:**  
The ratio of the present ages of Rohan and Kunal is $3 : 7$. The sum of the present ages of Kunal and Meera is 4.5 times Rohan's present age. If Rohan's age after 5 years will be 10 years less than $3/4^{\text{th}}$ of Meera's present age, then find the difference between the present ages of Kunal and Meera.

**हिन्दी:**  
रोहन और कुणाल की वर्तमान उम्र का अनुपात $3 : 7$ है। कुणाल और मीरा की वर्तमान उम्र का योग रोहन की वर्तमान उम्र का 4.5 गुना है। अगर 5 साल बाद रोहन की उम्र मीरा की वर्तमान उम्र के $3/4$ हिस्से से 10 साल कम होगी, तो कुणाल और मीरा की वर्तमान उम्र के बीच का अंतर पता करें।

**Options:**  
a) 2 years  
b) 3 years  
c) 4 years  
d) 5 years  
e) 6 years  

**Correct Answer:** **c) 4 years**

---

#### 🎯 Kaushik Sir's Approach (Integer Scaling):
1. **Ratio Setup:**
   - Let Rohan $= 3x$, Kunal $= 7x$.
   - $K + M = 4.5 R = 4.5(3x) = 13.5x \implies M = 13.5x - 7x = 6.5x$.
   - Multiply by 2 to get clean integer ratio units:
     $$R : K : M = 6k : 14k : 13k$$
2. **Apply Rohan-Meera Condition:**
   $$R + 5 = \frac{3}{4}M - 10$$
   $$6k + 5 = \frac{3}{4}(13k) - 10$$
   $$6k + 15 = \frac{39k}{4}$$
   $$4(6k + 15) = 39k \implies 24k + 60 = 39k \implies 15k = 60 \implies k = 4$$
3. **Difference between Kunal and Meera:**
   $$\text{Difference} = |14k - 13k| = 1k = 1(4) = \mathbf{4\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $R = 3x, K = 7x, M = 6.5x$.
- $3x + 5 = \frac{3}{4}(6.5x) - 10 \implies 3x + 15 = \frac{19.5x}{4} = 4.875x$.
- $1.875x = 15 \implies \frac{15}{8}x = 15 \implies x = 8$.
- Difference between $K$ and $M = 7x - 6.5x = 0.5x = 0.5(8) = \mathbf{4\text{ years}}$.

---

## 📌 SET 6: AGES — COMPLEX SYSTEMS, BIRTH TIMELINES & NON-LINEAR RELATIONS (Q30 – Q36)

---

### 🔹 QUESTION 30
**Topic:** Birth Timeline & 4-Member Family | **Concept:** Relative Origin Point

**English:**  
When Aarav was born, his father's age was twice the age of his elder brother at that time, while his mother was 20 years older than his elder brother. If Aarav's present age is 12 years and the present average age of all four family members is 40 years, find the ratio of the father's age 6 years hence to the elder brother's age 9 years hence.

**हिन्दी:**  
जब आरव का जन्म हुआ, तब उसके पिता की उम्र उसके बड़े भाई की उम्र से दोगुनी थी, जबकि उसकी माँ उसके बड़े भाई से 20 साल बड़ी थीं। अगर आरव की अभी की उम्र 12 साल है और परिवार के सभी चार सदस्यों की अभी की औसत उम्र 40 साल है, तो पिता की 6 साल बाद की उम्र और बड़े भाई की 9 साल बाद की उम्र का अनुपात पता करें।

**Options:**  
a) 55 : 32  
b) 16 : 11  
c) 32 : 17  
d) 18 : 11  
e) None of these  

**Correct Answer:** **b) 16 : 11**

---

#### 🎯 Kaushik Sir's Approach (Birth Origin Timeline):
1. **Ages at Aarav's Birth (12 Years Ago):**
   - Aarav $= 0$
   - Let Elder Brother $= x$
   - Father $= 2x$
   - Mother $= x + 20$
2. **Shift to Present Day (+12 Years for Everyone):**
   - Aarav $= 12$
   - Elder Brother $= x + 12$
   - Father $= 2x + 12$
   - Mother $= x + 20 + 12 = x + 32$
3. **Present Total Sum Equation ($4 \times 40 = 160$):**
   $$12 + (x + 12) + (2x + 12) + (x + 32) = 160$$
   $$4x + 68 = 160 \implies 4x = 92 \implies x = 23$$
4. **Calculate Target Future Ages:**
   - Present Father $= 2(23) + 12 = 58\text{ years} \implies \text{Father}_{+6} = 58 + 6 = 64\text{ years}$.
   - Present Brother $= 23 + 12 = 35\text{ years} \implies \text{Brother}_{+9} = 35 + 9 = 44\text{ years}$.
5. **Required Ratio:**
   $$\text{Ratio} = 64 : 44 = \mathbf{16 : 11}$$

---

#### 📘 Basic / Algebraic Approach:
- Total family age today $= 4 \times 40 = 160$.
- Total family age 12 years ago $= 160 - (4 \times 12) = 160 - 48 = 112$.
- 12 years ago (at birth): $A = 0$, $B = x$, $F = 2x$, $M = x + 20$.
  $$0 + x + 2x + (x + 20) = 112 \implies 4x + 20 = 112 \implies 4x = 92 \implies x = 23$$
- Today: $F = 2(23) + 12 = 58$, $B = 23 + 12 = 35$.
- Future ratio: $\frac{58 + 6}{35 + 9} = \frac{64}{44} = \mathbf{\frac{16}{11}}$.

---

### 🔹 QUESTION 31
**Topic:** Two-Variable Algebraic Ages | **Concept:** Simultaneous Offsets

**English:**  
The age of Rohan three years ago and the age of Kunal five years hence are $(2.4y)$ years and $(3.6y)$ years respectively. If Kunal is $(x)$ years older than Rohan, find the value of $(x)$, given that the average age of Rohan and Kunal four years ago was 25 years.

**हिन्दी:**  
तीन साल पहले रोहन की उम्र और पाँच साल बाद कुणाल की उम्र क्रमशः $(2.4y)$ साल और $(3.6y)$ साल हैं। अगर कुणाल, रोहन से $(x)$ साल बड़ा है, तो $(x)$ का मान ज्ञात कीजिए, जबकि चार साल पहले रोहन और कुणाल की औसत उम्र 25 साल थी।

**Options:**  
a) 3 years  
b) 4 years  
c) 5 years  
d) 6 years  
e) Can't be determined  

**Correct Answer:** **b) 4 years**

---

#### 🎯 Kaushik Sir's Approach:
1. **Find Present Sum of Ages ($R + K$):**
   - 4 years ago, Average $= 25 \implies \text{Sum 4 yrs ago} = 2 \times 25 = 50$.
   - $\text{Present Sum } (R + K) = 50 + (2 \times 4) = 58\text{ years}$.
2. **Express Present Ages in Terms of $y$:**
   - Rohan 3 years ago $= 2.4y \implies R = 2.4y + 3$.
   - Kunal 5 years hence $= 3.6y \implies K = 3.6y - 5$.
3. **Solve for $y$ using Present Sum:**
   $$(2.4y + 3) + (3.6y - 5) = 58$$
   $$6.0y - 2 = 58 \implies 6y = 60 \implies y = 10$$
4. **Find Present Ages and Difference $(x)$:**
   - Rohan $= 2.4(10) + 3 = 27\text{ years}$.
   - Kunal $= 3.6(10) - 5 = 31\text{ years}$.
   $$x = K - R = 31 - 27 = \mathbf{4\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $R - 3 = 2.4y \implies R = 2.4y + 3$
- $K + 5 = 3.6y \implies K = 3.6y - 5$
- $\frac{(R - 4) + (K - 4)}{2} = 25 \implies R + K - 8 = 50 \implies R + K = 58$
- $(2.4y + 3) + (3.6y - 5) = 58 \implies 6y = 60 \implies y = 10$
- $R = 27, K = 31 \implies x = K - R = 31 - 27 = \mathbf{4\text{ years}}$.

---

### 🔹 QUESTION 32
**Topic:** Invariant Difference & Unknown Future Time | **Concept:** Constant Gap Rule

**English:**  
The age of Rohan after $(x)$ years will be $3/4^{\text{th}}$ of Kunal's age at that time. Kunal is 6 years younger than Meera, and the ratio of the ages of Kunal and Meera after 6 years will be $11 : 13$. If the average of the present ages of Rohan and Meera is 25 years, find the value of $(x)$.

**हिन्दी:**  
$(x)$ साल बाद रोहन की उम्र, उस समय कुणाल की उम्र की $3/4$ होगी। कुणाल, मीरा से 6 साल छोटा है, और 6 साल बाद कुणाल और मीरा की उम्र का अनुपात $11 : 13$ होगा। अगर रोहन और मीरा की वर्तमान उम्र का औसत 25 साल है, तो $(x)$ का मान ज्ञात कीजिए।

**Options:**  
a) 13 years  
b) 12 years  
c) 11 years  
d) 10 years  
e) 9 years  

**Correct Answer:** **a) 13 years**

---

#### 🎯 Kaushik Sir's Approach (Invariant Difference Shortcut):
1. **Find Kunal and Meera's Present Ages:**
   - The age difference between Meera and Kunal is **always 6 years**.
   - Ratio after 6 years $= 11 : 13 \implies \text{Unit difference} = 13 - 11 = 2\text{ units}$.
   $$2\text{ units} = 6\text{ years} \implies 1\text{ unit} = 3\text{ years}$$
   - Kunal after 6 years $= 11 \times 3 = 33 \implies \text{Present Kunal } K = 33 - 6 = 27\text{ years}$.
   - Meera after 6 years $= 13 \times 3 = 39 \implies \text{Present Meera } M = 39 - 6 = 33\text{ years}$.
2. **Find Rohan's Present Age ($R$):**
   - Present Average of Rohan and Meera $= 25\text{ years} \implies R + M = 50$.
   $$R = 50 - 33 = 17\text{ years}$$
3. **Find $(x)$ using the Future Ratio ($3 : 4$):**
   $$\frac{R + x}{K + x} = \frac{3}{4}$$
   $$\frac{17 + x}{27 + x} = \frac{3}{4}$$
   $$4(17 + x) = 3(27 + x)$$
   $$68 + 4x = 81 + 3x \implies x = \mathbf{13\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- $M - K = 6$.
- $\frac{K + 6}{M + 6} = \frac{11}{13} \implies 13K + 78 = 11(K + 6) + 78 = 11K + 144 \implies 2K = 54 \implies K = 27$.
- $M = 27 + 6 = 33$.
- $\frac{R + M}{2} = 25 \implies R = 50 - 33 = 17$.
- $17 + x = \frac{3}{4}(27 + x) \implies 68 + 4x = 81 + 3x \implies x = \mathbf{13\text{ years}}$.

---

### 🔹 QUESTION 33
**Topic:** Multi-Variable Ages System | **Concept:** Aggregate Shift Sum

**English:**  
The sum of Rohan's age after 7 years, Kunal's age 4 years ago, and Meera's age after 5 years is $(x)$ years. Rohan is 8 years older than Kunal, while Meera's present age is 6 years more than $2/3^{\text{rd}}$ of Rohan's present age. If the sum of Rohan's present age and Meera's age after 9 years is 55 years, find the value of $(x)$.

**हिन्दी:**  
रोहन की 7 साल बाद की उम्र, कुणाल की 4 साल पहले की उम्र और मीरा की 5 साल बाद की उम्र का योग $(x)$ साल है। रोहन, कुणाल से 8 साल बड़ा है, जबकि मीरा की वर्तमान उम्र रोहन की वर्तमान उम्र के $2/3$ हिस्से से 6 साल ज़्यादा है। अगर रोहन की वर्तमान उम्र और मीरा की 9 साल बाद की उम्र का योग 55 साल है, तो $(x)$ का मान ज्ञात कीजिए।

**Options:**  
a) 50  
b) 60  
c) 70  
d) 80  
e) 90  

**Correct Answer:** **c) 70**

---

#### 🎯 Kaushik Sir's Approach:
1. **Solve for Rohan ($R$) and Meera ($M$):**
   - Condition 3: $R + (M + 9) = 55 \implies R + M = 46$.
   - Condition 2: $M = \frac{2}{3}R + 6$.
   - Substitute $M$:
     $$R + \left(\frac{2}{3}R + 6\right) = 46 \implies \frac{5}{3}R = 40 \implies R = 24\text{ years}$$
   - Then $M = 46 - 24 = 22\text{ years}$.
2. **Find Kunal ($K$):**
   - Condition 1: $R - K = 8 \implies K = 24 - 8 = 16\text{ years}$.
3. **Calculate $(x)$:**
   $$\text{Present Sum} = R + K + M = 24 + 16 + 22 = 62\text{ years}$$
   $$\text{Net Time Shift} = +7 - 4 + 5 = +8\text{ years}$$
   $$x = \text{Present Sum} + \text{Net Shift} = 62 + 8 = \mathbf{70}$$

---

#### 📘 Basic / Algebraic Approach:
- $R + M = 46$.
- $M = \frac{2}{3}R + 6 \implies R + \frac{2}{3}R + 6 = 46 \implies \frac{5}{3}R = 40 \implies R = 24$.
- $M = 22$, $K = 24 - 8 = 16$.
- $x = (R + 7) + (K - 4) + (M + 5) = (24 + 7) + (16 - 4) + (22 + 5) = 31 + 12 + 27 = \mathbf{70}$.

---

### 🔹 QUESTION 34
**Topic:** Non-Linear Age Relations | **Concept:** Quadratic Factorization & Integer Root

**English:**  
The ratio of the present ages of Rohan and Kunal is $17 : 3$. Four years ago, Kunal's age was equal to the square root of Rohan's age at that time. Find Kunal's present age, given that both ages are integers.

**हिन्दी:**  
रोहन और कुणाल की वर्तमान आयु का अनुपात $17 : 3$ है। चार वर्ष पहले, कुणाल की आयु उस समय रोहन की आयु के वर्गमूल के बराबर थी। कुणाल की वर्तमान आयु ज्ञात कीजिए, यह देखते हुए कि दोनों आयु पूर्णांक हैं।

**Options:**  
a) 12 years  
b) 15 years  
c) 18 years  
d) 21 years  
e) 24 years  

**Correct Answer:** **a) 12 years**

---

#### 🎯 Kaushik Sir's Approach (Option Elimination & Quadratic):
1. **Option Elimination (Speed Technique):**
   - Present age of Kunal must be a multiple of 3.
   - If Kunal $= 12$ ($x = 4$):
     - Rohan $= 17 \times 4 = 68$.
     - 4 years ago: Kunal $= 12 - 4 = 8$, Rohan $= 68 - 4 = 64$.
     - Is $8 = \sqrt{64}$? **YES!** (Direct match in 5 seconds).
2. **Mathematical Formulation:**
   - Present ages: Rohan $= 17x$, Kunal $= 3x$.
   - 4 years ago: Kunal $= 3x - 4$, Rohan $= 17x - 4$.
   $$3x - 4 = \sqrt{17x - 4}$$
   $$(3x - 4)^2 = 17x - 4$$
   $$9x^2 - 24x + 16 = 17x - 4 \implies 9x^2 - 41x + 20 = 0$$
   $$9x^2 - 36x - 5x + 20 = 0 \implies (9x - 5)(x - 4) = 0$$
   Since ages are integers, $x = 4$.
   $$\text{Kunal's Present Age} = 3(4) = \mathbf{12\text{ years}}$$

---

#### 📘 Basic / Algebraic Approach:
- Let $R = 17x, K = 3x$.
- $(3x - 4)^2 = 17x - 4 \implies 9x^2 - 41x + 20 = 0$.
- Quadratic formula:
  $$x = \frac{41 \pm \sqrt{(-41)^2 - 4(9)(20)}}{2(9)} = \frac{41 \pm \sqrt{1681 - 720}}{18} = \frac{41 \pm \sqrt{961}}{18} = \frac{41 \pm 31}{18}$$
  $$x = \frac{72}{18} = 4 \quad \text{or} \quad x = \frac{10}{18} = \frac{5}{9}\text{ (rejected)}$$
- $\text{Kunal's Age} = 3(4) = \mathbf{12\text{ years}}$.

---

### 🔹 QUESTION 35
**Topic:** Arithmetic Progression in Ages | **Concept:** AP Symmetry in 4 Terms

**English:**  
The present average age of four friends Rohan, Kunal, Meera and Tanya is $(x)$ years. Their present ages are in arithmetic progression in the same order. Tanya is 8 years older than Kunal, and the sum of the ages of Rohan and Meera after 5 years will be 70 years. Find the value of $(x)$.

**हिन्दी:**  
चार दोस्तों - रोहन, कुणाल, मीरा और तान्या - की वर्तमान औसत आयु $(x)$ वर्ष है। उनकी वर्तमान आयु इसी क्रम में एक समांतर श्रेणी (arithmetic progression) में है। तान्या, कुणाल से 8 वर्ष बड़ी है, और 5 वर्ष के बाद रोहन और मीरा की आयु का योग 70 वर्ष होगा। $(x)$ का मान ज्ञात कीजिए।

**Options:**  
a) 28  
b) 32  
c) 36  
d) 40  
e) None of these  

**Correct Answer:** **b) 32**

---

#### 🎯 Kaushik Sir's Approach (AP Common Difference Shortcut):
1. **Find Common Difference ($d$):**
   - Let AP terms be $R, K, M, T$ with common difference $d$.
   - Distance between Kunal ($2^{\text{nd}}$ term) and Tanya ($4^{\text{th}}$ term) is $2d$:
     $$T - K = 2d = 8 \implies d = 4\text{ years}$$
2. **Express Ages in terms of $R$:**
   - $R = y$
   - $K = y + 4$
   - $M = y + 8$
   - $T = y + 12$
3. **Use Future Sum of Rohan and Meera:**
   $$(R + 5) + (M + 5) = 70 \implies R + M + 10 = 70 \implies R + M = 60$$
   $$y + (y + 8) = 60 \implies 2y + 8 = 60 \implies 2y = 52 \implies y = 26$$
4. **Ages of the 4 Friends:**
   $$R = 26,\; K = 30,\; M = 34,\; T = 38$$
5. **Calculate Average $(x)$ via Symmetry:**
   $$x = \frac{\text{Sum of Two Middle Terms}}{2} = \frac{30 + 34}{2} = \mathbf{32}$$
   *(Or $\frac{26 + 38}{2} = 32$).*

---

#### 📘 Basic / Algebraic Approach:
- Let the 4 terms in AP be $a - 3d, a - d, a + d, a + 3d$ (Average $= a$).
  - Kunal $= a - d$, Tanya $= a + 3d$.
  - Tanya $- \text{Kunal} = 4d = 8 \implies d = 2$.
  - Rohan $= a - 3(2) = a - 6$.
  - Meera $= a + 2$.
- Condition: $(a - 6 + 5) + (a + 2 + 5) = 70 \implies 2a + 6 = 70 \implies 2a = 64 \implies a = \mathbf{32}$.

---

### 🔹 QUESTION 36
**Topic:** Birth Timeline with Sibling Ratio | **Concept:** Origin Shifting & Percentage

**English:**  
Ten years ago, Aarav's age was 25% of his mother's age, while his father's age was 125% of his mother's age. A baby girl was also born in the family at that time. If Aarav's present age is 40% of his father's present age, then after 6 years, Aarav's sister's age will be what percentage of his mother's age?

**हिन्दी:**  
दस साल पहले, आरव की उम्र उसकी माँ की उम्र का 25% थी, जबकि उसके पिता की उम्र उसकी माँ की उम्र का 125% थी। उस समय परिवार में एक बच्ची का भी जन्म हुआ था। अगर आरव की वर्तमान उम्र उसके पिता की वर्तमान उम्र का 40% है, तो 6 साल बाद, आरव की बहन की उम्र उसकी माँ की उम्र का कितना प्रतिशत होगी?

**Options:**  
a) 20%  
b) 30%  
c) 40%  
d) 50%  
e) 60%  

**Correct Answer:** **c) 40%**

---

#### 🎯 Kaushik Sir's Approach:
1. **Ratio Setup 10 Years Ago (Past):**
   - Let Mother's age $= 4u$ ($100\%$).
   - Aarav's age $= 25\% \text{ of } 4u = 1u$.
   - Father's age $= 125\% \text{ of } 4u = 5u$.
   - Sister's age $= 0$ (Born 10 years ago).
2. **Present Ages (+10 Years):**
   - Aarav $= 1u + 10$
   - Father $= 5u + 10$
   - Mother $= 4u + 10$
   - Sister $= 0 + 10 = 10\text{ years}$
3. **Solve for $u$ using Present Ratio ($40\% = \frac{2}{5}$):**
   $$1u + 10 = \frac{2}{5}(5u + 10)$$
   $$1u + 10 = 2u + 4 \implies u = 6$$
4. **Calculate Ages after 6 Years:**
   - Present Mother $= 4(6) + 10 = 34\text{ years} \implies \text{Mother after 6 yrs} = 34 + 6 = 40\text{ years}$.
   - Present Sister $= 10\text{ years} \implies \text{Sister after 6 yrs} = 10 + 6 = 16\text{ years}$.
5. **Required Percentage:**
   $$\text{Percentage} = \frac{\text{Sister's Age}}{\text{Mother's Age}} \times 100\% = \frac{16}{40} \times 100\% = \mathbf{40\%}$$

---

#### 📘 Basic / Algebraic Approach:
- 10 years ago: $M = 4u, A = u, F = 5u, S = 0$.
- Today: $A = u + 10, F = 5u + 10, M = 4u + 10, S = 10$.
- $u + 10 = 0.4(5u + 10) = 2u + 4 \implies u = 6$.
- Today: $M = 34, S = 10$.
- 6 years hence: $M = 40, S = 16$.
- $\text{Percentage} = \frac{16}{40} \times 100 = \mathbf{40\%}$.

---


# 3. SPEED DRILL & EXAM CHEATSHEET

---

## ⚡ 10 Golden Rules for 20-Second Exam Solving

```
  ┌────────────────────────────────────────────────────────────────────────┐
  │                   AVERAGE & AGES SPEED CHEATSHEET                      │
  ├────────────────────────────────────────────────────────────────────────┤
  │ 1. ASSUMED MEAN RULE: Actual Avg = Base + (Net Deviation / n)          │
  │ 2. REPLACEMENT INVARIANCE: Sum(New) - Sum(Old) = n * Delta(Avg)        │
  │ 3. INCLUSION / JOINING: Value(New) = Old Avg + (New n * Delta Avg)     │
  │ 4. EXCLUSION / LEAVING: Value(Left) = Old Avg - (New n * Delta Avg)    │
  │ 5. AP SYMMETRY: Average = (First + Last)/2 = Middle Term               │
  │ 6. EVEN TERMS IN AP: Average = (Middle_1 + Middle_2)/2                 │
  │ 7. ALLIGATION IN AVG: (n1 / n2) = |Avg2 - Combined| / |Combined - Avg1││
  │ 8. INVARIANT AGE DIFFERENCE: Age diff NEVER changes across timeline!   │
  │ 9. RATIO BALANCING: Scale ratios to equalize vertical unit changes     │
  │ 10. BOWLING AVERAGE TRAP: Lower is better! "Improves by x" = -x runs/w │
  └────────────────────────────────────────────────────────────────────────┘
```

---

## 🔍 Common Traps & How to Avoid Them

| Question Scenario | Common Mistake (Trap) | Correct Method |
| :--- | :--- | :--- |
| **Replacement of multiple members** | Dividing by $(n+2)$ or $(n-2)$ | Number of observations $n$ **remains identical** |
| **Bowling Average Improvement** | Adding $0.5$ when average improves | **Subtract $0.5$** because bowling avg improves when runs per wicket decrease |
| **Age Ratio after $T$ years** | Adding $T$ directly to ratio numbers (e.g. $2:3 \to 2+5 : 3+5$) | Multiply by common variable $x$ first: $\frac{2x+5}{3x+5}$ |
| **AP Series of Even/Odd numbers** | Assuming common difference is 1 | Consecutive even or odd numbers always have **$d = 2$** |
| **Birth Timeline Problems** | Setting birth age to 1 | At birth, the child's age is **0 years** |

---

## 🎯 Final Quick Recap Table of All 36 Questions

| Q# | Topic | Method Used | Key Formula / Step | Final Ans |
| :---: | :--- | :--- | :--- | :---: |
| **01** | Weight Replacement | Group Deficit/Surplus | $\text{Sum}_{\text{new}} = 130 + (10 \times 2) = 150 \implies 3u = 90$ | **c) 90 kg** |
| **02** | Subset Averages | Net Deviation $\sum \Delta = 0$ | $-48 + 20 = -28 \implies \text{Bal} = +28 \implies \text{Avg} = 40+14 = 54$ | **d) 54** |
| **03** | Linear Element Shifts | $\Delta\text{Sum} / n$ | $\Delta\text{Sum} = 56 - 36 = +20 \implies \Delta\text{Avg} = +2 \implies 97$ | **d) 97** |
| **04** | Variable Elimination | Simultaneous Difference | $4N = 60 \implies N = 15, S = 150 \implies \text{Avg} = 10$ | **c) 10** |
| **05** | Multiple Shifts | Invariant Mean Balance | $10X - 10 = 9X \implies X = 10$ | **a) 10** |
| **06** | Cricket Batsman Avg | Alligation Rule | $\frac{N}{3} = \frac{20-N}{2} \implies 5N = 60 \implies N = 12$ | **b) 12** |
| **07** | Chocolate Distribution | Inverse Share Surplus | $45 \times 2 = 90 \implies \text{Original Share} = \frac{90}{15} = 6$ | **b) 6** |
| **08** | Dual Inclusion System | Linear Combination | $X+Y=22$ & $3X+Y=24 \implies 2X = 2 \implies X = 1$ | **c) 1** |
| **09** | Class Weight Alligation | Alligation Proportion | $\frac{46-X}{8} = \frac{5}{4} \implies X = 36$ | **c) 36 kg** |
| **10** | Department Salaries | Net Deviation | $3(+400) + 1(-y) = 0 \implies y = 1200$ | **b) 1200** |
| **11** | Gamer Replacement | Score Drop / Member Drop | $N = \frac{32}{4} = 8$ | **c) 8** |
| **12** | Dual Constraint Alligation | Alligation + Ratio Equating | $\frac{Y-10}{Y+20} = \frac{2}{3} \implies Y = 70$ | **d) 70** |
| **13** | Consecutive AP Series | AP Symmetry | Largest A $= 46$, Smallest B $= 25 \implies \text{Sum} = 71$ | **c) 71** |
| **14** | Odd/Even AP Series | Extremes Average Invariance | Extremes Avg $= 26 \implies L = 33 \implies \text{Sum} = 3 \times 31 = 93$ | **b) 93** |
| **15** | Dual Series & Squares | Quadratic & Extreme Sum | $(2x+10)^2 = 900 \implies x = 10$, Odd $L = 21 \implies \text{Sum} = 31$ | **e) None (31)** |
| **16** | AP Distance Property | Invariant Index Shift | $\Delta T_5 - T_2 = 6 \implies 6 + 6 = 12$ | **d) 12** |
| **17** | AP Sum Linking | Middle Term Extraction | Smallest even $= 42 \implies \text{Odd } L = 35 \implies \text{Sum} = 180$ | **b) 180** |
| **18** | Even/Odd Group Decomposition| RRB PO 2023 Complement | $(180-82) - (152-68) = 98 - 84 = 14$ | **b) 14** |
| **19** | Annual Income & Savings | Assumed Mean Income | $\text{Income} = 25000, \text{Exp} = 13000 \implies \text{Sav} = 12000$ | **a) ₹12,000** |
| **20** | Multi-Variable Average | Integer Variable Scaling | $2a - 2b = 2(a - b) = 2(16) = 32$ | **d) 32** |
| **21** | Percentage Avg Increase | Quadratic Solution | $x^2 + 10x - 200 = 0 \implies x = 10 \implies \text{Avg} = 60$ | **c) 60** |
| **22** | 3-Person Height System | Pairwise Subtraction | $Y = 155 \implies D + F = 165 + 135 = 300$ | **d) 300 cm** |
| **23** | Multi-Person Ages | Direct Replacement | $M + T = 182 \implies \text{Avg} = 91 + 4 = 95$ | **d) 95** |
| **24** | 3-Person Ages Ratio | Ratio Merging & Percentage | $R:K:M = 6:15:8 \implies x=3 \implies \text{Sum}_{+12} = 123$ | **d) 123** |
| **25** | Fractional Age Multiplier | PO Prelims 2024 Step-by-Step | $K = 36, R = 28, M = 34, y = 9 \implies M+9 = 43$ | **c) 43 years** |
| **26** | Ages Timeline Shift | Linear Equation Elimination | $x = 20 \implies R = 70, K = 30 \implies M = 50-7 = 43$ | **b) 43 years** |
| **27** | 3-Person Ages Ratio | Fractional Unit Balance | $R:K:M = 5:9:13 \implies x = 4 \implies K_{+9} = 45$ | **c) 45 years** |
| **28** | Time Walking | Backward Unit Matching | $R=58, R_{-6}=52 \implies K_{-6}=32 \implies K_{+4}=42 \implies M=56$ | **d) 56 years** |
| **29** | Fractional Scaling | Scaled Integer Units | $R:K:M = 6k:14k:13k \implies k=4 \implies \text{Diff} = 4$ | **c) 4 years** |
| **30** | Birth Timeline | Relative Shift from Origin | Birth: $4x+20=112 \implies x=23 \implies 64:44 = 16:11$ | **b) 16 : 11** |
| **31** | Algebraic Ages Offsets | Sum Matching | $6y - 2 = 58 \implies y = 10 \implies x = 31 - 27 = 4$ | **b) 4 years** |
| **32** | Invariant Age Difference | Gap Preservation Rule | $\Delta K,M = 6 \implies K=27, M=33, R=17 \implies x = 13$ | **a) 13 years** |
| **33** | Multi-Variable Ages Sum | Aggregate Shift Sum | $R=24, M=22, K=16 \implies \text{Sum} = 62 + 8 = 70$ | **c) 70** |
| **34** | Non-Linear Ages | Quadratic & Integer Root | $(3x-4)^2 = 17x-4 \implies x=4 \implies K = 12$ | **a) 12 years** |
| **35** | AP in Ages | AP Symmetry | $d=4 \implies y=26 \implies \text{Ages: } 26,30,34,38 \implies \text{Avg} = 32$ | **b) 32** |
| **36** | Birth Timeline & Ratio | Timeline Base Shift | $u = 6 \implies S_{+6} = 16, M_{+6} = 40 \implies \frac{16}{40} = 40\%$ | **c) 40%** |

---

> 🎓 **Best Wishes for Your Banking & Insurance Exams!**  
> *Master these concepts, avoid the common traps, and practice with high-speed mental deviation techniques.*
