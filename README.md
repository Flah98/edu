# edu
1.반복문 무한루트 만드는 세가지 방법은 ?
while(ture){}
do{}while(ture);
for(;;){}

2.아래와 같이 출력되도록 프로그래밍 하시오.
-126500의 금액을 한국 화폐로 바꾸었을 때 각각 몇개의 화폐가 필요한지 계산해서 출력하기
오만원 2장 만원 2장 오천원 1장 천원 1장 오백원 1개 백원 0개
int won = 126500;
	        int oman = won/50000;
	        int manwon = (won-oman*50000)/10000;
	        int ochunwon = (won-((oman*50000)+(manwon*10000)))/5000;
	        int chunwon = (won-((oman*50000)+(manwon*10000)+(ochunwon*5000)))/1000;  
	        int obaek =(won-((oman*50000)+(manwon*10000)+(ochunwon*5000)+(chunwon*1000)))/500;
	        int baek=(won-((oman*50000)+(manwon*10000)+(ochunwon*5000)+(chunwon*1000)+(obaek*500)))/100;
	       
	        System.out.println("오만원"+oman);
	        System.out.println("만원"+manwon);
	        System.out.println("오천원"+ochunwon);
	        System.out.println("천원"+chunwon);
	        System.out.println("오백원"+obaek);
	        System.out.println("백원"+baek);
          
3. 구구단을 출력하시오.
