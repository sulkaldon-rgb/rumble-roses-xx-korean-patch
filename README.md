# rumble-roses-xx-korean-patch
늙고 병든 사람이 만든 XBOX360 럼블로즈 XX 비공식 한글패치에요
Rumble Roses XX (Japan) 한글패치 - ISO 드래그 적용판

사용법
1. ZIP을 압축 해제해요.
2. Rumble Roses XX (Japan).iso를 APPLY_KOREAN_PATCH.bat 위로 드래그해유.
3. 처음 실행할 때 인터넷이 연결되어 있으면 xdelta3와 extract-xiso를 공식 GitHub 릴리스에서 자동으로 준비해요.
4. 자동으로 ISO를 추출하고, 원본 PAC 3개의 SHA-256을 확인한 뒤 각각 xdelta를 적용해욧.
5. SHA-256 검증 후 새 XISO를 만들어요.
6. 원본 ISO는 변경하지 않고 같은 폴더에 *_Korean.iso가 생성되유.

내부 패치
- patches\menu.pac.xdelta
- patches\menu_tex_jpn.pac.xdelta
- patches\misc.pac.xdelta

중요
- 이 BAT는 ISO 자체에 단일 xdelta를 적용하는 방식이 아니라, ISO 안의 3개 PAC를 각각 xdelta로 패치한 뒤 XISO를 재구성해요.
- 출력은 Xenia 실행용 재구성 XISO이며 원본 Redump ISO와 동일한 디스크 구조/용량을 보존하지 않습니다.
- 무수정 PAC의 SHA-256이 정확히 일치하지 않으면 안전을 위해 중단해요.
