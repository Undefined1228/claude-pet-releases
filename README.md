# Claude Pet 릴리스

[Claude Pet](https://github.com/Undefined1228/claude-pet)의 빌드된 앱을 배포하는 저장소입니다. 소스 코드는 이 저장소에 없습니다.

## 설치

```bash
brew install --cask undefined1228/tap/claude-pet
```

또는 [Releases](https://github.com/Undefined1228/claude-pet-releases/releases)에서 `ClaudePet-x.y.z.zip`을 받아 압축을 풀고 `ClaudePet.app`을 `/Applications`로 옮깁니다.

- macOS 14 이상, Apple Silicon(arm64)
- Developer ID로 서명하고 Apple 공증을 받은 앱입니다.
- 설치 후 메뉴바 아이콘 → `설정…` → `프롬프트 복사`로 Claude Code에 연결합니다.

## 업데이트

앱 메뉴의 `업데이트 확인…`은 각 릴리스에 올린 `appcast.xml`을 읽습니다(Sparkle).
