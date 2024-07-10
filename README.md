# ReVOS

## Download

⬇️ Get the dataset from: 

 - ☁️ [**OneDrive**](https://mailsjlueducn-my.sharepoint.com/:f:/g/personal/yancl9918_mails_jlu_edu_cn/Ek3rFeIbNZtAv8kxVxr5n6sBoJZWbVZXHFxWYYxIq7kFKQ?e=Hx2JVd) **(Recommended)**
 - ☁️ [Baidu Pan](https://pan.baidu.com/s/18cj1BdJFhG9JVvEC9G4M9Q?pwd=visa)

 Please also check the SHA256 sum of the files to ensure the data intergrity:
 ```
# shasum -a 256 ReVOS/*
1844db76c3075deb95034935a8208ba459272784242ec39de9287c66a4c22f07  ReVOS/JPEGImages.zip
e9b4310661495ddd47dedcac1e289621cf8f5dff89c0bb8b65f7699f748d5cff  ReVOS/mask_dict.json
05d9be5d7bbed03b216a457274022ad1c9e683b4ffdc32b19c60c5e797fd8f01  ReVOS/mask_dict_foreground.json
3fbc3d82c36f109ce6d01d8750ad0a4f803ab7357a8f7a2d94d6a312a8baaf36  ReVOS/meta_expressions_train_.json
81f6fc809c3a024fc0356bf5f2d77374b763e19802a44b90213e4641b37fbbb9  ReVOS/meta_expressions_train_sub_.json
291d1854eb860ebac5dd3870451bfc9a2bf002765efabf39bf5496bcb8e1f4b6  ReVOS/meta_expressions_valid_.json
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

## BibTeX
Please consider to cite VISA if it helps your research.

```latex
...
```

## License
ReVOS is licensed under a [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) License. The data of ReVOS is released for non-commercial research purpose only.
