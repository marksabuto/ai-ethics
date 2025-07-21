# Part 2: Case Study Analysis

## Case 1: Biased Hiring Tool

### Scenario:
Amazon developed an AI-based recruiting tool that penalized resumes containing words like **"women’s"**, **"female"**, or all-female college names.

### Source of Bias:
The AI was trained on **historical hiring data** from a male-dominated tech industry, which led the model to associate **male attributes with stronger candidates**, reinforcing existing gender biases.

### Proposed Fixes:
1. **Use Diverse and Representative Training Data**:  
   Include resumes from a more diverse pool of applicants, including women and underrepresented groups.

2. **Implement Bias Audits**:  
   Regularly audit the model using fairness metrics such as:
   - **Disparate Impact Ratio**
   - **Equal Opportunity Difference**
   - **Statistical Parity Difference**

3. **Reweight or Remove Gender-Correlated Features**:  
   Reduce the influence of features that are strongly correlated with gender (e.g., college name, certain hobbies).

### Fairness Metrics to Monitor:
- **Disparate Impact Ratio**: Measures whether one group is disproportionately favored.
- **Equal Opportunity Difference**: Ensures the model has equal true positive rates across groups.
- **Statistical Parity Difference**: Measures whether outcomes are distributed fairly across protected groups.

---

## Case 2: Facial Recognition in Policing

### Scenario:
Facial recognition systems used in law enforcement show **higher misidentification rates for minorities**, especially Black women.

### Ethical Risks:
1. **Wrongful Arrests**: Misidentification can lead to unjust legal consequences.
2. **Privacy Violations**: Mass surveillance disproportionately affects marginalized communities.
3. **Erosion of Public Trust**: Communities may lose trust in law enforcement and technology.
4. **Discriminatory Policing**: Reinforces systemic bias in criminal justice.

### Recommended Policies for Responsible Deployment:
1. **Independent Fairness Audits**:  
   Require third-party audits to evaluate accuracy and fairness before deployment.

2. **Human-in-the-Loop Requirement**:  
   Ensure that no action is taken based solely on facial recognition results without human review.

3. **Community Consent and Oversight**:  
   Engage with affected communities and establish oversight committees to ensure accountability.

4. **Transparency and Logging**:  
   Maintain detailed logs of system usage and decisions for auditing and accountability.

5. **Ban or Restrict Use in High-Risk Contexts**:  
   Avoid deployment in policing unless the system demonstrates high fairness and accuracy across all demographics.

---

## Summary

These case studies highlight how **historical data biases** and **lack of oversight** can lead to **unfair AI outcomes**. Addressing these issues requires a combination of **technical fairness checks**, **policy enforcement**, and **ethical design practices**.