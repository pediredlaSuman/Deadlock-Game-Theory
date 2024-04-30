### Deadlock Game Theory
---
**Game theory** is the study of mathematical models of conflict and cooperation between intelligent rational decision-makers. Game theory is mainly used in economics, political science, and psychology, as well as logic, computer science and biology.


### Table of Contents
1.[Introduction](#introduction)
2. [Game Representations](#gameRepresentations)
3. [Deadlock GameOverview](#deadlockGameOverview)
4. [Principles Used](#principlesUsed)
5. [Framework](#framework)
6. [Strategies](#strategies)
7. [Results](#results)
8. [Real life applications](#reallifeapplications)
9.[Google Colab Files](#googel-colab-files)

---
### Introduction

- Game theory-based deadlock games show situations in which self-interest collides with cooperation, offering complex strategic difficulties.
- Our research explores these dynamics by applying the ideas of strategic interactions and logical decision-making to investigate the best possible solutions.
- To find winning strategies based on payoff analysis and success qualities, a variety of strategies, including Tit for Tat and Always Cooperative, are analyzed.
  
---

### Game Representations

#### **Players**:who are decision makers
- People? Governments? Companies? Somebody employed by a Company?

#### **Actions**:what can the players do?
- They can cooperate or defeat or exit game
#### **Payoffs**:what motivates players?
- Do they care about some profit? Do they care about other players?
#### **General Deadlock payoff matrix**
- Lists what payoffs players get as a function of their actions.
- In the deadlock game example, two players face a situation where cooperation yields a higher payoff for both, but defection is the dominant strategy due to the risk of being exploited by the opponent.

|            | Cooperate | Defect    |
|------------|-----------|-----------|
| Cooperate  | 2, 2      | 0, 0      |
| Defect     | 0, 0      | 1, 1      |

In this matrix:
- If both players cooperate, they each receive a payoff of 2.
- If one player cooperates while the other defects, the cooperator receives a payoff of 0, and the defector receives a payoff of 1.
- If both players defect, they each receive a payoff of 0.
---
### Deadlock Game Overview

#### Key Points:
- **Number of Players:** 2
- **Strategies per Player:** 2
- **Total Strategies:** 4
- **Sequential Game:** No
- **Zero-Sum Game:** No
  
---
### Principles Used 

#### Rational Decision-Making:
Is fundamental in game theory, emphasizing selfish behavior to maximize utility. It clarifies strategic reasoning in impasse scenarios, aiding in anticipating and reacting to actions.

#### Strategic Interactions:
Are central in deadlock situations, modeling complex relationships. Game theory helps understand the strategic dynamics at work and predict outcomes to create workable plans.

#### Payoff Matrix:
Provides insights into possible results, quantifying payoffs for decision-making. It offers a methodical approach to evaluate outcomes and predict the conclusion of impasses.

#### Nash Equilibrium:
Denotes stable situations where no party has an incentive to change course unilaterally. Identifying Nash equilibria offers insights into possible outcomes and decision-making dynamics.

#### Cooperative and Non-cooperative Strategies:
Play crucial roles in resolving deadlocks. Cooperative strategies entail collaboration for win-win results, while non-cooperative techniques involve autonomous decision-making. Understanding their dynamics affects the chances of coming to agreements.

#### Bargaining and Negotiation:
Are essential for resolving deadlocks, allowing parties to reach agreements. Modeled by game theory, they consider variables like bargaining power and commitment tactics. Understanding these dynamics promotes collaboration and win-win solutions.


---
### Strategies Used in Deadlock Game Theory

#### Sample Strategy:
- Starts cooperatively to promote cooperation.
- Retaliates against defection but resumes collaboration for cooperation.
- Rewards cooperative behavior and penalizes defection.
- Demonstrates repercussions of non-cooperation through retribution.
- Adjusts between cooperation and retaliation as needed.
![samp3](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/15582da4-b04b-41c8-b2c3-85b8e75837ea)


#### Friedman Strategy:
- Starts with collaboration and mirrors opponent's move.
- Rewards continuous cooperation.
- Outlines penalties for malfunctioning as retaliation against defection.
- Encourages collaboration and trust by mirroring opponent's actions.
- Responds predictably to opponent's actions.
![fred3](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/7e074639-3f37-4159-aa28-b2241b7f4ce1)

#### Tit for Tat Strategy:
- Copies adversary's prior action for reciprocity and trust.
- Acts cooperatively in return for cooperation.
- Mirrors opponent's move in retaliation to defection.
- Adjusts behavior to preserve stability and balance.
![tit](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/a9a46655-047d-42a0-b385-9fff35859de1)

#### Joss Sneaky Strategy:
- Cooperates initially, then mimics opponent's move with slight misprediction.
- Gains strategic advantage by creating ambiguity and confusion.
- Modifies behavior to take advantage of opponent's actions.
- Increases unpredictability through deceit.
![joss3](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/009e9d6b-92f4-4a55-b925-189a779c0d97)

#### Graaskamp Strategy:
- Starts with cooperation to build trust.
- Defects periodically to increase profit.
- Uses hybrid defection and cooperation for tactical advantage.
- Modifies tactics based on player reactions.
![grass3](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/a9f8d19e-f7f2-4282-b6b9-7de503b4b193)

#### Tester Strategy:
- Cooperates initially to establish rapport.
- Modifies plan based on opponent's actions.
- Reacts with cooperation or defection based on opponent's behavior.
- Adjusts defection timing for maximum reward.
![tester3](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/eb82c2d4-7d3e-4bee-afcb-11d3732242e6)

#### Always Cooperative Strategy:
- Cooperates consistently to create cooperative atmosphere.
- Puts collaboration ahead of revenge.
- Establishes connection and confidence with opponent.
![ac3](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/fb9526a5-2017-45be-83fd-5b76b8740158)

#### Generous Tit for Tat Strategy:
- Encourages cooperation by copying opponent's move.
- Acts cooperatively toward opponent.
- Forgives opponent's sporadic defections.
- Strikes balance between forgiveness and reciprocity.
![geene3](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/38b10a9c-f86d-4ea6-a02c-25eae042c038)

---
### Results

1. **Effective Strategies**: Through the examination of various strategies in game theory, it was observed that strategies like Tit for Tat and its variations, along with the Sample Strategy, demonstrate a well-balanced mix of cooperation and retaliation, promoting transparency in decision-making.

![rest](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/93fca77b-99a2-4ff2-bb19-d8e95cdcc686)

2. **Strategic Complexity**: Strategies such as the Graaskamp Strategy and the Joss Sneaky Strategy introduce strategic complexity and unpredictability by incorporating periodic betrayals and unpredictable actions, respectively.

3. **Optimal Strategies**: In complex game contexts, strategies like Tit for Tat and its generous form are frequently regarded as optimal due to their combination of forgiveness and reciprocity. The Friedman Strategy and the Sample Strategy closely follow, providing clear and dependable procedures.

4. **Real-Life Applications**: Game theory insights extend beyond gaming scenarios to real-life situations, emphasizing the importance of collaboration, retribution, and forgiveness in decision-making processes. Understanding these strategic intricacies can lead to well-informed decisions and promote win-win outcomes in various domains.

5. **Cooperation in Evolution and Politics**: Cooperation has been shown to offer evolutionary advantages and promote win-win results, both in the animal kingdom and in international politics. Examples from meerkat behavior to diplomatic engagements highlight the significance of collaboration, trust-building, and open communication in achieving peaceful outcomes and ensuring societal prosperity.

  
![image](https://github.com/pediredlaSuman/Deadlock-Game-Theory/assets/141764451/e9c9db00-bcce-47a9-a801-971253712b72)


### Uploaded Files on Google Colab

1. [File 1: Deadlock_game_implementation](https://colab.research.google.com/drive/1S8gOBzfVUBjwtakFtlvNsKhpv6T7OQ1T#scrollTo=rmdgkT2MmxD5)
   

2. [File 2: Applying_GameTheory__Strategies](https://colab.research.google.com/drive/1ptIEO5FeJRCui0YPl40zJcoodFh9WCAf)

3. [File 3: Payoff_Analysis](https://colab.research.google.com/drive/1ZwJdYc5Zd67dv5M1ZViOTIQec8ufIxMl)

4. [File 4: Deadlock_Principles_Analysis ](https://colab.research.google.com/drive/1-HlL50RRA1l9hhVhKn8yb8KNN8s5sx1I)


