# GAN

### Generative Adversarial Network(생산적  적대 신경망)

> Generation은 생성 모델이라는 뜻이다. '그럴듯한 가짜'를 만들어내는 모델이다. 언뜻 보면 진짜 같은 가짜 사람 얼굴 사진을 만들어내거나 실제로 있을 법한 고양이 사진을 만들어내는 것이 생성 모델의 예다.
>
> Adversarial은 두개의 모델을 적대적으로 경쟁시키며 발전시킨다는 것을 뜻한다. 경쟁을 통해 생성자(Generator)는 구분자(discriminator)를 속이기 위해 진짜와 구분 할 수 없는 가짜를 만들어 내게 된다.  이것이 GAN의 핵심적인 아이디어인 적대적 학습(Adversarial Training)이다.
>
> Network는 인공신경망 또는 딥러닝으로 만들어졌기 때문에 붙었다.

요약하자면 GAN은 생성이라는 문제를 풀기 위해 딥러닝으로 만들어진 모델을 적대적 학습이라는 독특한 방식으로 학습시키는 알고리즘이다. 이처럼 ‘Generative Adversarial Network’라는 이름 속에는 모델의 목적부터 학습 방법까지 GAN의 전반적인 개념이 모두 들어있다.