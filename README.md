# Kidney Transplant Analysis
matplotlib, Python, Pandas, Scipy.Stats, Numpy, Pathlib, hvplots, requests

**Challenge Synopsis:**

Our team of four students came up with a project to analyse and compare kidney transplantation between Oklahoma data and Nationwide data. This data was pulled on December 8th of 2023 at OPTN(cited below). Factors that could change kidney transplant wait times include blood types, ages, ethnicity, and gender. We determined as a group that payment time was a non-issue due to the fact that a patient must be able to pay for the transplant, blood transfusion, and follow-up treatment to be added to the wait list.

In our study we compared wait times between people living in Oklahoma and Nationwide. We used bar graphs, boxplots, and chi tests to execute comparisons.

**Our Null Hypothothesis:** Wait times are about the same for everyone who needs a kidney transplant both in Oklahoma and Nationwide.


**Challenges We Faced:**
- Data gathering
  
  - HIPPA greatly reduced our ability to gather more indepth information on patients and PII(Personal Identifiable Information)
  - Given the short timeframe for completion, [National Institute of Diabetes and Digestive and Kidney Diseases](https://www.niddk.nih.gov/) could not fulfill our request for datasets pertaining to our project.
  - The dataset we were able to obtain used a wait time range instead of numerical values for each patient. The ranges proved to be challenging in calculating statistical analysis in any capacity. These were later transposed into numerical values or medians per category.
  - The dataset kept including commas and quotations that didn't appear in the original dataset. Instead we coded a comma/quotation removal.
  - In our dataset, one person was listed multiple times based on how many ethnicities they identified with. These individuals had to be grouped together at not be counted more than once.


**Analysis and Conclusions**

As of December 8 2023 there were 88,767 people waiting for a kidney transplant in the USA. Of those 88,767, 597 of them reside in Oklahoma. We have rejected our null hypothesis finding that several factors contribute to longer wait times for receiving a kidney transplant. The demographics with the longest wait times had O blood type, were men, between the ages of 50-64, and were white/non-Hispanic. The median wait time is between 1 and 2 years for a kidney transplant no matter the variables.

**Citations:**

Contributors:

[Amanda Hinkle](https://www.linkedin.com/in/amanda-hinkle-9105941b6/)

[Barb Rupps](https://www.linkedin.com/in/barbrupps/)

[Amanda Pigman](https://www.linkedin.com/in/amanda-pigman-904558227/)

[Cory (Chapman) Houston](https://www.linkedin.com/in/cory-houston-679447147/)

Datasets acquired at: [Organ Procurement & Transplantation Network](https://optn.transplant.hrsa.gov/)

Instructor: [Othmane Benyoucef](https://www.linkedin.com/in/othmane-benyoucef-219a8637/)

Assistants: [Jacob Peroutek](https://www.linkedin.com/in/jperoutek/) [Isabella Taylor](https://www.linkedin.com/in/isabellajade/)
