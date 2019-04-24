# 4K-Face: A Dataset with Huge Scale-varying Faces

The images from 4K-Face dataset is collected from the Internet. Following WIDER FACE event categories, keywords, such as travel, surgeons, and celebration, are used to retrieve more than 25,000 images from web search engine. In order to obtain large scale variance, we only keep the images with 4K resolution (3840×2160). Images without face are filtered. Finally, 5,102 images with more than 30,000 annotated boxes are acquired in total.

The 4K-Face dataset is contributed by Megvii Research in the following paper.

```
SFace: An Efficient Network for Face Detection in Large Scale Variations,
Jianfeng Wang, Ye Yuan, Gang Yu, and Jian Sun
arXiv preprint arXiv:1804.06559 (2018).
```

The full paper is available at: <https://arxiv.org/abs/1804.06559>.

## Urls

[OneDrive](https://megvii-my.sharepoint.cn/:f:/g/personal/wangjianfeng_megvii_com/EuqMTgmVHllGpWI2agiizNcBRsbUk1Wvjxf3KOEp7wsYJg?e=ekCy09)

[BaiduDrive](https://pan.baidu.com/s/12rtKJEqqJcTJlOTDyQuY6A)

## Files

```
images.tar.00
images.tar.01
images.tar.02
images.tar.03
images.tar.04
images.tar.05
images.tar.06
images.tar.07
images.tar.08
images.tar.09
images.tar.10
images.tar.11
images.tar.12
images.tar.13
images.tar.14
images.tar.15
images.tar.16
README.md
result.json
```

## How to Use it

```bash
cat images.tar.* > images.tar
tar -xvf images.tar
```

## Label Format

```json
{
    "items": [
        {
            "filename": "selfie---231f78c09dab611423d2811b3cb60238.jpg",
            "gtboxes": [
                {
                    "box": [
                        973.0000001279999,
                        621.918945216,
                        554.5947264000002,
                        722.4323731199999
                    ],
                    "extra": {
                        "ignore": 0
                    },
                    "tag": "Face"
                },
                {
                    "box": [
                        1793.945800704,
                        724.0810546800001,
                        550.946289024,
                        762.56762688
                    ],
                    "extra": {
                        "ignore": 0
                    },
                    "tag": "Face"
                },
                {
                    "box": [
                        2614.892089728,
                        443.13525381600004,
                        901.215820416,
                        1076.3513184959997
                    ],
                    "extra": {
                        "ignore": 0
                    },
                    "tag": "Face"
                }
            ],
            "height": 2160,
            "width": 3840
        }
    ]
}
```

## Citations

Please consider citing this project in your publications if it helps your research. The following is a BibTeX reference.

```
@article{wang2018sface,
  title={SFace: An Efficient Network for Face Detection in Large Scale Variations},
  author={Wang, Jianfeng and Yuan, Ye and Yu, Gang and Sun, Jian},
  journal={arXiv preprint arXiv:1804.06559},
  year={2018}
}
```
