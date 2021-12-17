# MOTIVATION
The motivation behind this project is to identify the lifestyle factors that are most correlated with melanoma prevalence in the U.S. The significance of this work is evident by the large market for sun care products (estimated globally as ~10 billion USD in 2019), and the >100 million USD yearly cost to public and private insurers to diagnose and treat melanoma. More importantly, melanoma is the most deadly form of skin cancer and the most preventable. 

**The overall goals are as follows:**
1) Evaluate the relationship between various factors on the incidence of melanoma in the U.S. This will be accomplished by plotting U.S county data in a choropleth map. Notably, the primary factor that is considered for melanoma prevention is minimizing UV exposure. The first relation that will be explored is the degree to which UV intensity at any one county is predictive of melanoma rates.

2) A machine learning model will be developed in an attempt to derive a predictive relationship between selected features and melanoma incidence.

3) An interactive portal showing these findings will be developed to enable community access to the results.

**Future Directions:**

4) A real-time predictor of cumulative lifetime risk given current conditions for a particular zip code. The assumption is that salient factors that determine the melanoma incidence for a population can be used to estimate the risk for a single individual. This information is targeted towards individuals or organizations who want to increase awareness of the risk of sun exposure.

5) To promote healthy sun exposure, the amount of vitamin D that can be produced in the skin, and the time before sunburn is expected to occur will also be provided. This information is calculated from live UV data.

6) Using convolutional neural networks, an image recognition model can be developed to track the progress of moles and other skin lesions. The goal would be to augment the real-time UV intensity reporting, and melanoma risk, with a skin diary that can be used to monitor skin features and provide an early warning. 

**Interactive Access**
If you'd like to see the code live, you can access a live binder at https://mybinder.org/v2/gh/igpall/tdi2021/main

Any comments/ideas are welcome, particularly regarding dataset sourcing.
