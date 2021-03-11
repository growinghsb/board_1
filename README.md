# 리팩토링 할 것
* 테스트 코드 작성 (Service의 비즈니스 코드)   
* 네이밍 통일 할 것 (User는 없다, Content로 통일)   
* Controller에는 Entity를 노출하지 말 것 (Service에서 DTO 생성해서 전달)    
* Entity에서 setter 제거, protected 기본 생성자 생성, 방어적으로 프로그래밍 할 것    
