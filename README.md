# Universal-Style-Transfer
论文复现（Universal Style Transfer via Feature Transforms） 在同学石华榜的指导下完成相应作业
                                                              安装手册

#后端：
后端使用Python和Flask。只需写一个路由处理前后端通信即可。 进入到 server 目录，服务端代码和PyTorch风格转换代码都在里面，启动服务端的脚本文件是: app_stylize.py

#依赖
确保本机安装了Python3.7, 以下这些依赖是必须的: torch, pillow, flask, gevent。可以直接通过 requirements.txt 来安装这些依赖:
pip install -r requirements.txt

#运行：
python app_stylize.py
运行成功的程序会在 5002 端口监听请求。浏览器进入这个URL：http://localhost:5002 就能看到 /index 首页路由的简单返回。

#前端
需要安装好，配置好 npm 的系统环境:
Node.js

# 克隆本项目到本地
git clone git@github.com:S-HuaBomb/pytorch-in-flask.git
cd pytorch-in-flask

# 安装前端依赖
npm install

# 运行前端
npm run dev
在浏览器打开这个URL：http://localhost:8080，就能看到前端界面，并且能跟后端完美通信。

如果只想在后端上看效果，可以直接把想要的图片导入
