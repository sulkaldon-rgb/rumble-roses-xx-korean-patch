# rumble-roses-xx-korean-patch
늙고 병든 사람이 만든 XBOX360 럼블로즈 XX 비공식 한글패치에요
Rumble Roses XX (Japan) 한글패치 - ISO 드래그 적용판
패치를 적용할 ISO파일은 Rumble Roses XX (Japan).ISO 7.29GB (7,834,892,288 바이트)에요. 
실기에서 작동은 보장하지 못해요. XENIA에서만 실행을 확인했어요. 

사용법
1. ZIP을 압축 해제해요.
2. Rumble Roses XX (Japan).iso를 APPLY_KOREAN_PATCH.bat 위로 드래그해유.
3. 자동으로 ISO를 추출하고, 원본 PAC 3개의 SHA-256을 확인한 뒤 각각 xdelta를 적용해욧.
5. SHA-256 검증 후 새 XISO를 만들어요.
6. 원본 ISO는 변경하지 않고 같은 폴더에 한글패치가 끝난 *_Korean.iso가 생성되유.
7. 반드시 실행 전 XENIA 언어설정은 일본어(japanese)로 해주세요!! 영어로 설정되어 있으면 한글 안 나와요!!  

내부 패치
- patches\menu.pac.xdelta
- patches\menu_tex_jpn.pac.xdelta
- patches\misc.pac.xdelta

중요
- 이 BAT는 ISO 자체에 단일 xdelta를 적용하는 방식이 아니라, ISO 안의 3개 PAC를 각각 xdelta로 패치한 뒤 XISO를 재구성해요.
- 출력은 Xenia 실행용 재구성 XISO이며 원본 Redump ISO와 동일한 디스크 구조/용량을 보존하지 않습니다.
- 무수정 PAC의 SHA-256이 정확히 일치하지 않으면 안전을 위해 중단해요.
