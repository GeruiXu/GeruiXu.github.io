##  Autonomous Vehicle Takeover

As previously discussed, Level 3 is a watershed in autonomous driving, allowing drivers to engage in non-driving tasks while the system operates.

#d Non-Driving Tasks
In Level 3 autonomous driving, drivers are not required to engage actively in driving tasks, thus they are more inclined to participate in non-driving related tasks (also known as secondary tasks).

Non-Driving Related Tasks (NDRT) mainly involve the use of a driver’s cognitive, visual, auditory, verbal, manual, and other physiological or psychological resources. NDRTs can include verbal responses, listening to the radio, watching videos, text input, n-back tasks, and sustained attention response tasks (SuRT). Studies show that tasks occupying visual resources are used more frequently, consistent with Level 3 autonomous driving scenarios, where drivers do not need to monitor traffic conditions and can freely engage elsewhere. [Dogan et al., 2019](https://doi.org/10.1016/j.trf.2019.02.010); [Wu et al., 2022](https://doi.org/10.1016/j.aap.2022.106647)

>Dogan, E., Honnêt, V., Masfrand, S., & Guillaume, A. (2019). Effects of non-driving-related tasks on takeover performance in different takeover situations in conditionally automated driving. Transportation Research Part F: Traffic Psychology and Behaviour, 62, 494-504. https://doi.org/10.1016/j.trf.2019.02.010

>Wu, H., Wu, C., Lyu, N., & Li, J. (2022). Does a faster takeover necessarily mean it is better? A study on the influence of urgency and takeover-request lead time on takeover performance and safety. Accident Analysis and Prevention, 171, 106647. https://doi.org/10.1016/j.aap.2022.106647

#d Definition of Takeover
Autonomous Vehicle Takeover refers to the situation where a human driver must assume control from the autonomous driving system when it encounters complex or emergent circumstances.

#e Takeover Scenarios
Autonomous driving systems may issue a "Takeover Request" when they are unable to handle certain situations, such as poor road conditions, sensor malfunction, sudden construction zones, accident scenes, or other vehicles or pedestrians entering the road unexpectedly in emergency situations.

#c Discussion: The Paradox of Takeover Requests
Although research on takeover requests is increasing in academia, implementing them in the industry remains a significant challenge. It's crucial to recognize the paradox inherent in defining situations where "the system determines it cannot continue autonomous driving." The vehicle, based on sensor input data and modeling, outputs a decision (a numerical value) for both known (database) and unknown scenarios. If a machine can identify whether a takeover is needed, then it logically also has the capability to handle the unknown situation, negating the need for a takeover.

Similarly, if the environment for autonomous driving is defined manually, then the output is matched with predefined scenarios. In this case, the vehicle can only handle situations that match the known database, requiring human intervention for unmatched, unknown situations.

#c Discussion: The Safety Paradox
Furthermore, due to the attentional resources occupied by non-driving tasks, even if takeover requests are issued, drivers need longer to assume control of the vehicle. However, human response requires time, and longer takeover times mean closer proximity to danger, reducing the ability to avoid hazards even after taking over. This is especially concerning given that studies show a decline in driving performance with increased automation. [Dogan et al., 2019](https://doi.org/10.1016/j.trf.2019.02.010); [Roche et al., 2020](https://doi.org/10.1016/j.aap.2020.105588)

The primary goal of autonomous driving is to reduce human-caused dangers. If using autonomous driving leads to unavoidable risks, it contradicts the goal of traffic safety.

>Dogan, E., Honnet, V., Masfrand, S., & Guillaume, A. (2019). Effects of non-driving-related tasks on takeover performance in different takeover situations in conditionally automated driving. Transportation Research Part F-Traffic Psychology and Behaviour, 62, 494-504. https://doi.org/10.1016/j.trf.2019.02.010

>Roche, F., Thuering, M., & Trukenbrod, A. K. (2020). What happens when drivers of automated vehicles take over control in critical brake situations? Accident Analysis and Prevention, 144, Article 105588. https://doi.org/10.1016/j.aap.2020.105588

---