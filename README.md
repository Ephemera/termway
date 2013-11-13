# Termway
역명을 력하면 해당역의 가장 가까운 지하철 출발시각을 알려준다.

![usage](http://i.imgur.com/qHNDAAO.png)

### Usage
    ./termway 역명

### Requirement
[jq](/stedolan/jq/)

### Configuration
`~/.termwayrc` 파일에 [서울 열린 데이터 광장](http://data.seoul.go.kr)에서 발급받은 apikey를 아래와 같은 형식으로 넣어줘야 함. 

    key=123467890
    
근데... 그냥 'sample'이란 문자열을 넣어도 되는 듯 하다. 어떤 제약이 있는진 모르겠지만...
