**Name:** Deepika Senthil  
**UCSD email:** dsenthil@ucsd.edu  
**Section:** A01 (Data Valuation & Curation for Trustworthy AI)  
**Mentor:** Babak Salimi

**What is the most interesting topic covered in your domain this quarter?**  
Learning about the different distribution distance metrics and their underlying mathematics was the most interesting and foundational topic this quarter. Understanding the differences, pros, and cons of KL divergence, Wasserstein distance, and Maximum Mean Discrepancy (MMD) directly helped us analyze data valuation methods. This understanding was key to recognizing the drawbacks inherent in a framework like LAVA and appreciating how a method utilizing a more robust metric, such as KAIROS, helps effectively tackle those limitations.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
A potential investigation would be to expand the SAVAGE data injection framework to process data types other than tabular, specifically image datasets. This expansion is impactful because while LAVA and KAIROS can utilize image data, SAVAGE currently struggles to detect significant injection patterns in high-dimensional image datasets with thousands of features. This limitation currently limits our ability to create and test malicious datasets necessary for a full-scope evaluation of both LAVA and KAIROS.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
My current Quarter 1 project is an iterative process: my partner and I choose a dataset, I use SAVAGE to inject malicious datapoints, and my partner uses LAVA to try to identify them. We then switch roles and repeat the process, also switching to using KAIROS as the detection method instead of LAVA. A change I would make is to introduce a more standardized reporting phase after each detection round with LAVA or KAIROS. This phase would systematically quantify and document the specific features or patterns that the detectors flagged as malicious.

**What other techniques would you be interested in using in your project?**  
I would be interested in incorporating Shapley value-based data valuation techniques like Data-Shapley into the project. This inclusion would be valuable because it allows us to compare the effectiveness of malicious data detection across three distinct methodologies, the distribution-based metrics used by LAVA and KAIROS and the marginal contribution analysis provided by a Shapley-based method.
