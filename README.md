# Replication Package for Automatically Estimating the Effort Required to Repay Self-Admitted Technical Debt

##### Authors: Yikun Li, Mohamed Soliman, and Paris Avgeriou


## Description of This Study

Technical debt refers to the consequences of sub-optimal decisions made during software development that prioritize short-term benefits over long-term maintainability.
*Self-Admitted Technical Debt* (SATD) is a specific form of technical debt, explicitly documented by developers within software artifacts such as source code comments and commit messages.
As SATD can hinder software development and maintenance, it is crucial to address and prioritize it effectively.
However, current methodologies lack the ability to automatically estimate the repayment effort of SATD based on its textual descriptions.
To address this limitation, we propose a novel approach for automatically estimating SATD repayment effort, utilizing a comprehensive dataset comprising 341,740 SATD items from 2,568,728 commits across 1,060 Apache repositories.
Our findings show that different types of SATD require varying levels of repayment effort, with code/design, requirement, and test debt demanding greater effort compared to non-SATD items, while documentation debt requires less.
We introduce and evaluate machine learning methodologies, particularly BERT and TextCNN, which outperforms classic machine learning methods and the naive baseline in estimating repayment effort.
Additionally, we summarize keywords associated with varying levels of repayment effort that occur during SATD repayment.
Our contributions aim to enhance the prioritization of SATD repayment effort and resource allocation efficiency, ultimately benefiting software development and maintainability.


## Structure of the Replication Package

The replication package includes the dataset.


## Contact

- Please use the following email addresses if you have questions:
    - :email: <yikun.li@rug.nl>
