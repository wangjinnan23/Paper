1.sudo apt-get install git
2.git config --global user.name "Your Name Here"
3.git config --global user.email "your_email@example.com"
4.
git config --global credential.helper cache
git config --global credential.helper 'cache --timeout=3600'

…or create a new repository on the command line
5.Push（上传文件到仓库中）
mkdir ~/Demo
cd Demo
git init(初始化一个空的Git repository )
touch README
echo "# Demo ..." >> README
git add README
git commit -m "first commit" <第一次创建需要>
git remote add origin https://github.com/wangjinnan23/Demo.git <第一次创建需要>
git push origin master
等待输入帐号和密码

6.clone到本地
git clone https://github.com/username/Hello-World.git
