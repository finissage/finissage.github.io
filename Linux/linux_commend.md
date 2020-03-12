# Linux 命令

## > 和 >> 的区别
> `>`输出重定向 如果文件不存在就创建文件，如果文件存在就覆盖文件
> `>>`追加文件，如果文件不存在就创建文件，如果文件存在就追加到文件末尾

## | 和 || 区别
> `|` 表示管道： 上一条命令的输出，作为下一条命令的参数
> `||` 短路或符号：表示上一条命令执行失败，才执行下一条命令

## & 和 && 区别
> `&` 表示任务在后台运行，比如 redis-server &
> `&&` 短路与符号：表示上一条命令执行成功，才执行下一条命令 