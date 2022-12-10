# opencv
다운받아야 하는 라이브러리
`
pip install opencv-python

pip install imutils opencv-python scikit-image
`

원본이미지(무료 소스)
![original](https://user-images.githubusercontent.com/112916656/206732957-23fa47c7-d990-46ab-adc2-425f3c6bbab5.jpg)


테스트용 이미지(우측 상단에 test 글씨 추가)
![copy](https://user-images.githubusercontent.com/112916656/206733059-10224237-1cb6-495d-80f6-cbf644402979.jpg)


find_red_dots.py 에서 나온 결과
![reddot](https://user-images.githubusercontent.com/112916656/206733194-7fa3bcb2-05ab-4bde-9225-56dad7fa8d05.JPG)


find_section.py 에서 나온 결과
![section](https://user-images.githubusercontent.com/112916656/206733246-4a4a2889-b53d-4738-8c55-fa9faa72841f.JPG)

픽셀 단위로 비교하는 방식이므로 test1-1, test1-2 의 픽셀차이 때문에 해당 그림으로는 비교가 불가능하여 다른 그림으로 대체하였음.

유사도는 커맨드 창에 표시
![similar](https://user-images.githubusercontent.com/112916656/206735611-4d982ecb-604d-48c1-9e98-e6ff1eee5490.JPG)


reference
[reddot](https://soooprmx.com/opencv%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC-%EB%91%90-%EC%9D%B4%EB%AF%B8%EC%A7%80%EC%9D%98-%EB%8B%A4%EB%A5%B8-%EB%B6%80%EB%B6%84-%EC%B0%BE%EA%B8%B0/)
[diff](https://nadocoding.tistory.com/97)
[.](http://egloos.zum.com/mcchae/v/11271797)
[cv2.threshold](https://m.blog.naver.com/samsjang/220504782549)


