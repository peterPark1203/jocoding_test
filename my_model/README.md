# my_model

Teachable Machine에서 내보낸(export) 모델 파일을 이 폴더에 넣어주세요.

Teachable Machine → 모델 내보내기(Export Model) → Tensorflow.js → **Upload my model** (또는 다운로드) 후,
아래 3개 파일을 이 폴더에 그대로 넣으면 됩니다.

- `model.json`
- `metadata.json`
- `weights.bin`

`animal-test.html`이 `./my_model/model.json`, `./my_model/metadata.json`을 그대로 불러오도록 되어 있습니다.
