# Part 2: Case Study Analysis (40%)

## Case 1: Biased Hiring Tool

### Scenario Analysis: Amazon's AI Recruiting Tool

**Source of Bias Identification:**
The bias originated from **training data** that reflected historical hiring patterns where male candidates were predominantly selected for technical roles over a 10-year period. The algorithm learned to penalize resumes containing words associated with women (e.g., "women's chess club captain").

### Three Proposed Fixes:

1. **Data Rebalancing and Augmentation**
   - Create balanced training datasets with equal representation across genders
   - Use synthetic data generation to supplement underrepresented groups
   - Remove gendered language and identifiers from training data

2. **Algorithmic Debiasing Techniques**
   - Implement fairness constraints during model training
   - Use adversarial debiasing to minimize correlation between protected attributes and predictions
   - Apply post-processing calibration to equalize outcomes across groups

3. **Human-in-the-Loop Validation**
   - Establish diverse review committees for AI recommendations
   - Implement mandatory human oversight for final hiring decisions
   - Create feedback loops to continuously monitor and correct biased outcomes

### Fairness Evaluation Metrics:

- **Demographic Parity**: Equal selection rates across gender groups
- **Equal Opportunity**: Equal true positive rates for qualified candidates
- **Calibration**: Prediction scores should reflect actual hiring success rates equally across groups

## Case 2: Facial Recognition in Policing

### Scenario Analysis: Facial Recognition Bias in Law Enforcement

### Ethical Risks Identified:

1. **Wrongful Arrests and Prosecutions**
   - Higher false positive rates for minorities leading to innocent people being detained
   - Erosion of presumption of innocence due to algorithmic "evidence"

2. **Privacy and Civil Liberties Violations**
   - Mass surveillance capabilities infringing on freedom of movement
   - Chilling effect on peaceful assembly and protest participation

3. **Systemic Discrimination Amplification**
   - Reinforcing existing racial biases in policing practices
   - Disproportionate targeting of minority communities

### Recommended Deployment Policies:

1. **Technical Standards and Auditing**
   - Mandatory accuracy thresholds across all demographic groups
   - Regular third-party bias audits and public reporting
   - Prohibition of use until accuracy parity is achieved

2. **Legal and Procedural Safeguards**
   - Facial recognition results cannot be sole basis for arrest
   - Require additional corroborating evidence before action
   - Establish clear legal frameworks and judicial oversight

3. **Transparency and Accountability Measures**
   - Public disclosure of system capabilities and limitations
   - Community oversight boards with veto power over deployment
   - Mandatory training for officers on system biases and proper use