# ChineseWordCloud

## Ideas
It creates the word cloud for Chinese text corpus. The layout and color of the word cloud is fit to the background templates (accept .png and .jpg files).

First, the input text is tokenized into different words. Second, stopwods will be filtered before we count the frequency. In the end, word clouds based on different background templates are generated. The output files are generated and named based on the templage names.

## File structure
```
|-ChineseWordCloud
  |-create_word_cloud.py
  |-data
    |-stopwords.txt
    |-templates
      |-love.png
      |-color_love.png
```

## Usage
The input file can be specified in the command line. 

```
python create_word_cloud.py example.txt
```
The default output will be
```
love_example.png
color_love_example.png
```

## Notes
This is a part of 2017 birthday gifts to my wife :).
