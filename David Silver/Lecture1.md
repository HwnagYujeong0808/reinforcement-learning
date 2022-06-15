# Introduction to Reinforcement Learning 😀

<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173747708-e405fae0-fe2a-4356-a15d-c3477550a1c4.png"></p>

## Characteristics of Reinforcement Learning
+ 기계학습에는 supervised learning, unsupervised learning, reinforcement learning 이 있다.
+ 강화학습이란 supervisor, 즉 정답을 알려주는 사람이 없이 agent가 리워드를 바탕으로 스스로 reward를 maximize 할 수 있는 정답을 찾아가는 과정이다.
+ feedback이 delay될 수 있다. 
+ 데이터를 어떻게 피팅하느냐에 따라서 데이터를 받는 방법도 달라진다. 

### Examples of Reinforcement Learning
+ 투자 포트폴리오 관리 (reward : 이윤) 
+ control power station
+ make a humanoid robot walk

### Reward
+ **cumulated reward**를 최대화하는 것, 즉 당장의 봅상보다는 미래의 받게 될 모든 보상의 총 합을 maximize 하는 것이 agent의 목적이다. 
+ **real hypothesis** : All goals can be described by the maximisation of expected cumulative reward
+ ex) 리워드를 maximize 하는 것 = 잘 걷는 것

### Agent and Environment
<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173748500-e304716e-f21e-4898-a543-521929ed971b.png"></p>

+ 매 step마다 $A_t$ 실행, $O_t$ 관찰, $R_t$ receive 하는 과정 반복

### History and State
<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173750281-6ff87be5-3128-4a93-b1d4-98de3fced73b.png"></p>

+ state 자체는 agent가 history의 정보를 가공해 다음의 상태를 결정하는 함수라고 볼 수 있다.
+ **History** is the sequence of observations, actions, rewards


<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173749953-7f5734a7-beed-437c-8fcd-570b0b3b576e.png"></p>

