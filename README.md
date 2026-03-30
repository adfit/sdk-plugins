# sdk-plugins

Kakao AdFit SDK 연동을 위한 Claude Code 플러그인 마켓플레이스입니다.

## 연결된 플러그인

| 플러그인 | 설명 |
|---|---|
| [adfit-plugin-ios](https://github.com/adfit/adfit-plugin-ios) | AdFit iOS SDK 연동을 위한 Claude Code 플러그인 |

## 1. 마켓플레이스 등록

Claude Code 내에서 다음 슬래시 커맨드를 실행하여 마켓플레이스를 등록합니다.

```
/plugin marketplace add adfit/sdk-plugins
```

## 2. 플러그인 설치

마켓플레이스에 등록된 플러그인을 설치합니다. 형식은 `plugin-name@marketplace-name`입니다.

예시) adfit-plugin-ios 설치:

```
/plugin install adfit-plugin-ios@sdk-plugins
```

## 3. 설치 확인

`/plugin`을 실행한 후 **Installed** 탭에서 설치된 플러그인을 확인합니다.

```
/plugin
```
