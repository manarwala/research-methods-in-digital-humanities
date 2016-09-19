---
layout: post
title:  "Text Analytics 101 notes"
date:   2016-09-19
categories: blog
---

## Notes from class

We walked through the first couple steps in analyzing text, [according to John Laudun](http://johnlaudun.org/20130221-text-analytics-101/), in class today. Here are the commands Carlos and I used in iTerm:

```
git clone https://github.com/libbyh/upst
cd upst
subl settings_example.cfg
conda create --name upst python=2.7 anaconda nltk Cython Pillow numpy scikit-learn
source activate upst

python stats.py
python words.py > ash-words.txt
python concordance.py -w think
```

## More Resources
The research assistants in my lab have written intros to some of the tools you saw me use in class today:

- [Package managers](http://www.casmlab.org/code/package-management/)
- [Jupyter notebooks](http://www.casmlab.org/code/running-casm-lab-code/)

Lucky for you, they are also in the class. So, you can ask them next time you see them.

If you're interested in learning more Python, I recommend [Codecademy](https://www.codecademy.com/learn/python). Or, you could ask the guys taking CS 331. They are learning it right now.