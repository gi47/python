# 4.0 Methods
## List
- ["1","2,..."]
## Method: vs function
- function : ()
- method: .blah()


# 4.1 Lists

```
.clear() # mutate한
.reverse()
.remove()
```

# 4.2 Tuples
```py
# tuples are immutable : tuple은 불변한다, 수정 불가
days = ("Mon","Tue", "Fri")

days[0]
days[-1] # 맨 뒤 
```
- 변경 가능하게 만들자 >> 리스트
- 변경할 수 없는 데이터로 만들자 >> 튜플

# 4.3 Dicts
- key-value
- 많은 속성을 가진 데이터를 저장할 때
- mutable =  수정가능
- 접근법: palyer['key']
```py
player = {
'name' : 'nico',
'age': 12,
'alive': True
}
player.clear()
player.get(key) # key에 맞는 value 값
player['fav_food'].append("hotdog")

```
