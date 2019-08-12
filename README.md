## Comics Dataset for Visual Sentiment Recognition

The Comics datset contains more than $10,000$ images belongs to $8$ categories. In specific, we use *Amusement, Awe, Contentment, Excitement* as positive sentiment, and *Anger, Disgust, Fear, Sadness* as negative sentiment. The images are collected from about seventy comics of various countries (e.g., America, Japan, China and France). About seventy comics are selected as candidates, e.g., Sponge Bob, Spiderman, The Avengers, One Piece, Slam Dunk, etc.  Finally, a total of $10,281$ comic images are selected and roughly divided into Comic subset and Manga subset.



###  File Structure

The IP102 dataset can be downloaded from [Baidu](https://pan.baidu.com/s/1I5NKaa7B8lmB9bqsz4tGZA) (pw: meg3) or [Google](https://drive.google.com/open?id=1dnw8Z4XIADWBdLX0ecokRwqVmRKJa-QP). The folders are arranged like this:

```
Comics
├── annotation
│   ├── test.txt
│   ├── train.txt
│   ├── trainval.txt
│   └── val.txt
├── images.zip
└── readme.md
```



### Class Examples

![屏幕快照 2019-08-12 20.42.58](/Users/shedongyu/Desktop/屏幕快照 2019-08-12 20.42.58.png)



### Dataset Statistics

| Class     | Amusement | Awe  | Contentment | Excitement | Anger | Disgust | Fear | Sad  | Total |
| --------- | --------- | ---- | ----------- | ---------- | ----- | ------- | ---- | ---- | :---: |
| Comic set | 274       | 102  | 829         | 454        | 456   | 360     | 865  | 264  | 3604  |
| Manga set | 1220      | 327  | 1302        | 422        | 1128  | 388     | 1151 | 739  | 6677  |
| All       | 1494      | 429  | 2131        | 876        | 1584  | 748     | 2116 | 1003 | 10281 |

*The final version is slightly different from the paper.*




### Additional Information
If you find the Comics helpful, please cite it as
```
@article{She19sentiment,
  title={Learning Discriminative Sentiment Representation from Strongly- and Weakly-Supervised CNNs},
  author={Dongyu She, Ming Sun, Jufeng Yang},
  journal={ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)},
  year={2019},
  publisher={ACM}
}
```

ATTN: This dataset is free for academic usage. For other purposes, please contact Dongyu She (sherry6656@163.com).
# Comics
