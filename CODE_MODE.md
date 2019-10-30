# 코딩 양식 통일 방안

## 1. 헤더 파일 생성

헤더 파일을 따로 생성하여 다음 양식 적용

#include<iostream>
#include<string>
#include<exception>
#include<limits>

//...이외 추가 헤더 파일

using namespace std;

## 2. 중괄호 위치

중괄호는 코드 아랫줄에 작성

ex)

int main()
{
	...내용
}

## 3. 변수, 함수등 선언시 헝가리안 표기법, 카멜 표기법 적용

ex) int m_iNum;//int형 변수이므로 맨 앞글자 i를 붙이고 카멜 표기법에 따라 단어 앞글자를 대문자로 적용

m_는 멤버 변수라는 뜻

## 4. 단어 사이 띄우기 또는 분리할 필요가 있을시 _ 사용

ex) string strHello_world;

## 5. 한 줄 짜리 함수는 개행 없이 한 줄로 작성

ex) void getNum() { return m_iNum; }
