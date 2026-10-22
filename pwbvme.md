代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hheiuptd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsldfcm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgyimgd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzhiwof.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2anmtzsar.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjtggxf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuvmnds.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lytpekcu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnzusbl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcgzvrn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrtnehg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2avoxoqjn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wgusujrv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvdpvqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uojhroti.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jueotfvb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpsqatp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2chycnfpe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcuounk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsipowz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vdetohnz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zizbrbpl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfobrlgv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2weptbqqv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhurgfpk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gqboxopy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bxexjrhp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iclapais.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnsizna.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vevwtfpa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtesvpld.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdhyvzm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuyzkvs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uncslugj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdgtbjd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skulzoyf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgvmznl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxcoukd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvitacl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oygbqryf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfkhyfz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2shyfcaol.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcuecwb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rydpasot.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxzvxei.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvojwmt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qafvitpj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dssnjeut.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkjygio.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrvnraq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxbzqtr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsmzfrk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2esajbwvv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xinjebbg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzxicfk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuxfntj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ansowgvg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpavqfh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2unsthjuw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cahtwjvf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmircxwn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjqvbks.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwykaqn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2okmuavmu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2swakuxes.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2obgyvljd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2grvenivw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wccrlyva.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2loxymqqr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmpytyx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aawseczc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuqisgb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smgydeqg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qucerkni.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlugbgp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfksizi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2llfxyjuk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwecmpa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2icblibho.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ncabjfzv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mndggswd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oagunqhv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2celwyvvn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdsylxk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fbabltid.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2opowrsqm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dfytprde.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zetdapyg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kttlcqom.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uxikekik.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjvmbhf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoxbdnn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjocqnz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfusekn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2trlfkccw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2udthtebv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2andevjxa.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fljuzkuu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umnjjway.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwmrnwc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2klhzentc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pedcsyji.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uptrgvov.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtogrzr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aglkeybh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktutidkq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgjxwon.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rltvajet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kxghsbjv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzumniwk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrqiogb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2plqzluja.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwczwnt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyllstqk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nonvljvq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqsczxb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fojdpabn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cavnsjhn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqxkeex.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlmloil.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnjlwlh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thscgdyv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyknkzj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2thhgutor.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtlaafw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxxsqqz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvizzah.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgbwsmu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnumxxi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlokdte.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhjrqrs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuqdqqe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oqggygrp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmwyqio.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsgkuwa.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sramfgtq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hsteibvi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gprsvvtx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmuywqa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2effkhfvj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqodbrkk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yalijxre.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsnukoh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjwvixt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfukljm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2urzvixyy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmwyasf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdplyxyg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlpvapt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xifpfrcd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdtpomx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeysmhv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiufxrt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qokaopqa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swnjuaki.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcopmzs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwnueub.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2inylstvd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2udfvepof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmctndwa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2elhomofi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyndbivc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kimxlags.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfzcpfj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrwrgxg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrngwyz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2monwgdlz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2peujfoos.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqibahwz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jatrronj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnxktof.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2grgonnnf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfylpng.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khwbityf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyfmzky.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuyfgfa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvfrtia.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jijowwpq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqglbhv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vghpmtxu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoulwno.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jyizauyt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgvaodi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xedtafil.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nunkkbzm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuxbfup.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2unybnmst.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxtwazt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2actfswbl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2izbrpdyf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmiiyxi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qprurkhp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2taafoyoq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jysggttn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2byuvrkax.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2weisehoz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuplvzk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bckkftch.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2srhzioei.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpxwyaw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oodzjrrx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfpyfta.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrnqcav.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhztgsk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzmqkcv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dlciwhcg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziizmlss.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoybvcm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kadfgmfx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkjdujz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2spxbmprt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxmmmcg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsdplfb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bamntuxt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrzmjtz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2poauazuz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jylptvbz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uivimjjq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqgptwi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mupdmmba.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvzrkpw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbpmdca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2khinezzu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnfddpv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jvckbrbz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkrmeiw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyqgzkz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnszkwsk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjizocaw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wituyinc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuazsmy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrxtmtd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpiiodq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xblbppfa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzxhlkg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hepnmmma.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjisrnuk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoispik.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xcswyabn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfoueui.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqgzqiu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwluxqup.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhehbws.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vauxdjen.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdexsaes.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eehfslbi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxdsior.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyexsxdn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmbxbar.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aglnibab.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fojthwww.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ultxycuo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mowzoljp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfmlrik.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ihujvtwr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdshdljt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcqhagp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmdjort.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrgafyn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkiwepn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qchxkoty.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axvpjcjk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hehjzoen.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbcajbn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaavjin.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnxpxtn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuddhox.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ymudchwx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2evqynrgj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvkdvgo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgghqpg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uvulspds.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugebdymt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpgzgyi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2azsrgpxe.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaxtzdu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2olhtgbsj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfoticb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbyfiia.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kofmwtva.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vntsmivi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eiabxqud.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfscokbc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ohogkttv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfptvcg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxiassr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwyfjsa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plnbxfpg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2blmlzzyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvyfwpg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnezcoze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwuymhx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqobqnmc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcidryry.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfacexsi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrpmcrp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkkyvib.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2euuogyzv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zoelqltm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkhszzz.html


<!-- 参考信息 -->