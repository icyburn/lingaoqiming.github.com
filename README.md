小说《临高启明》的网站
======================

#说明：

本站托管于github page上，由jekyll实现，实现了小说《临高启明》的共享式编辑，即每个注册于Github的用户均可对各章节的内容进行修改，并可追踪各修改的具体内容及修改人。各修改只有经同意后才能在被接受(术语称为：版本控制)。

#用法：

首先在github上注册用户。

点击[网站](http://lingaoqiming.github.io/)进入各具体章节。在每一章节页面下点击“页面编辑”，即可进入github页面编辑，点右上方的小笔，开始编辑。所有文件均为[markdown格式](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown)，编辑时：
-*1、文件前几行（即"---"之间的几行）用于网站控制，请勿修改*
-2、各行的第一个字不能是+,-,空格,*等，总之是中文字就行了
-3、修改中可以点左上方的"Preview changes"查看本次修改的内容
修改结束后，点击下方的propose file change提交修改，修改提交后不会马上显示。首先要网站（代码仓库）拥有者确认修改，确认修改后git page的jekyll引擎还要重新生成网页，这个过程要30分钟（git hub说只要10分钟，每都要20分钟以下）左右。
文件的修改可以点上方的"history"查看。
