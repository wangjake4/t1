代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqeihuo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdlsuiu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2idchpmqg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isbyqsmr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2grxpubpn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkhyhta.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsejimst.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2svdbbfgx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjlsgao.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmfwfio.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jamkdalo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkynrgvz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfedvyk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khfeisbl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2goekvlyn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxpnokw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeamymb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kkofypec.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpnmcom.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mskvgfat.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sricejjq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxlhvoz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yspioumb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgujapgx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2whaozasx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhloxhzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjblvod.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qycgpcik.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djmyzhlq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hftoiagf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpjbtcj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvaiwkb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuqqfgt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgacpri.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmthsab.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvofsidg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prcjyfum.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgufyuv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmklfvd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdnzoba.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avxejijc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdwgtsb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqbigga.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjnpumb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkfoqib.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tbekdprm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjdxvow.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqftxcj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxivgehi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfarvqld.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2teltiskr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlhdnpv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bstlgzfu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnmpeva.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2grnodsxa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxegfgn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2txzkiezg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2boidgxod.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2plevgaja.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpehultb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2glrfqhpx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuamjvt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvvsiaa.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnvshrd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiobpdv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ketqbyql.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfikmzb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgzktdv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnxwpuo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkkoufb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gliymrfk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2csbypkly.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyaaywf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aupfmjap.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2izpjcgli.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iucvghgg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrynzcfq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxksyzt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hneqenvf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpswppz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqbzxwo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bfybweek.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xabykabp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhyojcm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvtmxrt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzparqz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzmyjwf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2auwddejx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcbvuqs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tictmfpj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pjejdtra.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2odrpmebb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2birscjyl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uyifwtnk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmehtsa.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mucxjgmj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbamrze.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2akhjsspo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iacllsop.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfykmzvb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbpswye.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndouhojj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqokvoz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2aityijwb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxjanmx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgvuhph.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdckilx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gswvcihk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nhclwrkh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiynctva.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odfwlbru.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkzqotc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2owawamiw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfwkjxc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jiftgxzq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kczhrups.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxjlyjm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnfodyg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kbssvtfy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmdtfjr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfhpjky.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tttbvxgh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoeqqvr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cbikrqzq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qsltwkql.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaailydu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2twnxloot.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ynubpniq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoxqzgh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvvlbwx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tehernsf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kmygixyy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2swfmiiiz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvdyckg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gmugqhag.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvjtaoj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2acdttswr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzidmmoh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blwsrtbu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2evckryux.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvkonzt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyzspyp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfxrqun.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2maajbtii.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lracuegn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxeqled.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ychgnnnp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tljzzmfq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqakmzh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfvflzb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgglgqn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgsrqyd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2unppuofi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2voqtmjbs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wuixbqhk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rxshvvub.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2biekgnxd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpbbxii.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czskdnxn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzrbgiw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqsvuo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbfeidg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pueeujfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlpgjfb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxnjtai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrnobhv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zvumpnqu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbqimdj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bolartdc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iiulsjgw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbzqycg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gukjhzee.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuufgfm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgrevvr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeanucf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kevbbhmn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wynpgysm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cygvqocp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2avbjtxmj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2limycrdz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrzmibo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvklddr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2heybksph.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kztosvkw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwfrllj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxprkmxh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqztpwqc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrpqbrz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2canqbizu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhbyspn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxdnhby.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyljepqa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbvpgsz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drmtdovy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qflykjqc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2stybgtwl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwramxgo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxqcarp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjiqdcf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxpkevt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsvzmkj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhfjzud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nacovfxl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jorivpgv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfdxjry.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wseofdrr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwfhyoq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmdeebe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vehclmhm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwqjxim.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xarnykhw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2crialaiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkggsfip.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hausbgmt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnrxxbm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bpikckkl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqydmgtn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoieodf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cngasjwc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcjhamy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzddvlqd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xuixqqkb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbjnota.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imfwbryb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxfmhck.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhsyrxm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqimzfh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrmyotq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbcpavi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2evhkvxgn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjivkpc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpemxap.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fehhdeus.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vppqtcgv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkegbxl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2chjjjlhw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zypvzdow.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2frxyxkiv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2drdzvatu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swqpjmaz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgoiyfr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nioesfip.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqyfhrt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdhhmot.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmcyddp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tihmyqim.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwpjdnm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aoagqmiz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plhhwupl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmsimep.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvatgsb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcnzjvc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlfnmky.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrqcrqs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bibirfgn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2epmojkra.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2miyhabrw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpcxilv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2inchyjnq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckssysok.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uremeiwy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrjbbtq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtnelhk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyerwkn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpnmbtq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syqtqngl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2famkddqg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfsuhuy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2weqpcvjz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwcbcap.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtydurzk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhozpih.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbxulue.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2httoqxvg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjmfluv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqbjozi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psczmfop.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fqggzesi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdmadqk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcxvalm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeeczrv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lirfubqn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekgpvhj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbxbsmn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frlajgiw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgznsftn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2djmhxmre.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zstlgowp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrgnzlt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdtlrni.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrkfopq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2itaylfbp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2esmlcqqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywexttwd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2utvthcfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rinbenja.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvfipum.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wahrgail.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhrsnc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mlplsmik.html


<!-- 参考信息 -->