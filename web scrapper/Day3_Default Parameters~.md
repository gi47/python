# 2.9 Default Parameters
- def 함수명(argument="인자를 주지 않았을 떄 임의 값"):
```py
def say_hello(user_name="stranger"):
  print("welcome",user_name)

say_hello("baji")
say_hello()
```

![image](https://user-images.githubusercontent.com/99578725/187718673-665be389-2573-4349-9ab6-ccacd328b2f0.png)

# 2.10 Return Values 
## 문자열 안에 변수 넣기 - f"{변수}"
```py
def self_intro(name,age,sex):
  print(f"My name is {name},I'm {age},anf I'm a {sex}")

self_intro("Fuyu",18,"man")
```
![image](https://user-images.githubusercontent.com/99578725/187721157-4b1260f0-7e64-4ce7-a298-8bfe9691bd08.png)



