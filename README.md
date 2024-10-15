# modern-contreol-systems
제어공학 과제1                         2020732066 최민승

### p2.7

![이미지 설명](https://github.com/minseong124123123/modern-contreol-systems/blob/4e71741580cd9d20e29b6a3a9d7c81c9160669e8/P2.7.png)

### p2.12

![이미지 설명](https://github.com/minseong124123123/modern-contreol-systems/blob/b576fd5db6ce8bdda62c8a4a8c088977db1e2721/P2.12.png)

### P2.15

![이미지 설명](https://github.com/minseong124123123/modern-contreol-systems/blob/26fbfeb11112208a0adb2438666e7a5fc950e8b6/P2.15.png)

다음은 MATLAB에서 심볼릭 변수와 역라플라스 변환을 수행하는 코드입니다:

```matlab
% 심볼릭 변수 정의
syms s t m b k 

% 주어진 식 정의 (X(S) 식)
X_S = 1 / (m*s^2 + b*s + k) ;

% 역라플라스 변환 수행
x_t = ilaplace(X_S, s, t);

% 결과 출력
disp('x(t) = ');
disp(x_t);

```

$$
x(t) = \frac{2 \sin\left(\frac{t\sqrt{-b^2 + 4km}}{2m}\right) \exp\left(-\frac{bt}{2m}\right)}{\sqrt{-b^2 + 4km}}
$$


### p2.26

![이미지 설명](https://github.com/minseong124123123/modern-contreol-systems/blob/405f79abac5993ce8b14e41386df7e4c4308d5c9/P2.26.png)

### p2.37

![이미지 설명](https://github.com/minseong124123123/modern-contreol-systems/blob/1d4620c873e240fd89365f4a429e9479e6e81bab/P2.37.png)
