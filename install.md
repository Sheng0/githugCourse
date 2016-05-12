#安装githug
------------
其实游戏的安装很简单，所以作者如是说：

>首先我们需要来安装这个游戏，`githug` 是用 `Ruby` 编写的，可通过如下命令安装：  
>`gem install githug`
>
>如果遇到权限问题，请加上 `sudo` ：  
>`sudo gem install githug`

但是这里其实有个小坑：  
没有用过的 `Ruby` 的同学来说以上的命令很可能是不会成功的。  
因为我们缺少必要的命令 `gem` 。

所以真正的安装步骤如下（CentOS 7）：  

- 首先安装 `Ruby`   
	`yum install ruby`  
- 安装 `githug` 本体  
	`gem install githug`  
- 当然，你不能没有 `git`  
	`yum install git`  



--------------------------------------------
**tips:**  
&ensp;&ensp;&ensp;&ensp;可能会遇到没有任何动作卡住或者速度慢的感人   
	原因是国外服务器的访问受限（你懂的）导致  
	解决方案是更换 `gem` 包管理的源  
	`gem sources --add https://ruby.taobao.org/`  
	`gem sources --remove https://rubygems.org/`  

