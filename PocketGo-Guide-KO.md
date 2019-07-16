# Pocket Go v1 Custom Firmware

이 작업을하기 전에 **Steward-fu**와 메인 페이지 특별 감사에 언급 된 사람들에게 감사를 표합니다 [바로 여기에](https://github.com/TriForceX/NewBittboyCFW#special-thanks).

**아직 베타 버전이며 아직 개발 중입니다.**

## 1) 준비물
1. Pocket Go v1
2. 8기가 이상의 SD카드
3. 최신 CFW v3.9 이미지 [(다운로드)](https://www.dropbox.com/s/m2j56qx2utt9d6z/PocketGo_V1_CFW_v3.9_10-06-2019.img.7z?dl=0)
4. Partition Wizard [(다운로드)](https://www.partitionwizard.com/download.html)
5. Win32diskimager [(다운로드)](https://sourceforge.net/projects/win32diskimager)
6. 7zip [(다운로드)](https://www.7-zip.org/download.html)
7. 선택적 설치 SD Card Formatter [(다운로드)](https://www.sdcard.org/downloads/formatter)

## 2) 설치
![pocketgo-guide](https://user-images.githubusercontent.com/16083854/59299539-e0ebb600-8c5a-11e9-91bb-f9386ec71d1c.png)

1. 포함 된 SD를 사용하는 경우 _Partition Wizard_, _SD Card Formatter_ 또는 _Windows Disk Management_를 사용하여 모든 파티션을 제거해야합니다.
   ** 참고 : ** SD 카드는 in_FAT 32_ 형식이어야합니다.
2. CFW 파일이 ** .7zip ** 압축 된 경우 진행하기 전에 _7zip_을 사용하여 압축을 풀면됩니다.
3. _win32diskimager_를 실행하고, SD 카드를 선택하고, **. IMG ** 파일을로드 한 다음 ** 쓰기 ** 버튼을 눌러 계속 진행하십시오.
4. 이미지가 SD 카드에 구워지면 파티션 마법사를 열고 디스크 관리를 선택하십시오.
5. _main_ 파티션을 마우스 오른쪽 단추로 클릭하고 extend (최대로 설정)를 선택하고 적용하십시오.
6. SD를 새 Bittboy에 넣고 켭니다. 부팅하면 성공합니다.

**노트:** Windows 7 또는 8의 "기본"파티션에 액세스하는 데 문제가있는 경우 [여기를 클릭하십시오](https://user-images.githubusercontent.com/16083854/61264146-7d710e80-a759-11e9-99e4-de446c032818.jpg)

**Enjoy!** :grin:
