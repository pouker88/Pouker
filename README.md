自定义制作组

Group.txt 

自定义替换词

1 CHSCHTRE.txt CHS替换为简体等 

2 GroupRE.txt 字幕组名字替换 

3 anime.txt 常用替换



自定义渲染词

1 CHSCHTRE.txt CHS替换为简体等 

2 GroupRE.txt 字幕组名字替换 

3 animeifre.txt 常用替换 

4 episodegroupRE.txt 需配合剧集组 

数字就是顺位 #@####

##这两条是自动 给后面SXXEXX EPXX里面的集号 加括号 非必要不用使用 (S\d+E\d+)(.)\b(S\d+E\d+)\b => \1\2[\3] (S\d+E\d+)(.)\b(E.\d+)\b => \1\2[\3]
