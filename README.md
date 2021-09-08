This is my toolbox for Natural Language processing tools adjusted to work on dialects and dead languages. I will keep adding and sharing scripts as I write them.

<b>Main scripts</b>

1_character_list.py - This script give you an overview of what characters you have in your text. You should open it, and delete all the characters you want to keep, and leave the unwanted ones

2_preprocess.py - By using the list generated by 1_character_list, it will remove the unwanted characters from your target text.

extractor.py - The purpose of this script is to extract certain grammatical endings and sound patterns in the word list generated by <i>sort.py</i> The search can be focused on the start, middle and end of the words. You can also import language scripts, for example <i>Danish_Norwegian_Swedish.py</i> which gives you the option to search for entire phonetic categories at once, such at dentals, labials, nasals and so on. You can also use regular expreeions to do more creative searches. Other prepared scripts: <i>Albanina.py</i>, <i>Faroese.py</i>, <i>Old_Icelandic.py</i>, <i>Icelandic.py</i>, <i>Latin.py</i>, <i>Old_Church_Slavonic</i> and <i>Proto_Germanic.py</i> Read more about regular expressions here: https://www.w3schools.com/python/python_regex.asp

mirror.py - This takes the word list generated by <i>sort.py</i> and mirrors every word, so you can focus on the endings.

sort.py - This script takes each word, remove all duplicates, and lists every word in alphabetic order in a separated text file.

whereis.py - This script let you type in a word, it does not matter if you use big or small letters, it will find both "Cat" and "cat" if that occurs in the preprocessed text. It will tell you at what line number you can find your word in the text file.

word2vec.py - It takes the preprocessed text, and gives you the vector represenation of chosen words. Vectors shows how similar or different the use of different words are. Hear more here: https://www.youtube.com/watch?v=gQddtTdmG_8&t=66s


<b>Other Scripts</b>

path_finder.py - This is a script I wrote to import into other scripts. It simply helps the other python scripts to find out where it is on the computer and where other scripts and text files are located.

Import other scripts, will generate a directory called <i>__pycache__</i> which you can just ignore.
