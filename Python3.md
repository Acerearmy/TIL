# 함수(function)
- 함수는 정리정돈 도구같은 것.  

![alt text](image-26.png)
- 작동방식은 몰라도 입력이 있으면 출력이 있다 정도는 알 수 있다.
- 우리가 직접 만들 수도 있다.
- 함수를 만드는 명령어는 def
```python
def abc():
    print('a')
    print('b')
    print('b')
abc()
```
a,b,c를 출력하는 함수를 만들수있다.
print('a')  
print('b')  
print('b')  
를 abc()한줄로 표현할 수 있게된다.  
```python
def get_vat(Price,vat_rate):
    print(price*vat_rate)
```
- 함수에 입력값을 인자(argument)라고 칭하고 그 인자를 받아 함수 안에서 사용하는 변수를 매개변수(parameter)라고 한다.
- 내부에 매개변수를 만들어 더 간단하게 사용가능하다.
- 해당값을 다른 함수나 파일 등으로 넘겨주고 싶다면  
print~부분을 return으로 바꿔주면 해당 값을 다른 함수나 프로그램에서도 사용가능하다.  
#email.send('mumy@gmail.com',get_vat(20000,0.3))을 사용하면 이메일로 결과값을 보내는 것도 가능
---
함수의 사용자체도 자바와 비슷. 파이썬만의 문법에 주의할 것.