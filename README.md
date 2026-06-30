[![Using MoveIt with a piper robot arm in Isaac Sim](https://img.youtube.com/vi/dGvGAYixpRw/maxresdefault.jpg)](https://youtu.be/dGvGAYixpRw)
<br>

<h1> 초기설정 </h1>

### git Repository 설치
```
git clone https://github.com/stupid1potato/Using-MoveIt-with-a-piper-robot-arm-in-Isaac-Sim.git
```

```
colcon build
```

빌드 진행 후

<br><br>

<h1> Isaac Sim </h1>

src/piper_moveit_config/piper_simpleRoom.usd를 Isaac sim에서 불러온 뒤 실행

```
ros2 launch piper_moveit_config demo.launch.py
```
명령어를 통해 piper moveit 실행


<br><br>


### Action graph에서 오류가 발생할 시 해결방법

<img width="719" height="217" alt="image" src="https://github.com/user-attachments/assets/92f78f8b-11cb-4bdb-8c7c-4ccbd5150e4e" /><br>
여기에 보이는 topicName을 자신의 환경에 맞는 이름으로 수정하면 됩니다.
