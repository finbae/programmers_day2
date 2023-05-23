# programmers_day2
## coding test
#### A 강조하기
    def solution(myString):
    answer = ''
    a = myString.lower()
    return a.replace('a', 'A')
    
#### 배열에서 문자열 대문자, 소문자 구분하기
    def solution(strArr):
    answer = []
    for i in strArr:
        if strArr.index(i) % 2 == 0:
            i = i.lower()
            answer.append(i)
        else:
            i = i.upper()
            answer.append(i)
    return answer
