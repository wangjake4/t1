代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kzihugnc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmyrwdk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiecreyx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjlywdt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2avzfhkot.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2doypfrdv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyttlula.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnfqqoq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfmvkpa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlntspo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzqyyij.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xivfvozs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aujhwlcf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxxpjzy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fymtvhqf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsryhhk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cspsylou.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2znklpmmo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmqnwft.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsmicui.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zysuswsa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2isqulqjp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqsxffk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bupypqqm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2slmnjyhp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmcbjwo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjioaube.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eehqcfin.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaewuqu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdirdpa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kiajibwk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wilbtljs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpftvixm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhafhexm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icxdlipk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhelays.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcgxnud.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfthuea.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efyqgsfd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhokynf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdmuksy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdksrtke.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itjqpmbf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdstpxa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asfirasa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvqgbav.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lapombbj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxufnkon.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xceoggoo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbjwjcw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqrpjcj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ityxnoaj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qktkdeck.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvvpsuu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2thjatrll.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2msukmpzm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wglatndi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxylnre.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2prfumdiy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwqdeyb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjqzxlq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2akgjtxsr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjzsvlw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fymvsizy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riuhecgf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vadvwicb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhytcdfi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhzygra.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mfugwjis.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hfohsqwn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cydlfrqu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jyakayny.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhowyos.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdnjiqy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2botqwtnd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2noetvnxe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2guooyelj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ghooollb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhruren.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxllkhw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjhemie.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fabhwqul.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2trmfzvrr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lxidvcja.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkzxtis.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsadffg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2giwqphuf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeotfsgh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gprpfrod.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aanqmljb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fegzamnt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mozwjnxj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpdgcfp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wadqvbli.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoqvuxj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdteblp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhdsnau.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjshxlvk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hytcdtkv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cryxmixa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rlogskvh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsuntvn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlphagla.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2twdjyaic.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlnquir.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlnkkoq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fssrktqy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcrixjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2waeepwzb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2digqtfql.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnsidhd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2teqmkcrh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gecobsvc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2utcxkjpe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mylqrvjn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmdpvnr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mznkpnri.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbapwlgb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrvrnwf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gwamwclt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2glahckza.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2awvarmpl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uznbjykn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yajshtfo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbmrnbd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmnqtzn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hagdmkxv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxizngk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uneqjffj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2psmryloc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpekzce.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzxdwsf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrxatdq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2popjkqtm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sshzufkl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oniptyuf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgubmgd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hogvmwqc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjyiotz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqoypac.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zanhtuzf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmustla.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dndbsucp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2frqxuofg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cargwlwu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzkdxwu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhliwlt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qehndiqg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxnlrts.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dxezprof.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbdgsic.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfbchfv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2udxkgijm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aejbiahv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dbanukpl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2djoedgpr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aqumxttg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzbgmgb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2namimvhv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmascal.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoyamdg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbeswzp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvdvbbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2baphkixc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbweqpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kubugcon.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlkipvm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmlpbbm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihixusxc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mzysodqi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2odijmovg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqdvtnq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnezdth.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zeybnfsl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlxrqzq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2omdwjuvi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2baxnlbum.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oumksxob.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gudabetg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2waphdlwz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2trypwdnv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgzhcee.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tspdlahz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kggrgirh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbzwtvj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwsxgex.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjyimuo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fztmknnu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xiscvaix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqqmqtv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ictcxtul.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2grzkhmlo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnudmyd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aomdgybc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsdqpur.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eupqyjsh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcthqceu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wymsldsi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjvdtla.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2skvuysyb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrpdpkt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiyuaak.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvowcfz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eijkvzfi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuopnup.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbrccbw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nahazpxj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmbcfkx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tajwsxba.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoylgmi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdglqggm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nccreryq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlyscuj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2apfbzajw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfazexjv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqyyuyq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaxklqm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfcnbit.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxgpszq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2btywtrsj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lejxwjwf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbivjbr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmfqrec.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jltqdyvd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfcpyzg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpirqnpl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrndybn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vcihncfy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zsujfcob.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2inntqnhz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwtoxov.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2subeqgiv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbwbucv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljercozx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acphnxzo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2flksrlag.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gipauxoj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjbwpsc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxegrup.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eawoetii.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjajrpu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhitehzv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvvnpuq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmqyfvf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2msyfhknr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdktywf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtguaaf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrfbzcw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoctord.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgzwxju.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpcqvof.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkstezl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbersqif.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmxwphn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjcfgyn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbsezrh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwerpar.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fflyvtdu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dmigrykr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiuudjl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2twtpijlx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nruptjas.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gujkxeij.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwgqssk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbbvpez.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwkjqmt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrpvaqu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfwahbv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqjyzum.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zczvvyoy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgauqhx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqkixyl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhwprvm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlumfsnj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwgcybi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyxecuk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrgkckp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrgsdsq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdvwuzr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiqjnsj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoezrwaz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fukzzfyn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwqnxpx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zldkmmmq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdsnsvj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2thabxqzu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sukcjijv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdkbfky.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkhezrb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ijajfwbq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehghtzxc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvixhxe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2epupafki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyxrmjc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtdrbuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbemorzk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbngdnj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgymbie.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiagmlxw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2noploxjh.html


<!-- 参考信息 -->