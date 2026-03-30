# sdk-plugins

Kakao AdFit SDK 연동을 위한 Claude Code 플러그인 마켓플레이스입니다.

## 연결된 플러그인

| 플러그인 | 설명 |
|---|---|
| [adfit-plugin-ios](https://github.com/adfit/adfit-plugin-ios) | AdFit iOS SDK 연동을 위한 Claude Code 플러그인 |

## 1. 마켓플레이스 등록

이 마켓플레이스를 Claude Code에 등록합니다.

```bash
claude mcp add-marketplace adfit/sdk-plugins
```

## 2. 플러그인 설치

마켓플레이스에 등록된 플러그인을 설치합니다.

예시) adfit-plugin-ios 설치:

```bash
claude plugin install adfit/adfit-plugin-ios
```

## 3. 설치 확인

설치된 플러그인 목록을 확인합니다.

```bash
claude plugin list
```
