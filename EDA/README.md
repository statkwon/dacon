# Data Schema

## CUS_INFO
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|CUS_ID|고객번호|숫자|-|
|SEX_DIT_CD|성별|범주|-|
|CUS_AGE|연령대|범주|-|
|ZIP_CTP_CD|주소(시도)|범주|-|
|TCO_CUS_GRD_CD|고객등급|범주|-|
|IVS_ICN_CD|고객투자성향|범주|-|
|GEN_CD|세대|범주|파생|

## ACT_INFO
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|ACT_ID|계좌번호|문자|-|
|CUS_ID|고객번호|문자|-|
|ACT_OPN_YM|계좌개설년월|날짜|-|

## IEM_INFO
|변수명|설명|형태|
|:-:|:-:|:-:|
|IEM_CD|종목코드|문자|
|IEM_ENG_NM|종목영문명|문자|
|IEM_KRL_NM|종목한글명|문자|

## TRD_KR
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|ACT_ID|계좌번호|문자|-|
|ORR_DT|주문날짜|날짜|-|
|ORR_ORD|주문순서|숫자|-|
|ORR_RTN_HUR|주문접수시간대|숫자|-|
|LST_CNS_HUR|최종체결시간대|숫자|-|
|IEM_CD|종목코드|문자|-|
|SBY_DIT_CD|매매구분코드|범주|-|
|CNS_QTY|체결수량|숫자|-|
|ORR_PR|체결가격|숫자|-|
|ORR_MDI_DIT_CD|주문매체구분코드|범주|-|
|ORR_PR_TT|총체결가격|숫자|파생|

## TRD_OSS
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|ACT_ID|계좌번호|문자|-|
|ORR_DT|주문날짜|날짜|-|
|ORR_ORD|주문순서|숫자|-|
|ORR_RTN_HUR|주문접수시간대|숫자|-|
|LST_CNS_HUR|최종체결시간대|숫자|-|
|IEM_CD|종목코드|문자|-|
|SBY_DIT_CD|매매구분코드|범주|-|
|CNS_QTY|체결수량|숫자|-|
|ORR_PR|체결가격|숫자|-|
|ORR_MDI_DIT_CD|주문매체구분코드|범주|-|
|CUR_CD|거래통화코드|문자|-|
|TRD_CUR_XCG_RT|거래통화환율|숫자|-|
|ORR_PR_KRW|한화체결가격|숫자|파생|
|ORR_PR_TT|총체결가격|숫자|파생|

## WICS
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|IEM_CD|종목코드|문자|
|CAT_1|대분류|문자|
|CAT_2|중분류|문자|
|CAT_3|소분류|문자|

## TRD_KR_MERGED
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|IEM_CD|종목코드|문자|-|
|CUS_ID|고객번호|문자|-|
|ACT_ID|계좌번호|문자|-|
|ORR_DT|주문날짜|날짜|-|
|ORR_ORD|주문순서|숫자|-|
|ORR_RTN_HUR|주문접수시간대|숫자|-|
|LST_CNS_HUR|최종체결시간대|숫자|-|
|SBY_DIT_CD|매매구분코드|범주|-|
|CNS_QTY|체결수량|숫자|-|
|ORR_PR|체결가격|숫자|-|
|ORR_MDI_DIT_CD|주문매체구분코드|범주|-|
|ORR_PR_TT|총체결가격|숫자|파생|
|ACT_OPN_YM|계좌개설년월|날짜|-|
|SEX_DIT_CD|성별|범주|-|
|CUS_AGE|연령대|범주|-|
|ZIP_CTP_CD|주소(시도)|범주|-|
|TCO_CUS_GRD_CD|고객등급|범주|-|
|IVS_ICN_CD|고객투자성향|범주|-|
|GEN_CD|세대|범주|파생|
|IEM_ENG_NM|종목영문명|문자|-|
|IEM_KRL_NM|종목한글명|문자|-|
|CAT_1|대분류|문자|-|
|CAT_2|중분류|문자|-|
|CAT_3|소분류|문자|-|

## TRD_OSS_MERGED
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|IEM_CD|종목코드|문자|-|
|CUS_ID|고객번호|문자|-|
|ACT_ID|계좌번호|문자|-|
|ORR_DT|주문날짜|날짜|-|
|ORR_ORD|주문순서|숫자|-|
|ORR_RTN_HUR|주문접수시간대|숫자|-|
|LST_CNS_HUR|최종체결시간대|숫자|-|
|SBY_DIT_CD|매매구분코드|범주|-|
|CNS_QTY|체결수량|숫자|-|
|ORR_PR|체결가격|숫자|-|
|ORR_MDI_DIT_CD|주문매체구분코드|범주|-|
|ORR_PR_KRW|한화체결가격|숫자|파생|
|ORR_PR_TT|총체결가격|숫자|파생|
|ACT_OPN_YM|계좌개설년월|날짜|-|
|SEX_DIT_CD|성별|범주|-|
|CUS_AGE|연령대|범주|-|
|ZIP_CTP_CD|주소(시도)|범주|-|
|TCO_CUS_GRD_CD|고객등급|범주|-|
|IVS_ICN_CD|고객투자성향|범주|-|
|GEN_CD|세대|범주|파생|
|IEM_ENG_NM|종목영문명|문자|-|
|IEM_KRL_NM|종목한글명|문자|-|
|CAT_1|대분류|문자|-|
|CAT_2|중분류|문자|-|
|CAT_3|소분류|문자|-|

## CUS_INFO_MERGED
|변수명|설명|형태|기타|
|:-:|:-:|:-:|:-:|
|CUS_ID|고객번호|숫자|-|
|SEX_DIT_CD|성별|범주|-|
|CUS_AGE|연령대|범주|-|
|ZIP_CTP_CD|주소(시도)|범주|-|
|TCO_CUS_GRD_CD|고객등급|범주|-|
|IVS_ICN_CD|고객투자성향|범주|-|
|GEN_CD|세대|범주|파생|
|ORR_DT_RCT|최근주문날짜|날짜|파생|
|ORR_BRK_PRD|거래휴식기간|숫자|파생|
|ACT_OPN_YM_1ST|최초계좌개설년월|날짜|파생|
|ORR_PR_TT_MED|총체결가격중위값|숫자|파생|
|CNS_QTY_MED|체결수량중위값|숫자|파생|
|ORR_CYL|거래주기|숫자|파생|
