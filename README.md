# finetuning instruct pix2pix : text to character colorization
텍스트를 기반으로 이미지 변환을 위해 제안된 [instruct pix2pix](https://github.com/timothybrooks/instruct-pix2pix/tree/main) 을 finetuning하여 텍스트를 기반으로 이미지 내 캐릭터의 채색 자동화 시스템을 구축해보았습니다. 또한 학습이 완료된 모델을 Flask 프레임워크를 활용하여 api로 구축한 후 직접 사용자가 캐릭터를 선택한 후 텍스트를 입력하여 채색된 이미지가 출력되는 사이트를 개발하였습니다.

|              | 흑백 이미지 | 컬러 이미지 | caption    |
|--------------|-------------|-------------|-----------|
| 이미지 개수  | 826         | 826         | 307       |
| 크기         | 28.6MB      | 37.6MB      | 15.1KB    |
