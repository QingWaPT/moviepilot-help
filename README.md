# QingWaPT MoviePilot Help

## 使用说明

```markdown
├─ backup
│ ├── app.env                  # 【设定】的内容，根据变量名寻找对应位置使用
│ ├── category.yaml            # 【二级分类策略】的内容，可在【插件】-【二级分类策略】中替换使用
│ ├── rules.txt                # 【规则组】书写内容，仅供需要个性化配置时参考
│ ├── rules.json               # 【设定】-【规则】-【自定义规则】的配置，选择导入后粘入使用
│ └── rules-group.json         # 【设定】-【规则】-【优先级规则组】的配置，选择导入后粘入使用
└── words
  ├── common.txt               # 【词表】-【自定义识别词】的内容，通过下方链接引入【插件】-【共享识别词】中使用
  ├── movie-FROG.txt           # 【词表】-【自定义识别词】的内容，通过下方链接引入【插件】-【共享识别词】中使用
  ├── movie.txt                # 【词表】-【自定义识别词】的内容，通过下方链接引入【插件】-【共享识别词】中使用
  ├── anime-FROG.txt           # 【词表】-【自定义识别词】的内容，通过下方链接引入【插件】-【共享识别词】中使用
  ├── anime.txt                # 【词表】-【自定义识别词】的内容，通过下方链接引入【插件】-【共享识别词】中使用
  ├── series-FROG.txt          # 【词表】-【自定义识别词】的内容，通过下方链接引入【插件】-【共享识别词】中使用
  ├── series.txt               # 【词表】-【自定义识别词】的内容，通过下方链接引入【插件】-【共享识别词】中使用
  └── other.txt                # 【词表】-【自定义制作组/字幕组】&【自定义占位符】&【文件整理屏蔽词组】的内容，粘入使用
```

### 自定义识别词链接

```txt
https://raw.githubusercontent.com/QingWaPT/moviepilot-help/main/words/common.txt
https://raw.githubusercontent.com/QingWaPT/moviepilot-help/main/words/movie-FROG.txt
https://raw.githubusercontent.com/QingWaPT/moviepilot-help/main/words/movie.txt
https://raw.githubusercontent.com/QingWaPT/moviepilot-help/main/words/anime-FROG.txt
https://raw.githubusercontent.com/QingWaPT/moviepilot-help/main/words/anime.txt
https://raw.githubusercontent.com/QingWaPT/moviepilot-help/main/words/series-FROG.txt
https://raw.githubusercontent.com/QingWaPT/moviepilot-help/main/words/series.txt
```

### 自定义识别词规则参考

```txt
https://raw.githubusercontent.com/Putarku/MoviePilot-Help/main/Words/TV.txt
https://raw.githubusercontent.com/Putarku/MoviePilot-Help/main/Words/anime.txt

https://movie-pilot.org/etherpad/p/MoviePilot_TV_Words
https://movie-pilot.org/etherpad/p/MoviePilot_Anime_Words
```