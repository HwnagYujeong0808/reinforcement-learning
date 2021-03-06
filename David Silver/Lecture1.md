# Introduction to Reinforcement Learning ๐

<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173747708-e405fae0-fe2a-4356-a15d-c3477550a1c4.png"></p>

## Characteristics of Reinforcement Learning
+ ๊ธฐ๊ณํ์ต์๋ supervised learning, unsupervised learning, reinforcement learning ์ด ์๋ค.
+ ๊ฐํํ์ต์ด๋ supervisor, ์ฆ ์ ๋ต์ ์๋ ค์ฃผ๋ ์ฌ๋์ด ์์ด agent๊ฐ ๋ฆฌ์๋๋ฅผ ๋ฐํ์ผ๋ก ์ค์ค๋ก reward๋ฅผ maximize ํ  ์ ์๋ ์ ๋ต์ ์ฐพ์๊ฐ๋ ๊ณผ์ ์ด๋ค.
+ feedback์ด delay๋  ์ ์๋ค. 
+ ๋ฐ์ดํฐ๋ฅผ ์ด๋ป๊ฒ ํผํํ๋๋์ ๋ฐ๋ผ์ ๋ฐ์ดํฐ๋ฅผ ๋ฐ๋ ๋ฐฉ๋ฒ๋ ๋ฌ๋ผ์ง๋ค. 

### Examples of Reinforcement Learning
+ ํฌ์ ํฌํธํด๋ฆฌ์ค ๊ด๋ฆฌ (reward : ์ด์ค) 
+ control power station
+ make a humanoid robot walk

### Reward
+ **cumulated reward**๋ฅผ ์ต๋ํํ๋ ๊ฒ, ์ฆ ๋น์ฅ์ ๋ด์๋ณด๋ค๋ ๋ฏธ๋์ ๋ฐ๊ฒ ๋  ๋ชจ๋  ๋ณด์์ ์ด ํฉ์ maximize ํ๋ ๊ฒ์ด agent์ ๋ชฉ์ ์ด๋ค. 
+ **real hypothesis** : All goals can be described by the maximisation of expected cumulative reward
+ ex) ๋ฆฌ์๋๋ฅผ maximize ํ๋ ๊ฒ = ์ ๊ฑท๋ ๊ฒ

### Agent and Environment
<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173748500-e304716e-f21e-4898-a543-521929ed971b.png"></p>

+ ๋งค step๋ง๋ค $A_t$ ์คํ, $O_t$ ๊ด์ฐฐ, $R_t$ receive ํ๋ ๊ณผ์  ๋ฐ๋ณต

### History and State
<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173750281-6ff87be5-3128-4a93-b1d4-98de3fced73b.png"></p>

+ state ์์ฒด๋ agent๊ฐ history์ ์ ๋ณด๋ฅผ ๊ฐ๊ณตํด ๋ค์์ ์ํ๋ฅผ ๊ฒฐ์ ํ๋ ํจ์๋ผ๊ณ  ๋ณผ ์ ์๋ค.
+ **History** is the sequence of observations, actions, rewards


<p align="center"><img src="https://user-images.githubusercontent.com/66208800/173749953-7f5734a7-beed-437c-8fcd-570b0b3b576e.png"></p>

