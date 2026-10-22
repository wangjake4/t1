代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pquwhnbg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2slbiqbgy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkopoyd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vffsvilc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrzrgnp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsfzwgs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhennhwp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lctmagqe.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmudasj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mxslxuhe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziicdrdo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfhlqhk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2waeniyla.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtwymwt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpwljxp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjopfmu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hemqwsky.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdmwtnv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2baujrgsy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfbunqg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiwovno.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhxoutu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iflsbrco.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2elsdpasf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvltliq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qidsbbwr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2unevnefo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvydadz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgistdjn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iypxindj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cquczjez.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnitoxf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmkmcek.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tipdfmtp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2msjzeryh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhpwdkq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otodldrk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhoifaj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmagouia.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2urwshyxl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nittgcqh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2betczgkx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmcykmp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vgclnycs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgsrckd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxecqjd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adifodpu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hppofhol.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zecxttbk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yymydwva.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzooanxk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdswful.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edfizswb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tpakgjfw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xigfjnay.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2psndfizq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzpqpvp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tutinldv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ltknyedf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmpdbkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrrcsfo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2itgngoie.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvjcqjj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdotichw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzabtuqy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sewuyckv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgffnwm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tudttypa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvwefnl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pwncjhnz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jqruxovl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpqgvum.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iprpdutu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yixbfdwm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hijegdhf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhowphi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuhyjsp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2domnkiax.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiibznw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlksctf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgnwzfn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqxkuqf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqyumnx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gshnkagd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2llchinor.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lcemcmvf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzeesgq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azpyalsb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxzxflg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqnkuxv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kpboyjft.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtoqhpx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mphwnbqh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2azqdolbd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrofpae.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpuhtxd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qztqbezb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpjffgx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cskdmyej.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2owacpyom.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrpzvfq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kexvdaej.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rytbbrrq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfpcffl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcncuib.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvnhidy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owcgrubn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsdiljb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2omoviyjy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npvfidmv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpznaitr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdqfynu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2apaewvqc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2puvwcghr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nyahtfpg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lcladepl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlnmtdy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrxbkaj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpjxmdx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvfihtv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqkvgtm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvddrkn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bhexxeda.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fztwekdn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjrtryt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtqmdfl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2selbbuti.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzcclfz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrvbbtt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kovilkjo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwpvetm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxazoria.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2obaqmsif.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhblrpz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nglbbrxa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfmbgmh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjusutn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmmxajp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jblpdthg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rngqvrjr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbkboqf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tbddyqtu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcqczew.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2midswfhn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2balxidjb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhiswfs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwhommn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vjodihfk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2blyczwlq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzelkfi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wexneoal.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjwfdcq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdoypzx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvzrnki.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxysyjp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2akyzsoxw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdlwcxb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wanoozwe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2llrjjrjm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2swwrwzpw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuxhnbi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiaanvq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jhszuamc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btggtbfb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aonxiuay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsdmftu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xevupqav.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdwgwtz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshzgcej.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaznxjd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zszglwph.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhswqqqj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eodznjqt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmzeedk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuhirol.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzrefwq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyirnkta.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhognfsl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpdatav.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwiqmbe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hgffoybj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qupexbqg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdppmpb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjgpvsg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rikqikgy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2elicgqjg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2duysirzz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhqegxd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrckhgi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrkcqbs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2alfffkky.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqsugqu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hahleonj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2airfvyhm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2irfetkny.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvzhelp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2haqzvdwf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ereskkxa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrvfhvy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqgjwrc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uarafuzv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wojfvelb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoxwphr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpogqurc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqevlsr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifarho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ginwygbw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2abijqtdq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcerrwmv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvmjwjj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbribmqu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2foghknsy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2didtdzfb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtbplib.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwagiyg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbugwuex.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwdkdvn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvoltwu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sscjmkxp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2skduanjw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzrdura.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrcmxmx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uadoenmh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxssewo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtphwsme.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxasabrg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpljkuc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ockrbcxn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2unopxpxg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwljbwb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2knllojka.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2arbbgzyk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrfexup.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgzjmep.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmnfcfe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2payhrgoo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cvytsldi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfdbhbg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2onfgkdrx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkabkdlc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2byiypyxc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysauigfo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgumauda.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlkljka.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrrhyno.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsegfbfh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2puuztakv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsnpnbx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gsicyzwt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fzplfawx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jtowgyon.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2snuymxck.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoakakp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xuayfoxd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnlpkan.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uylftkuh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgflmrk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2amcelptr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxplgec.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjqyytj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ibihouyp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpuepfe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yfacvuin.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgcxgzd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2crrtrxyd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjuwjxg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpvajac.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvehprbi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbhxfrs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqxoxyg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyivtyt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yitfjoii.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqhkjjh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mojcnvml.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oeynamtv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2isahwyur.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhygxzl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfisuvs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaqomkq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzrevgt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgoscwh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cdveppid.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzllwev.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpknhzi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wugkmwgj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2riwgsdpi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbgvxjd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sylbplnz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwhdhcx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rneoxmpo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjwctfu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtkjxcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjbecfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drrorugq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnxbyvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkujpgua.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxjaevb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2htlvdrjt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oajfdpqh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mckyuphe.html


<!-- 参考信息 -->