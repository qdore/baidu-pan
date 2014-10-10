=========================
You need to install the Python Requests library. In Debian / Ubuntu / Raspbian, you just run the following command:

    sudo pip install requests


USAGE:

```
<script> push [flag] [file/directory] - 上传文件并标记为[flag]
<script> pull [flag] - 下载标记为[flag]的文件
<script> rm [flag] - 删除所有标记为[flag]的文件
<script> ls <flag> - 显示所有flag/显示flag下的内容
```
EXAMPLES:
```
<script> push thesis thesis.doc mythesis[directory]
<script> pull thesis
<script> ls thesis
<script> ls thesis/mythesis
<script> rm thesis
```

文件默认保存在/app/bypy中
