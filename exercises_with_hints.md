# Data analysis and visualization exercises with hint

This is a collection of exercises that have been collected to offer a quick
reference for both students learning tidyverse or for those who teach.

## Import

#### 1. Save the following data as "test.txt", import it and then calculate `grade` average for two terms (fall, spring). (★☆☆)

(**hint**: please check manual of `read.table` or `read_delim` regarding, use of delimeter, skipping lines and changing comment character. [solution](http://github.com/alperyilmaz/dav-exercises/issues/2))

```
// student grades for spring 2016
// department of X
student_no|department|term|grade|letter_grade
1600001|math|fall|4|A
1600120|chem|fall|3.4|B
1600121|math|fall|3.9|A
1600051|math|spring|2.7|C
1600081|chem|spring|3.3|B
```


## Text Mining 

#### 1. What are most common *positive* (use `bing`) word pairs that appeared in *same sentence* in Jane Austen books dataset? Please remove stop words before counting. (★★★) 

(**hint**: tokenize sentence first, keep sentence number then tokenize words. first line of answer is `happy, love, 44`. [solution](http://github.com/alperyilmaz/dav-exercises/issues/1))
