# C1_0921
 C프로그래밍1 0921 수업 내용 공부

#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

//int main(void)
//{
//	// 변수 num과 int의 크기를 계산하여 그 결과로 sz1과 sz2를 초기화
//	int num = 10;
//	int sz1 = sizeof(num);
//	int sz2 = sizeof(int);
//}
//int main(void)
//{
//	// 연산자 sizeof를 이용한 바이트 크기의 확인
//	char ch = 9;
//	int inum = 1052;
//	double dnum = 3.1415;
//	printf("변수 ch의 크기: %d \n", sizeof(ch));
//	printf("변수 inum의 크기: %d \n", sizeof(inum));
//	printf("변수 dnum의 크기: %d \n", sizeof(dnum));
//
//	printf("char의 크기: %d \n", sizeof(char));
//	printf("int의 크기: %d \n", sizeof(int));
//	printf("long의 크기: %d \n", sizeof(long));
//	printf("long long의 크기: %d \n", sizeof(long long));
//	printf("float의 크기: %d \n", sizeof(float));
//	printf("double의 크기: %d \n", sizeof(double));
//
//	return 0;
//}
//int main(void)
//{
//	// 정수의 표현 및 처리를 위한 일반적 자료형 선택
//	char num1 = 1, num2 = 2, result1 = 0;
//	short num3 = 300, num4 = 400, result2 = 0;
//
//	printf("size of num1 & num2: %d, %d \n", sizeof(num1), sizeof(num2));
//	printf("size of num3 & num4: %d, %d \n", sizeof(num3), sizeof(num4));
//	printf("size of char add; %d \n", sizeof(num1 + num2));
//	printf("size of short zdd; %d \n", sizeof(num3 + num4));
//
//	result1 = num1 + num2;
//	result2 = num3 + num4;
//	printf("size of result1 & result2: %d, %d \n", sizeof(result1), sizeof(result2));
//
//	return 0;
//}
//int main(void)
//{
//	// 실수의 표현 및 처리를 위한 일반적 자료형 선택
//	double rad;
//	double area;
//	printf("원의 반지름 입력: ");
//	scanf("%lf", &rad);
//	area = rad * rad * 3.1415;
//	printf("원의 넓이: %f \n", area);
//
//	return 0;
//}
//int main(void)
//{
//	// 문자의 표현 - 서식문자 %c: 해당 숫자의 아스키 코드 문자를 출력해라
//	char ch1 = 'A', ch2 = 65;
//	int ch3 = 'Z', ch4 = 90;
//
//	printf("%c %d \n", ch1, ch1);
//	printf("%c %d \n", ch2, ch2);
//	printf("%c %d \n", ch3, ch3);
//	printf("%c %d \n", ch4, ch4);
//
//	return 0;
//}
//int main(void)
//{
//	// 리터럴 상수의 자료형
//	printf("literal int size: %d \n", sizeof(7));
//	printf("literal double size: %d \n", sizeof(7.14));
//	printf("literal char size: %d \n", sizeof('A'));
//
//	return 0;
//}
//int main(void)
//{
//	// 접미사를 이용한 다양한 상수의 표현
//	float num1 = 5.789f; // 경고 메시지 발생 -> f 붙이면 발생X
//	float num2 = 3.24F + 5.12F; // 경고 메시지 발생 -> f 붙이면 발생X, 소문자f 대신 대문자F 써도 됨
//	return 0;
//}
//int main(void)
//{
//	// 이름을 지니는 심볼릭(Symbolic) 상수: const 상수
//	const int MAX = 100;	// MAX는 상수. 따라서 값의 변경 불가
//	const double PI = 3.1415;	// PI는 상수. 따라서 값의 변경 불가.
//}