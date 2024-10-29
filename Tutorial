Download Docker Desktop from https://www-docker-com.translate.goog/?_x_tr_sl=en&_x_tr_tl=sv&_x_tr_hl=sv&_x_tr_pto=sc

Install WSL2 in Windows， follow this instruction ：https://learn.microsoft.com/en-us/windows/wsl/install
Dont forget check the Prerequisites before installing of WSL

当WSL安装完成后安装 Ubuntu 22.04 LTS Linux 发行版 (注意！目前Docker Desktop 并不支持Ubuntu 24。04 LTS），并将Ubuntu 22.04 LTS 设置成默认版本 （通过此代码：wsl --set-default Ubuntu-22.04)

确认Docker Desktop启动，可通过右下角任务栏中查看是否有一个鲸鱼的图标。

当Docker Desktop启动后，在Linux终端中输入 Docker info可以查看Docker的服务状态。

以下是接下来会用到Docker指令
在下面所有代码中 [] 内的都是可选选项,这里只会写每个指令的一部分选项。
在Linux中 CTRL + C 可以终止当前在终端中运行的进程。

拉取镜像：Docker pull <imageName>[:<version>] , Docker pull 会从Docker Hub 或其他指定仓库中拉取Docker image，标签是个可选选项，默认是拉取latest version，例如 docker run redis:7.4.1 则会指定拉取redis 7.4.1版。
创建容器：Docker run [--name] [-d] [-e] [--net] [-p] <imageName/imageID> --name 用于给容器指定一个名字。-d 选项会让容器在后台运行。 -e 设置环境变量。-p 将host的端口绑定到容器的端口上
启动容器：Docker start <ContainID/Name>
停止容器：Docker stop [-f] <ContainID/Name>, -f可以强制终止一个或多个Docker容器
删除容器：Docker rm [-f] <ContainID/Name>, -f可以强制终止一个或多个Docker容器
删除镜像： Docker rmi <imageName/imageID>
查看当前Docker主机上所有的网络：Docker network ls
查看当前运行的容器: Docker ps [-a], -a可以查看当前停止的容器
查看当前存在的镜像：Docker images
查看容器的日志：Docker logs <ContainID/Name>
命令一个运行中的容器内执行命令：Docker exec [-it] <ContainID/Name>, -it 进行交互式，与/bin/bash一起使用可启动交互式终端，例如 docker exec -it <容器ID或名称> /bin/bash （当没有bash时：docker exec -it <容器ID或名称> /bin/sh）







