---
layout: post
title: "Use Case Points."
comments: true
---

### Use Case Points (UCP)

* ####  Unadjusted Use Case Weight (UUCW)

![Unadjusted Use Case Weight](/assets/images/uucw.png)

* #### Unadjusted Actor Weight (UAW)

![Unadjusted Actor Weight](/assets/images/uaw.png)

* #### Technical Complexity Factor (TCF)

  #### TCF = 0.6 + (TF/100)

![Technical Complexity Factor](/assets/images/tcftable.png)

* #### Environmental Complexity Factor (ECF)

  #### ECF = 1.4 + (-0.03 x EF)

![Environmental Complexity Factor](/assets/images/ecftable.png)

  * #### Corresponding interpolation values (S) of Environmental Complexity Factor (ECF)

  ![Corresponding interpolation values (S) of Environmental Complexity Factor](/assets/images/ecftable2.png)

  * #### Experience Stability Estimate (ES)

  $$ES = \sum_{i=1}^8 S_i$$

  ![Environmental Complexity Factor](/assets/images/es.png)

* #### Unadjusted Use Case Weight (UUCW)

  #### UUCW = (Total No. of Simple Use Cases x 5) + (Total No. Average Use Cases x 10) + (Total No. Complex Use Cases x 15)

* #### Unadjusted Actor Weight (UAW)

  #### UAW = (Total No. of Simple Actors x 1) + (Total No. Average Actors x 2) + (Total No. Complex Actors x 3)

* #### Use Case Points (UCP)

  #### UCP = (UUCW + UAW) x TCF x ECF

* #### Estimate Effort (EE)

  #### EE = AUCPxP (Hours)

* #### Step by step Use Case Points Methods

![Use Case Points Methods](/assets/images/UseCasePointsMethod.png)

* #### Review App Demo

  * #### Create New Project

  ![Create New Project](/assets/images/project.png)

  * #### Use Case & Actor

  ![Use Case & Actor](/assets/images/usecase.png)

  * #### Technical Complexity Factor

  ![Technical Complexity Factor](/assets/images/tcf.png)

  * #### Environmental Complexity Factor

  ![Environmental Complexity Factor](/assets/images/ecf.png)

  * #### Estimate Effort

  ![Estimate Effort](/assets/images/effort.png)

* #### Source code

  [Use Case Points](https://github.com/qnDev/ktcnpm.20181/tree/master/UseCasePoint)

* #### References

  [1] [Use Case Points From Wikipedia](https://en.wikipedia.org/wiki/Use_Case_Points)

  [2] [Software cost estimation using use case points: Getting use case transactions straight](https://www.ibm.com/developerworks/rational/library/edge/09/mar09/collaris_dekker/index.html)

  [3] [UML - Use Case Diagrams](https://www.tutorialspoint.com/uml/uml_use_case_diagram.htm)
