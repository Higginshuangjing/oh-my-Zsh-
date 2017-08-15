# oh-my-Zsh-

first the official website ： http://ohmyz.sh/  

在打算安装oh-my-Zsh这个工具的时候，需要使用另外一个工具：wget（安装包管理工具）   


**安装之前的准备**：  
-看了很多网上的安装wget的教程，各种复杂，结果从旁边厉害的运维小哥那里学到了非常简单的一招:  
（苹果自带brew命令）：brew install wget（安装wget)  

-可以通过-which wget- :查看本地是否存在这个命令   
如：jetking-MacBook-Pro:~ huangjing$ which wget   
                        
**安装oh-my-Zsh**：  
1） wget自动安装： wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh  
2） 切换到zsh模式（需要一行命令就可以切换到 zsh 模式） : jetking-MacBook-Pro:~ huangjing$ zsh  
好像可以用了！~ but  不知道有什么用  只是让黑白搭配的命令行页面颜色非常好看 (๑•̀ㅂ•́)و✧ （继续研究下）（我竟然写了GitHub 好可怕:-O）  
3)  其实大概就好了,安装了之后可以使用一些比较方便的命令去操作git等相关的指令，如：  
    alias g='git'  
    alias ga='git add'  
    alias gaa='git add --all'  
    alias gapa='git add --patch'  
    alias gb='git branch'  
    alias gba='git branch -a'  
    alias gbda='git branch --merged | command grep -vE "^(\*|\s*master\s*$)" | command xargs -n 1 git branch -d'  
    alias gbl='git blame -b -w'  
    alias gbnm='git branch --no-merged'  
    alias gbr='git branch --remote'  
    alias gbs='git bisect'  
    alias gbsb='git bisect bad'  
    alias gbsg='git bisect good'  
    alias gbsr='git bisect reset'  
    alias gbss='git bisect start'  
