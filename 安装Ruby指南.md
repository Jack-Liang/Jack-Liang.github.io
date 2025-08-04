# 安装Ruby指南

为了在本地运行这个Jekyll项目，您需要先安装Ruby环境。以下是Windows系统的安装步骤：

## 步骤1：下载RubyInstaller
- 官方下载地址：[RubyInstaller官网](http://rubyinstaller.org/downloads/)
- 国内镜像：[RubyInstaller.cn](https://rubyinstaller.cn/)

建议下载与项目Gemfile中指定版本兼容的Ruby（Gemfile中指定了Jekyll 4.0，推荐使用Ruby 2.7或3.0版本）。

## 步骤2：安装Ruby
1. 双击下载的安装文件
2. 在安装向导中，勾选**Add Ruby executables to your PATH**选项
3. 按照提示完成安装

## 步骤3：验证安装
安装完成后，打开命令提示符（CMD）或PowerShell，运行以下命令验证安装：
```
ruby -v
gem -v
```
如果能看到版本信息，说明安装成功。

## 步骤4：安装Bundler
```
gem install bundler
```

完成以上步骤后，我们可以继续安装项目依赖并运行项目。