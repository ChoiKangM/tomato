# Tomato
> find ripen tomato

Hello, Robotics

## 사진 찍을때

```bash
$	while true; do takephoto; sleep 1;done   

$	raspistill -o $(time).jpg  

$	export time="$(date +"%F_%T")"  
```



#### 참고 문서
* [딥러닝 CIFAR-10 CNN 예제에 내 사진을 넣어서 학습 시켜 보자](https://github.com/hohoins/ml/tree/master/ImageBinaryGenerator)
* [cifar-10 사용 방법](https://github.com/tensorflow/models/tree/master/tutorials/image/cifar10_estimator)