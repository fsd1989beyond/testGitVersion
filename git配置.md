### Git基本配置
- 系统配置（对所有用户适用）
  `存放在Git安装目录下，%Git%/etc/gitconfig`  
  `使用git config --system 选项`
- 用户配置
  `存放在用户目录下，~/gitconfig`  
  `使用git config --global 选项`  
- 仓库配置  
   `当前仓库的配置文件。（。git/config）`  
    `使用git config --local 选项`
    
- 个人身份配置

- 文本换行符配置  
  window 用户提交时自动把行结束符CRLF转换成LF. 而在导出代码时把LF转换成CRLF。  
  git config --global  core.autocrlf true
  
- 文本编码配置  
  git config --global  gui.encoding utf-8
  git config --global  i18n.commitencoding utf-8
  git config --global  i18n.logoutputencoding.encoding utf-8
  git --amend  修改最近一次的提交记录。 （常用于修改message）

