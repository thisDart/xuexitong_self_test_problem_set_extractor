# 用途：
提取学习通题库

# 使用步骤：
1. 电脑、手机处于同一 WiFi 下，电脑打开 Fiddler 或任意抓包软件，手机设置代理；
2. 手机打开学习通，开始自测，直接提交，查看试卷，此时注意电脑上 Fiddler 捕获到的 HTTP 请求，复制其 URL、Cookie 备用；
3. 运行 test.py 文件，按照提示依次输入 URL、Cookie，完成后 test.py 文件所在目录下会生成 3 个 .txt 文件，自行查看使用即可。
