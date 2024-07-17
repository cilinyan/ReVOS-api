# ReVOS

## Download

⬇️ Get the dataset from: 

 - ☁️ [**OneDrive**](https://mailsjlueducn-my.sharepoint.com/:f:/g/personal/yancl9918_mails_jlu_edu_cn/Ek3rFeIbNZtAv8kxVxr5n6sBoJZWbVZXHFxWYYxIq7kFKQ?e=Hx2JVd) **(Recommended)**
 - ☁️ [Baidu Pan](https://pan.baidu.com/s/1StuFnJdLnc5wl3MjndSQ_g?pwd=visa)

 Please also check the SHA256 sum of the files to ensure the data intergrity:
 ```
# shasum -a 256 ReVOS/*
1844db76c3075deb95034935a8208ba459272784242ec39de9287c66a4c22f07  ReVOS/JPEGImages.zip
e9b4310661495ddd47dedcac1e289621cf8f5dff89c0bb8b65f7699f748d5cff  ReVOS/mask_dict.json
05d9be5d7bbed03b216a457274022ad1c9e683b4ffdc32b19c60c5e797fd8f01  ReVOS/mask_dict_foreground.json
3917dfba8725d080c8658dc43ad4a84cf41ce51438acfaee70bef5aa0310417a  ReVOS/meta_expressions_train_.json
e171028757d8ec75bea33a661c38c288ecdafdb6c7bc64bb9e14edb97e2e5ade  ReVOS/meta_expressions_train_sub_.json
127b975e78effef6033846e68989dcf79c692d644dd07c835b723cea700d4c2d  ReVOS/meta_expressions_valid_.json
 ```

## File Structure
```
ReVOS
├── JPEGImages  # JPEGImages contains all images of the train set and valid set
│   ├── <video1  >
│   ├── <video2  >
│   └── <video...>
├── mask_dict.json                # mask dict (train set & valid set)
├── mask_dict_foreground.json     # foreground mask dict (train set & valid set)
├── meta_expressions_train_.json  # meta expressions (train set)
└── meta_expressions_valid_.json  # meta expressions (valid set)
```

## Acknowledgement
ReVOS largely borrows videos from [MOSE]( https://github.com/henghuiding/MOSE-api), [MeViS]( https://github.com/henghuiding/MeViS), LV-VIS(https://github.com/haochenheheda/LVVIS), [OVIS](https://songbai.site/ovis), [TAO](https://arxiv.org/pdf/2005.10356) and [UVO](https://arxiv.org/pdf/2104.04691). 
The copyright for these videos is held by the organizers of MOSE, MeViS, LV-VIS, TAO and UVO.

## BibTeX
Please consider to cite VISA if it helps your research.

```latex
@article{yan2024visa,
      title={VISA: Reasoning Video Object Segmentation via Large Language Models}, 
      author={Yan, Cilin and Wang, Haochen and Yan, Shilin and Jiang, Xiaolong and Hu, Yao and Kang, Guoliang and Xie, Weidi and Gavves, Efstratios},
      journal={arXiv preprint arXiv:2407.11325},
      year={2024}
}
```

## License
ReVOS is licensed under a [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) License. The data of ReVOS is released for non-commercial research purpose only.
