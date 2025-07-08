自定义制作组

Group.txt https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/Group.txt

自定义替换词

1 CHSCHTRE.txt CHS替换为简体等 https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/CHSCHTRE.txt

2 GroupRE.txt 字幕组名字替换 https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/GroupRE.txt

3 anime.txt 常用替换 https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/anime..txt



自定义渲染词

1 CHSCHTRE.txt CHS替换为简体等 https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/CHSCHTRE.txt

2 GroupRE.txt 字幕组名字替换 https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/GroupRE.txt

3 animeRE.txt 常用替换 https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/animeRE.txt

4 episodegroupRE.txt 需配合剧集组 https://raw.githubusercontent.com/pouker88/Pouker/refs/heads/main/Anime/episodegroupRE.txt

数字就是顺位 #@####

##这两条是自动 给后面SXXEXX EPXX里面的集号 加括号 非必要不用使用 (S\d+E\d+)(.)\b(S\d+E\d+)\b => \1\2[\3] (S\d+E\d+)(.)\b(E.\d+)\b => \1\2[\3]

识别词与渲染词来自 https://github.com/pikaqiu2222/555999
