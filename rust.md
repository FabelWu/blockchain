# install rust
https://www.rust-lang.org/tools/install
## macos
### 确保文件归你所有
sudo chown admin:staff ~/.bash_profile
### 给自己写权限
chmod u+w ~/.bash_profile
### 添加环境变量
export PATH="$HOME/.cargo/bin:$PATH"
### 生效环境变量
source .zshrc
## visual code
### 安装插件
- rust-analyzer
- Error Lens
## 创建helloworld
cargo new helloworld
