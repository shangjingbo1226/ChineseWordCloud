# ChineseWordCloud

## Example Results

If we use some transcripts of movies (i.e., example.txt), we can get the following word clouds.

![alt text](https://github.com/shangjingbo1226/ChineseWordCloud/blob/master/color_love_example.png)
![alt text](https://github.com/shangjingbo1226/ChineseWordCloud/blob/master/love_example.png)

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
  |-fonts
    |-STFangSong.ttf
```

## Usage

Install the required packages through *pip*
```
pip install -r requirements.txt
```

The input file can be specified in the command line as follows.
```
python create_word_cloud.py example.txt
```

The default output will be
```
love_example.png
color_love_example.png
```

## Advanced Usages

#### More Backgraound Templates

Please put your new pictures under *./data/templates/*. Both png and jpeg files are accepted.

#### Different Fonts

Please modify the *font_filename* in the python script.

## Notes
This is a part of 2017 birthday gifts to my wife :).
