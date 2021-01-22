# go Mod 相关
使用VS code过程中出现同一package下，引用报错的问题，逻辑上没有问题，但IDE会报错。
&emsp;&emsp;项目第一次使用时 用go mod init 项目名字，生成go.mod文件，使用go mod tidy 会检测项目文件夹下所有依赖项，并写入go.mod文件中。使用 go mod vendor 执行此命令,会将所有依赖转移至该项目根目录下的 vendor(自动新建) 文件夹下。