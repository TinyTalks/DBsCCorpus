<div align="center"><img src="https://avatars.githubusercontent.com/u/128916285?s=400&u=8ea76106ce0018439d6d6414b26aea62680712d6&v=4" height="300px"/></div>

<h2 align="center"> 📕DDmkTCCorpus: Diachronic Danmaku Text Comments Corpus</h2>

<h4 align="center">
    <a href="https://github.com/DBsCCorpus">中文</a> |
    <a href="https://github.com/DBsCCorpus">English</a>
</h4>

1️⃣ The project provides open-source comment data for researchers to conduct in-depth research on the bullet-screen corpus, which mainly focuses on the subculture bullet-screen comment corpus (including but not limited to the guichu, animation and e-sports type).  

2️⃣ Corpus is maintained by TinyTalks, a Community for NLP research in Short Text in Chinese. 

## Video corpus
The video corpus were more than 1 milions plays during the years from 2017 to 2020. The attributes can be as follow.
| Attribute | explanation |
| ----- | ----- |
|Bvno | Video ID |
Tname | Main Tag |
Tag_name | Tag List |
Owner_mid| Publisher ID |
Title | Title |
Pubdate | Publication Date |
Duration | Duration |
View | View Count |
Danmaku | Danmaku Count |
Reply | Reply Count |
Favorite | Favorite Count |
Coin | Coin Count |
Share | Share Count |
Like | Like Count |

Source: https://pan.bnuz.edu.cn/l/J5z6nP password:bnuz

<img src="https://github.com/Chen-X666/bullet-screenCorpus/blob/main/%E5%9B%BE3%20%E8%A7%86%E9%A2%91%E5%B1%9E%E6%80%A7%E7%9A%84%E5%85%B3%E8%81%94%E7%B3%BB%E6%95%B0.png" width="300px">

## Video - channel network
https://pan.bnuz.edu.cn/l/g1ydM2 password:bnuz
| Attribute | explanation |
| ----- | ----- |
|videoType | Video Type |
relation | Belongs to |
channel | Channel Tag |

<img src="https://github.com/Chen-X666/bullet-screenCorpus/blob/main/%E5%9B%BE1%20%E7%94%B5%E7%AB%9E%E7%B1%BB%E5%9E%8B%E9%A2%91%E9%81%93%E5%85%B3%E7%B3%BB%E7%BD%91%E5%9B%BE.png" width="260px"><img src="https://github.com/Chen-X666/bullet-screenCorpus/blob/main/%E5%9B%BE10%20%E9%AC%BC%E7%95%9C%E7%B1%BB%E5%9E%8B%E9%A2%91%E9%81%93%E5%85%B3%E7%B3%BB%E7%BD%91%E5%9B%BE.png" width="260px"><img src="https://github.com/Chen-X666/bullet-screenCorpus/blob/main/%E5%9B%BE11%20%E5%8A%A8%E6%BC%AB%E7%B1%BB%E5%9E%8B%E9%A2%91%E9%81%93%E5%85%B3%E7%B3%BB%E7%BD%91%E5%9B%BE.png" width="260px">

## Bullet-screen comment corpus
The attributes detail can as follow.

| Attribute | type | explanation | Default |
| ----- | ----- |  ----- |  ----- |
text  | (str) | 弹幕文本

|dm_time | (float) | Position of the danmaku in the video, in seconds | 0.0
send_time | (float) | Time the danmaku was sent | time.time()
crc32_id | (str) | CRC32 hash digest of the danmaku sender's UID | None
color | (str) | Hexadecimal color of the danmaku | "ffffff"
weight | (int) | Weight of the danmaku in the danmaku list | -1
id_ | (int) | ID of the danmaku | -1
id_str | (str) | String ID of the danmaku | ""
action | (str) | Unclear | ""
mode | (Mode) | Mode of the danmaku | Mode.FLY
font_size | (FontSize) | Font size of the danmaku | FontSize.NORMAL
is_sub | (bool) | Indicates if the danmaku is a subtitle | False
pool | (int) | Unclear | -1
attr | (int) | Unclear | -1
### All corpus
uploading...
### Classification of corpus 

Weird category
https://pan.bnuz.edu.cn/l/pn3Yj5 
(Password: bnuz)

Esports category
https://pan.bnuz.edu.cn/l/I510mH (Password: bnuz)

Anime category
https://pan.bnuz.edu.cn/l/toTTtQ (Password: bnuz)

Epidemic category
https://pan.bnuz.edu.cn/l/aoMMOM (Password: bnuz)

https://pan.bnuz.edu.cn/l/onFbAO (Password: bnuz)

https://pan.bnuz.edu.cn/l/QJGkNF (Password: bnuz)

### Text corpus
In order to be used by scholars who only need textual data, this paper also provides a plain text corpus, which is useful for training various language models.

https://pan.bnuz.edu.cn/l/r1Kkfd (Password: bnuz)


## DanmakuMarked-data
The data is encoded in UTF-8 and saved as comma-separated values (CSV).

The data is divided into numerical information, text information, and labeled categories (unlabeled data has no label information).

Numerical information includes the following fields, separated by commas:

Timestamp of the danmaku appearing in the video
Display mode
Font size
Font color
Send time
Danmaku pool number
Sender user ID
Danmaku ID in the database
Label categories:

0: Happy
1: Sad
2: Angry
3: Surprised
4: Negative sample
https://pan.bnuz.edu.cn/l/snpijm password: bnuz

citation: https://github.com/MelkiorOno/DanmakuMarked-data

## word2vec model training by 4000w bullet-screen comments
uploading...

## Citation

If you use this corpus in your research, please cite this repository.

```bibtex
@article{
 QBTS202209010,
 author = {Chen Xin;Zhang Yixin;Wu Junchao;Guo Lingyu;Yu Zehui & Yang Jing},
 title = {Construction and Analysis of Diachronic Bullet-screen Comment Corpus: Case Study of Youth Subculture Bullet-screen Comment},
 journal = {Information Research},
 volume = {No.299},
 number = {77-85},
 year = {2022},
 issn = {1005-8095},
 doi ={https://www.doi.org/10.3969/j.issn.1005-8095.2022.09.010}
 }
```
