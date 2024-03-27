# autobrew
auto install application by homebrew in macos 
Mac 电脑一键部署常用软件

大多数从外网下载的软件会有网络问题。不想折腾的就多试几次。
或者你懂的


安装 homebrew

"/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)""

安装 zsh （不必要，增加兼容性）
"brew install zsh"

安装ohmyzsh （不必要，好看）
"sh -c "$(curl -fsSL https://gitee.com/allenjia09/ohmyzsh/raw/master/tools/install.sh)""

更新 rosetta （不更新有的会报错）
"sudo softwareupdate --install-rosetta"

执行安装命令 brew install xxx 可以放多个，中间空格隔开。

"brew install wechat qq qqmusic neteasemusic geph wpsoffice iina  eul  obs steam bilibili  baidunetdisk todesk tencent-meeting dingtalk maczip"

对照下表，把不需要的软件从上面删掉。
安装过程中会有输入密码。不是完全自动。

wechat 			        	//微信
qq 				            //企鹅
qqmusic 		        	//企鹅音乐
neteasemusic         	//网易云音乐
geph 				          //急救
wpsoffice 		        //金山办公
iina 				          //视频播放器
eul 			          	//监控面板
obs 			          	//录屏
bilibili  		      	//哔哩哔哩
baidunetdisk 		    	//百度云盘
todesk 				        //远程桌面
tencent-meeting			  //腾讯会议
dingtalk			        //钉钉
maczip				        //解压打包

-----------------------------------------------
下面的单独安装，有的要权限，有的要梯子，有的没用。
the-unarchiver			  //解压打包
visual-studio-code    //vscode
android-studio	      //安卓模拟器
blender 		          //全能冠军
openemu 			        //街机模拟器（不带 mame，带 mame 的需要手动安装）
blender 		    	    //全能冠军
parallels-client 		  //rdp 远程控制
wetype			          //微信输入法（只下载，完毕后在终端里运行 open /opt/homebrew/Caskroom/wetype/1.0.3,269/WeTypeInstaller_1.0.3_269.app）
steam 				        //玩游戏
parallels 			      //虚拟机（正版）
google-chrome 		  	//浏览器

有想加入列表的软件，先从下面的网址查询有没有。

https://formulae.brew.sh
