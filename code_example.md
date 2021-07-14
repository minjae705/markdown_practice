WA  
  
2. 다음 프로그램의 출력결과를 쓰시오.  
```c
#include <stdio.h> 
int main() 
{ 
    char sTemp[16] = "Hello Sujebi"; 
    printf("%s", &sTemp[6]); 
    return 0; 
}
```
답) Sujebi  
  
print("%c", sTemp[6]); --> S  
print("%s", &sTemp[6]); sTemp[6]='S'이후의 문자열 --> Sujebi  
  
[출처] [2021년 제1회 기사 실기 출제예상 문제] (6과목) 프로그램밍 언어 활용 - 2 (수제비- IT 커뮤니티 (정보처리기사,빅데이터분석기사 등)) | 작성자 보안쌤  
