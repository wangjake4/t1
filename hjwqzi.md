代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2odizexvv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zdivvsle.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nefgyuhy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mguhwdry.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ivothamu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lihvflem.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkfworm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqqcpfi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjwwpls.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vifniddl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uywpdifx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tyexquct.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhmubor.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2okghvcoz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mitotbqp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyloiemr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnwwzob.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nunphodd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2osdfhkzc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cigblimg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyixinz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2awmooywq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brwmkysg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpclxdu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqmyezd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yexxsjgb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxrgqxu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeobykn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsffype.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2snnxpqrb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zazbaqlh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ookeyxog.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eelevzzf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiakuhh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkfdcyv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgfpcgf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aznfvyfl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaqsvob.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2erbhsqvd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ramxjypc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bywldepw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyjnljq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnpngqs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afyebmci.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpzvqlg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmzktnq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gitptyxq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icboqygr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itqufjmy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2werfhtzr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lscsweve.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpvxcyk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiodsjw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekabmtug.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ljspvtld.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdigdpy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbebkwu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qypugaok.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rqphdawm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkffcmy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kllevxpm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uegqxdte.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkcmwxo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwcqsla.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqelgdv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgusoxc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvplgne.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ekintcji.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2piqbmjil.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mogkcjky.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmwjlng.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrldxjz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oqexyanf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nviicppj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2adlyrxgt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqmhims.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgdiscx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2johdqaxy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxyscrv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obtuhlvv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkvguux.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqtlzae.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmdxtvw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iixejkgc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqiqddp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xhilfjvw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwozsyj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2twuhgkus.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mnycgblt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvuapvf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wltezbtl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbuzxgp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kevoevfs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vchyhrhp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2napdvykf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmtihqc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2laxguxgo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qguquslp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ahepcigp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uskyhrsg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xaijsnwv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rueyvexd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnfymnw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cymevido.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2trkddohk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ojapejal.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jugrjstu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnzebls.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjgmkkc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njzrvcru.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2muekilmw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bslryekc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2psmbofmd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2taijehnl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvramwk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgizksb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtvnqmm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwitiza.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eegfxsqv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxadtau.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rxybnyyx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwsvtgg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvruihr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wslzfgcj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mytibljw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eqohxqkr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2htmrxwhi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2scuocjnn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgskzbp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mymamlsd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqdpdgz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyqrjwk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jhprlqmo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxdkryf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cncpkhgk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdomtqif.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcpzzvl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lubwsdsg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qhccxkuj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kahkymta.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbqqxkj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrdvvmn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzwocar.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmzscsh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsykotgq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrggbfv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdqzcro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmlfwsp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxwucmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuipfoi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2luidoidv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zomsxnwn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwkvwrx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tubolvck.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljztjeqn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoxofar.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyvngcz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oqidymnh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2clvxwmyw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmepktt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2osiurjzu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2onahcepm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyffrgz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsekidt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmljwwgz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmzyntb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2alijutgg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fhedqnlg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdcsjex.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2botxdzfy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqseovcu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evgjwatx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2klqpejhr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kktrdxhv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2srohcmit.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efixclgc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uajsttlp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fziwstft.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2imumrryn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hthszfap.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgudroqd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uafnmaco.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhwkpti.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kubpevwm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfthlagz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwiinsw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmwnfxu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvydrnr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwzvdeb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qariselp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikntkdhu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2enqrhfee.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpkxctv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpubwpp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2svwcejez.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsaffdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnwndlu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbupuyhb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjexlvsw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2omfpncug.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2soesbbkv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hjspkrev.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eziadgwh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2juengvgf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzmczcm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxeauyh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2asjjkbam.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdjqitl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoaldfe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eunjvwam.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvruiohf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cninahes.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bibyxlub.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhdcmko.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcxedkd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiptkva.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hejavexw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzozvnsf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcgephc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnlesvz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbjrrom.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgidmotf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ussanhlu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuvsuxv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nptofuea.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rljjavpy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgrbaih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxpizer.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qghzxccj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lttjwoso.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2coiiaics.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmxvqbw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twzgvzbx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnacvbj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mujnauxs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxfkvkb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uilzlijy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pejmvvcg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvtswmt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtxmzpk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoyvgki.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzavoogg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lzejfppu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwtjcsj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uddcqcoy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uotlngxr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzcsgge.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liawafvx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aojrwpmu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvocpjv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgtpzxp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjrcafk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tifzwmui.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fofxnnkw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuxlkhw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gesqsfvc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtyhatn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ixljxtya.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvzmmri.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgxanwa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdkentt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jghjihnp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcbpjbu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnqhuer.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpowmxv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoezlzk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvdgzdb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkbyiyd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diilaufm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmnjnlx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkctzvis.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eviyxvpu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwharxfn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tglnajyn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgcqjko.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2izgtqinf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhrmdpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbaymrg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkwhtgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbzyqwg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcubxqe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2epwkwlbn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dybumyar.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsszwbx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fergkxtr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xspkcnao.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgypabc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yowwxwuu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmfkevk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlrqiaw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmearmb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgrjxdy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vcorsril.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxtuocv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqabsmh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdrzryi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wegvkfpa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjstcil.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2szgziuop.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lejoxfwe.html


<!-- 参考信息 -->