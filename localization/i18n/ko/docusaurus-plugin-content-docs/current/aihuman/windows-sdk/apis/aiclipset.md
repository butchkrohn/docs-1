---
sidebar_position: 4
---

# AIHuman.Common.Model.AIClipSet

| Modifier and Type | Method and Description                                       |
| ----------------- | ------------------------------------------------------------ |
| `enum`            | `ClipType` 클립셋 타입의 종류는 아래와 같습니다.<br />- CLIP_SPEECH: 제스처가 없는 일반 발화만 가능한 Clip <br />- CLIP_GESTURE: 제스처만 가능한 Clip<br />- CLIP_SPEECH_GESTURE: 제스처가 포함된 발화가 가능한 Clip |
| `ClipType`           | `Type { get; }` 클립셋에 설정된 클립셋 타입을 가져옵니다.           |
| `string`             | `SpeechText { get; }` 클립셋에 설정된 발화 문장을 가져옵니다.        |
| `string`             | `GestureName { get; }` 클립셋에 설정된 제스처 이름을 가져옵니다.               |
| `string`             | `ClipId { get; }` 클립셋에 설정된 아이디를 가져옵니다.             |
| `CustomVoice`             | `CustomVoice { get; }` 클립셋에 설정된 음성을 가져옵니다. return 값이 null일 경우는 기본 음성임을 의미합니다. |
