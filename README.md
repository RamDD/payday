## 170913

*Class* - 메서드, 프로퍼티 집합체? (코드의 묶음)

- 사용하려면 인스턴스가 필요하다

 >ex)인스턴스.b 여기서 점은 b의 패키지를 열기 위한 점 
   
- 클래스는 작은 응용프로그램 같은 것이다?

 >코딩 시 하나의 파일로 작성 된다.
    
- 자주 반복되는 함수를 class 로 하나로 묶어 실행되는 응용프로그램 방식으로 만든다. 

- 인스턴스는 인스턴스 던전으로 생각하면 된다.

- 캐스팅에 대해 알아보기 , return <--리턴에 대해새 다시 하번 읽기

- 메서드 (method)는 특정 타입에 관련된 함수를 지칭한다. 

- 프로퍼티는 클래스, 구조체, 열거형 등에 관련된 값을 말한다. ex) var array:String = **_[aa,bb,cc]_**
-  super. self. 는 자기 자신을 가르킨다. ; 자기 자신의 위치를 명확하게 해주고 싶을때 사용한다.

- 상속 받을때 쓰는 것이 오버라이드 ex) override func ~() {

- 코드 정렬시 오류가 없다면 control + i 커맨드를 입력하면 자동정렬된다.


```swift 
class levelclass{

func cal(student:student)
{
   var totalscore:Int = 0
   var subject = student.subjects
   for subject in subjects
   { totalscore += subject.score
```
```
ex) 
var a=10
var b=10 
var c= a+b
 a= a+1
 b= 5 

func add(x,y) -> Int
{  
 x = x+1
 return x + y
 }
 
 class subjeck
 {
 
 ....
 }
 
 
 var a=10
 var b=10
 var c:subject = subject
```
 

## *클래스 관련 실습 꼭 해보기*
