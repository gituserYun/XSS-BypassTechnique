# XSS Bypass Technique
웹 애플리케이션을 사용해서 다른 최종 사용자의 클라이언트에서 임의의 스크립트가 실행되는 취약점
<br/><br/>

## 소개
'XSS-BypassTechnique' 리포지토리는 다양한 XSS(교차 사이트 스크립팅) 우회 기술을 상세히 설명하고, 관련 페이로드를 제공합니다.  
또한 이것 이외에도 연계될 수 있는 다양한 페이로드 또한 제공할 것입니다.
<br/><br/>

## 기술 목록
- **Stored XSS**: 악성 스크립트를 웹 어플리케이션 서버에 저장되어,해당 페이지를 방문하는 Victim이 악의적 영향을 받는 방식
- **Reflected XSS**: Victim이 Attacker가 조작한 링크를 클릭 및 URL 접근 시, 악성 스크립트가 포함된 응답이 반영되는 방식
- **DOM-based XSS**: 원래 서버 응답은 변경하지 않고, 클라이언트 측에서 DOM(Document Object Model)을 조작하여 악성 스크립트를 실행하는 방식(URL의 해시 '#' 뒤에 이:ㅆ는 데이터를 이용하는 경우가 대표적)
<br/><br/>

## 페이로드 Referer to ... 
- [주요정보통신기반시설_기술적_취약점_분석_평가_방법_상세가이드.pdf](https://www.kisa.or.kr/2060204/form?postSeq=12&lang_type=KO&page=1#fndoDocumentPreview)
- [PortSwigger_Cross-site scripting (XSS) cheat sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet)
<br/><br/>

## 진단 시, 유용한 참고 사이트
- [인코딩/디코딩 사이트](https://dencode.com/)
- [RequestBin 사이트](https://pipedream.com/)
  
