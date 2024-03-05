# VSCode에 설정방법

## settings.json에 아래 두 항목을 추가

```json
{
  ...
  "java.format.settings.url": "https://raw.githubusercontent.com/MinByeongDon/ablecoms-java-format/main/AblecomsJavaStyle.xml",
  "java.format.settings.profile": "ablecoms",
}
```

# Eclipse에 설정방법

# preference > java > code style > formatter

- import로 다운로드 받은 xml파일을 import하고 profile에서 'ablecoms'선택
