## 강화 학습(Reinforcement Learning) 예제들

예제 명명법 : 환경_알고리즘

- Windy01_DP : 결정론적(Deterministic) 바람부는 격자세계(Windy Grid-World)을 동적계획법(Dynamic Programming)으로 풀기, Policy Iteration
- Windy02_DP : 확률적(Stochastic) 바람부는 격자세계를 동적계획법으로 풀기, Value Iteration
- Mnist_CNN  : MNIST(필기체 숫자 자료)를 간단한 Convolutional Neural Network로 분류(classification)하기
- Cartpole_Keyboard : 카트 위에 세워진 막대(Cartpole)을 20도 이상 쓰러트리지 않기. 키보드로. ("1"-카트 오른쪽으로 밀기)
- Cartpole_DQN : 카트폴 쓰러트리지 않기 학습. Deep Q-Network로.
- Cartpole_REINFORCE : 카트폴 쓰러트리지 않기 학습. REINFORCE로. 
- Cartpole_ActorCritic : 카트폴 쓰러트리지 않기 학습. Actor-Critic 방법으로.

* Cartpole_Keyboard는 https://github.com/openai/gym/blob/master/examples/agents/keyboard_agent.py 의 내용을 조금 변경하였으며, Cartpole_DQN, Cartpole_REINFORCE, Cartpole_ActorCriti은 https://github.com/rlcode/reinforcement-learning/tree/master/2-cartpole 의 내용을 조금 변경하였습니다.

* 모든 .py 파일은 "jupyter nbconvert -to script *.ipynb"을 통해 생성되었습니다.

* 숨은원리 출판사 : blog.naver.com/kwonpub
              www.facebook.com/kwonpub
		   	  kwonpub.com