# OpenAI API 활용

## Parameters of `create chat completion`

full guide: [here](https://platform.openai.com/docs/api-reference/chat/create)

### 필수 파라미터

- `model` : 사용할 GPT 모델 
- `messages` : 대화 메시지 목록 

<br><br>

### 응답 다양성 제어를 위한 파라미터

- `temperature` : 0~2 사이 값. 다음 토큰 예측의 다양성 조정. 

- `top_p` : 0~1 사이 값. 선택할 토큰의 확률 범위 제한.

<br>

cf. `temperature`과 `top_p`를 함께 활용하면

