# 정보처리산업기사-필기

## 1.데이터베이스

#### 001 정보 시스템
  * *정보 시스템*
    * 조직체에 필요한 Data를 수집, 저장해 두었다가 필요시에 처리해서 의사 결정에 유용한 정보를 생성하고 분배하는 수단이다.
    * 사용하는 목적에 따라 경영 정보 시스템, 군사 정보 시스템, 인사 행정 정보 시스템, 의사 결정 지원 시스템 등으로 사용된다.
  * *정보와 자료*  
    * 자료(DATA) : 현실 세계에서 관찰이나 측정을 텅해 수집한 단순한 사실이나 결과값으로 가공되지 않은 상태
    * 정보(Information) : 의사 결정에 도움을 줄 수 있는 유용한 형태로, 자료를 가공(처리)해서 얻는 결과물
    * 자료 처리 시스템 : 정보 시스템이 사용할 자료를 처리하는 정보 시스템의 서브 시스템으로, 처리 형태에 따라 일괄 처리 시스템, 온라인 실시간 처리 시스템, 분산 처리 시스템으로 분류
    * 데이터웨어 하우스(DataWare House) : 조직이나 기업체의 중심이 되는 주요 업무 시스템에서 추출되어 새로이 생성된 데이터베이스로서 의사결정 지원 시스템을 지원하는 주체적, 통합적, 시간적 데이터의 집합체
     
#### 002 데이터베이스의 정의
 * 통합된 데이터(Integrated Data) : 자료의 중복을 배제한 데이터의 모임
 * 저장된 데이터(Stored Data) : 컴퓨터가 실시간으로 접근할 수 있는 저장 매체에 저장된 자료
 * 운영 데이터(Operational Data) : 조직의 고유한 업무를 수행하는 데 있어서 존재 가치가 확실하고 없어서는 안될 반드시 필요한 자료
 * 공용 데이터(Shared Data) : 여러 응용 시스템들이 공동으로 소유하고 유지하는 자료
 
#### 003 데이터 베이스의 특성
 * 실시간 접근성(Real Time Accessibility) : 수시적이고 비정형적인 질의(조회)에 대하여 실시간 처리(Real-Time Processing)에 의한 응답이 가능함
 * 계속적인 변화(Continuous Evolution) : 새로운 데이터의 삽입(Insertion), 삭제(Delete), 갱신(Update)으로 항상 최신의 데이터를 유지함
 * 동시 공유(동시 공용)(Concurrent Sharing) : 여러 사용자가 동시에 자기가 원하는 데이터를 이용할 수 있음
 * 내용에 의한 참조(Content Reference) : 데이터베이스에 있는 데이터를 참조할 때 데이터 주소나 위치에 의해서가 아니라 사용자가 요구하는 데이터 내용으로 데이터를 찾음
 
#### 004 기존의 파일 처리 방식에서의 문제점
 * *종속성으로 인한 문제점*
   * 종속성이란 응용 프로그램과 데이터 파일이 상호 의존적인 관계를 말한다.
   * 데이터 파일이 보조기억장치에 저장되는 방법이나 저장된 데이터의 접근 방법을 변경할 때는 응용 프로그램도 같이 변경해야 한다.
 * *중복성으로 인한 문제점*
   * 일관성 : 중복된 데이터 간에 내용이 일치하지 않는 상황이 발생하여 일관성이 없어짐
   * 보안성 : 중복되어 있는 모든 데이터에 동등의 보안 수준을 유지하기가 어려움
   * 경제성 : 저장 공간의 낭비와 동일한 데이터의 반복 작업으로 인한 비용의 증가
   * 무결성 : 제어의 분산으로 인해 데이터의 정확성을 유지할 수 없음
   
#### 005 DBMS의 정의 및 필수 기능문제점
_DBMS란 사용자와 데이터베이스 사이에서 사용자의 요구에 따라 정보를 생성해 주고, 데이터베이스를 관리해 주는 소프트웨어로 다음과 같은 3가지의 필수 기능이 있다._
 * 정의(조직)(Definition) 기능 : 데이터의 형(Type)과 구조, 데이터가 DB에 저장될 때의 제약 조건 등을 명시하는 기능
 * 조작(Manipulation) 기능 : 데이터 검색, 갱신 삽입 삭제등을 체계적으로 처리하기 위해 데이터 접근 수단 등을 정하는 기능
 * 제어(Control) 기능 
   * 데이터베이스를 접근하는 갱신, 삽입, 삭제 작업이 정확하게 수행되어 데이터의 무결성이 유지되도록 제어해야 한다.
   * 정당한 사용자가 허가된 데이터만 접근할 수 있도록 보안(Security)을 유지하고 권한(Authority)을 검사할 수 있어야 한다.
   * 여러 사용자가 데이터베이스를 동시에 접근하여 데이터를 처리할 때 처리 결과가 항상 정확성을 유지하도록 병행 제어(Concurrency Control)를 할 수 있어야 한다.
  
## 2.전자계산기 구조
## 3.시스템 분석 및 설계
## 4.운영체제
## 5.정보 통신 개론
> 출처 : 2020 시나공 SUMMARY 정보처리 산업기사 필기   
> 출판사 : 길벗
