# 뉴 비트보이(New Bittboy) rev1 커스텀 펌웨어

작업하기 앞서 저희에게 펌웨어를 개발해 주신 **Steward-fu**와 **bittboy** 디스코드 체널 여러분께 무한한 감사를 표합니다.

**대부분의 사진자료는 Steward-fu의 사진자료를 활용하였습니다.**

https://steward-fu.github.io/website/handheld.htm

**다음 영상으로 SPI플레싱 방법을 쉽게 확인할 수 있습니다.**

[![click here](https://i.imgur.com/I3S12VG.png)](https://youtu.be/FjQquL3W99U)

## 1) 준비물
1. New Bittboy - rev1(초기 버전)
2. 8기가 이상의 SD카드
3. 납뗌 용품 (인두기, 은납)
4. 점퍼케이블(얇은 케이블 추천)
5. 데비안 or 우분투 환경의 컴퓨터

## 2)작업 순서
1. 하드웨어 모드(hwmod)
2. SPI플레싱 환경 구축
3. SPI플레싱
3. SD 카드에 이미지 굽기

## 3.1 하드웨어 모드(hwmod)
1. 나사를 풀어 케이스를 때어냅니다.\ 
![step-1](https://i.imgur.com/LHmhgJN.png)
2. 표시 부분을 확인합니다. LCD커넥터가 표시부분에 없다면, Rev2입니다.(간단히 구분방법)\
![step-2](https://i.imgur.com/KuanR5A.png)
3. 저항 R75, R76, R78을 제거합니다.
4. DM, DP 솔더 조인트합니다.(납으로 접지합니다.)\
![image 3](https://i.imgur.com/B2DWSGW.png)
   - -수정전\
![image 4](https://i.imgur.com/lieDKbu.png)
   - -수정후
5. SPI IC칩의 2번에 점퍼선을 접지합니다.\
![image 5](https://i.imgur.com/F0CPt0b.png)
 

## 3.2) SPI플레싱 환경 구축
1. PC에 데비안 or 우분투를 설치합니다.
2. root권한이 있는 계정으로 터미널을 실행합니다.
3. 다음과 같은 순서대로 입력합니다.
   ```
   sudo apt-get install git-core
   ```
4. 설치가 완료되면 다음과 같은 순서대로 입력합니다.
   ```
   git clone https://github.com/steward-fu/f1c100s_sunxi-tools
   cd f1c100s_sunxi-tools
   make clean && make
   ```

## 3.3) SPI플레싱
1. USB로 뉴 비트보이(New Bittboy)와 PC를 연결합니다.
2. 사진과 같이 점퍼선을 접촉시킨 상태에서 전원을 켭니다.
3. Steward-fu의 github에서 최신 spi이미지를 다운로드 합니다. https://github.com/steward-fu/miyoo_rel
   ```
   SPI이미지 파일명 예시 >miyoo_spi_hwmod_1bit_ghostkey_20190216.bin
   ```
4. 다운받은 SPI이미지를 홈으로 이동합니다.
5. 터미널을 실행합니다.
6. 다음과 같이 입력합니다.
   ```
   sudo sunxi-fel -p spiflash-write 0 SPI이미지.bin
   ex>sudo sunxi-fel -p spiflash-write 0 miyoo_spi_hwmod_1bit_ghostkey_20190216.bin
   ```
7. 100% 완료될때까지 기다립니다.
8. 뉴 비트보이(New Bittboy)와 PC를 연결 해제하고 전원을 끕니다.
9. 뉴 비트보이(New Bittboy) 본체를 조립하고 전원을 킵니다.
10. 다음과 같은 화면이 출력되면 성공입니다.\
![image 6](https://i.imgur.com/JxTEsDV.png)

## 3.4) SD 카드에 이미지 굽기
1. Steward-fu의 github에서 최신 MiOS이미지를 다운로드 합니다. https://github.com/steward-fu/miyoo_rel
   ```
   MiOS이미지 파일명 예시 >MiOS_v1.0_20190203.zip, MiOS_v1.0_20190203.z01, MiOS_v1.0_20190203.z02 ...
   ```
2. SD카드의 파티션을 모두 제거하고 FAT32등으로 포맷합니다..(필자는 윈도우 디스크관리를 이용했습니다.)
3. `win32diskimager`를 다운받고 설치합니다. https://sourceforge.net/projects/win32diskimager/
4. `win32diskimager`를 실행하고 SD드라이버를 선택 후 MiOS이미지를 불러온 후 "Write"버튼을 눌러 진행합니다.\
![image 7](https://i.imgur.com/ut0wzto.png)
5. 이미지가 다 구워지면 뉴 비트보이(New Bittboy)에 SD를 삽입하고 전원을 킵니다. 아래와 같이 부팅되면 성공입니다.\
![image 8](https://i.imgur.com/l0ZXpH7.png)

즐깁시다! :grin:
