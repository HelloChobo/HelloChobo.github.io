---
layout: single
title: "Tensorflow Errors"
---

## 모델 생성 시 에러
> pip install numpy==1.19.5 로 numpy 다운그레이드


## 모델 로드 시 에러

<pre>
<code>
saved_path = 'C:\\Users\\a\\Documents\\Desktop_Based_AI_Secretary\\'
model = tf.keras.models.load_model(saved_path + 'bidirectional_lstm_(final)_Project_tags')

>> JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</code>
</pre>


> 대신 가중치 로드

