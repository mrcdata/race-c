# RACE-C
This repository maintains RACE-C, a multi-choice reading comprehension dataset, collected from college English examinations in China. It can be regarded as a supplement of RACE, released by [Lai et al. (2017)](http://www.cs.cmu.edu/~glai1/data/race/), which contains RACE-M and RACE-H for middle and high school English examinations respectively.

- paper: http://proceedings.mlr.press/v101/liang19a.html

```
@InProceedings{pmlr-v101-liang19a,
  title={A New Multi-choice Reading Comprehension Dataset for Curriculum Learning},
  author={Liang, Yichan and Li, Jianheng and Yin, Jian},
  booktitle={Proceedings of The Eleventh Asian Conference on Machine Learning},
  pages={742--757},
  year={2019}
```

Please contact [Yichan Liang](mailto:liangych8@mail2.sysu.edu.cn) and [Jianheng Li](mailto:lijheng3@mail2.sysu.edu.cn) for questions about the dataset.

We construct the same format of RACE-C as [Lai et al. (2017)](http://www.cs.cmu.edu/~glai1/data/race/), 	specifically：
```
{
  "article": "This is an article",
  "questions": ["Question1?", "Question2's answer is _ ."],
  "options": [["Q1_opt1", "Q1_opt2", "Q1_opt3", "Q1_opt4"],["Q2_opt1", "Q2_opt2", "Q2_opt3", "Q2_opt4"]],
  "answers": ["D", "A"],
  "id": "1.txt"
}
```

*This dataset is intended for non-commercial research purpose only.
