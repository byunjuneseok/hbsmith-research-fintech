# 1. 문제 파악 / 목표
## 오픈뱅킹 API 서비스 이용 대상자가 아님.
[오픈뱅킹 공식 홈페이지](https://www.open-platform.or.kr/apt/content/openplatform?location=openPlatform2)를 확인하면 이용 가능 기업의 범위가 아니기때문에 사용할 수 없습니다.
> 정보통신기술 또는 그 밖의 기술을 활용하여 금융회사의 업무 효율성을 증대 시키거나 이용자의 편의성 향상에 기여하는(또는 기여가 예상되는) 금융관련 업무(‘18.11.27, 금융위원회)


## 목표 : 테스트 자동화에 필요한 송금 API 작성
> 외부계좌에서 매 시간마다 1원씩 특정 가상계좌에 입금을 자동화 할수 있는 API나 서비스를 탐색하였으나 찾지 못함


# 2. 탐색
## toss
토스의 경우, 가맹점에 대한 결제 API만을 지원합니다. 예전엔 송금대행 API가 존재했으나 없어진 것으로 파악됩니다. [공식문서](https://tossdev.github.io/) 

## kakaopay
카카오 페이또한 마찬가지로 결제 API만을 지원합니다. [공식문서](https://developers.kakao.com/docs/latest/ko/kakaopay/common)

## 카카오뱅크 & 케이뱅크
오픈뱅킹 API 만 지원.

## 제2금융권
API 제공 제2금융권은 없음

## 쿠콘 
입금이체 API 서비스를 제공합니다. 본 페이지 하기된 클라이언트 리스트를 보면 신뢰도가 어느정도는 확보된 것으로 파악됩니다. [공식 홈페이지](https://www.coocon.net/main_1002_02.act?APP_SRNO=473)

* 비용의 경우 *문의하기*를 통해야 알 수 있습니다. 1주차 보고 이후에 의논 후 진행하겠습니다.

## 농협 API
농협에서 이체 API 를 제공하고 있습니다. [공식 문서](https://developers.nonghyup.com/service/SE_3010)

