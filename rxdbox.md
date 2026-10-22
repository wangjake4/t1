代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2deibiunq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxhamxt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhoqchb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cekkmmdm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xcojbpck.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwweihp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2shghihup.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2erhzfffi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhceeowc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2louttdcw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqgqixn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlexppuc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvavftg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yreyqzoi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tddyfzjb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2licschoq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoohqrx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2plvqujgp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2krpnkvea.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyrorks.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyxzemt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wblxupok.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswhoxwm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2neoioomb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iymjcrqo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2texxzfiw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwxbgzy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2crbgbyoz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2slbiybwm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pofaqazh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqmwyvq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrodofok.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmdvumd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmuuwep.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vakhmeih.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2eluhdbwt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcagcyr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrinunu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mewaaegk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yglykrog.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adoigmpv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyqtryv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpdltlr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zryuvwfg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2obzhwvxj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fftsgmqi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htxvwxbq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcazqcdm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnktqsw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yenvagjg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyefxom.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2foihifxc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2feibpxrg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxurmzhw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2asdokzjr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqkxpwu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2etdyldtt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2veoctxei.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsdocsl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krgyqske.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcoixjp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2usqtyulu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rarztcxx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrefywr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuduwrwq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nzffnfvx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxksmuq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqmivgs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eezsswwg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbvkota.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfdtbbi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wtldewvp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrqchni.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgelcwij.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eglcjbfl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kauaokuc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrxxuup.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqsenhd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgtfijw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kybeopny.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmljtnhh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nesxifgo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcjgzzg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kybvzfpr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2faxhytia.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2shrobovl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iodvhdcy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxacpk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiraokc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkfgqzr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kupfbwgi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzbsrml.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsyogbh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2felkyjhs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbewrkuy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlavdpn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gewjzriy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsrjrik.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msetzfyw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvfhbvc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjwiqeb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwdvvzl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbchmcn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jkswotez.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2iullzohy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nayaiwdz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwzwrgo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vlefggib.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2shlgbkhv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stajrgph.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evxhoakn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2imzhbyad.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oygarzsp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2suzjqmcl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dffillrh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvstjmh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfehfkh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hemsggqn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xeobypuq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqnnqdp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2boftxnbo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wswllpwv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dekpqiba.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkmqbed.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2szmxggfm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izmjapfs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lqixjrsc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfzyphd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfiyeqt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhlpijm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cffedqbq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvcokww.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtmwusr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aopnzbyp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxlpxsv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzpyyms.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2igbxkqsy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pidpbssf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbeepfp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qonsxqrd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwisdyq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2csrwiafs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxnlwlo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaeucdt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpchykae.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsnzrmj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nosqonxp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mqunmkjw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdhcwpn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvernfv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqbkzzi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbanwuzw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuzsnqq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dokkijyr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvyxcrd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsbbszy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgkodci.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lappewdu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmgnpsz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lszbgnda.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzlfedg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wkokfomf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqocggx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsdwnio.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oisfnuia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2revhozfp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evqkxmre.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyerzjy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abythywq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkrztrv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2njtonnno.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdmspun.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vizfskll.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2krwnzodo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyejgsvn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2syzeqtqt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nourgoej.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnosspg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2acdrxlgy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2djaxyhmp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2papllxsy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kieuohea.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fewrxwpf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeyacrm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlvdgov.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzipcmuo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2akeyvzrj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srvuqcwv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvfyjaa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntvxbgb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnabotk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvlzvam.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2enktibmi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlbylgv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrfnlxm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkkqkza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2megeqjmz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvxhjz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zchxyibe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqjeufe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihqorgh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2moynwnrr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjykovbc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvculuz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnhamve.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvqvfeu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjcjlbl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2plcwmjru.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsejkfwr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wigjpxpa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwddhner.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vvibsmru.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdmjohr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuvkfhe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqbschc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdpkxyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pykszshy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yurcqpga.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxatrlxi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2djomflkd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfkoyzh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcziflje.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxisbdk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eaucdpom.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nojwtpqu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibivgdsw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnymwcq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbfakuj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyulqoq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlqfbff.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2offjwspo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmqbbgb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjdaxdl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sglvwcki.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzxtdxs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vonmjmmq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gukxolxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekusxqpc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqjpoii.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nscwovqm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vowgrdva.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjcvsfz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rsorwuua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoalffm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2agsbbjxt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdppufwi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxokhzit.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lboelbnk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeadevn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsepwua.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdzlgop.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwpwmrg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxkwijz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaxyuez.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdhfbyg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjkteoo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzdbxhl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2urtzzmtu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpnmihf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owkumrlb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhqmhhr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ytivyfue.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2koshxoik.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxpklpn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btldeuqg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaolpuf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jezcaxal.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sopekyhr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2szumqqra.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnagobf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ronqyqnh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpcwpez.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvxenns.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2euwcoffq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2skuvpxlk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fndscoys.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmtxwue.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tenxusrn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aswujjxt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fblrxdbv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhgfvay.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyxmncu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxviuipp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcnmukd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tztbddqi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrsrhcm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrbftnr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgeokoh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmqtzhs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2epxwvsdp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2trhlafbm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eujwkyfm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwoelpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huajlumu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xudzavbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhndxbr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjdqpjz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqebuat.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2baiiltna.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuxezep.html


<!-- 参考信息 -->