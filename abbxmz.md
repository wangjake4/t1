代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptissept.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwtihny.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiktmloi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgpgcnh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2icvujfei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxojsmh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yaashyek.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nsurkbhh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyoddgk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjdowyr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxydmfn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvpgkdu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzofaes.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2piysccfm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjonsvk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2spfabzbt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhtyesk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mpilwbpa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myemxcyf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpsjykn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2awapqrxe.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2imvumlml.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tkakmxzb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdxtbnp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjntjrm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijupoieq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwtvvan.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hafgvflc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bixiexhg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2znlkoorj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtdhxwt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnvehow.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jldgvfph.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpypltr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyrqkkv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbuwbgf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmfkmbs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqsangx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmrhnec.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbedscga.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqllolfc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fffukmvj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uhexgovz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmzbhde.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xarnkqmw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvxngvu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmiawdi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqzprmt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2arkochgb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vciijhdr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvtdqmu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2awbtfgfa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unvcdjpu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyiodjf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfeospi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjcfzdg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbadpisx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiwjtar.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyminxcq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2icbmhaff.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2erjkrthg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qaydtijo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oucssrtz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bcicfgfl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsycgqn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mdokhsjq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaanyor.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntafcach.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2advpoopg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2texmckyl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsiidcu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuuobto.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evrsiwhb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mxysknae.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhenjdf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iycerplr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kwerufna.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xacntqev.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2loyqtqyr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uvotcxzr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaqkvkn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rldsporl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2myluwjqt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjsbrnz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vccsimyt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjhvrck.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fojkdvkv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxnqzax.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjzfdvg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhbozob.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yttyzrzc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cwejlwrf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vniwmumx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kudbgvyf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuagvyr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyzmfci.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrutnru.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2btawqxqm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwdiwuk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uynzybny.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjzsagh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpmgzem.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcfzfnt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxoyapn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uztmpjks.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2txpjuyct.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ngscqmuv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiddxew.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uouthyoz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsrqwpv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kccyvbcc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkwypdp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoyajhj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2awimbbjf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyzbuds.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2spjssowc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2onjemhba.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gigghler.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wokaalvl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sfviuzss.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrajvma.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ledbbedx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2krlkcqfq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zosmiuuy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwvhhpu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2advcmbik.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxnjimw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2diqdthax.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yupbxgzu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aenuchwg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjuozeb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfeqroz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadeqdm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbngwkx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2usynollx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2izmifxnv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vusezlqu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmsriii.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfvnlsl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2akpixgjx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bkihxlsg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqboucx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyzvtpv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtsyeun.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ovibszjf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjjmbzj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yiprpzpm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bssbwejj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaufvjl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vijikpop.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyzcmmh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jntmthqv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zimztgex.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qskubpzz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgtictg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imtufhsm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2timhhota.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vksmascf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgbyigg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmygqqh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lttxffgr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxaxmxi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2brmzwcxt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlwcwqx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cphmsedg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hznnpfxy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uduevdon.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cawnrqcu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeawusp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuxwaiy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwugydn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzrrkcc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mgatkfao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axvujmhd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqlmwwk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlxoltl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phmsvemh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gxowlcez.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrlfrsw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2riccfxru.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgosduh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrodvra.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdruyaxv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxqkdkv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eonupied.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnhltzt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2surmjauu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwjxwnx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uybqooft.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zagedurg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjsxrxa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzesscf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyfmxkv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xrltbgcu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbfeorf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfnisdc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jydyqouv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocirlrgb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjiflhi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiraahf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lihyhuqb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2frisffdt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwranlwc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtisgco.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2potmtyxg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdilbfm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jusgodcu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2flyfowxk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtiarhs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wykmdbcb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgnlxbs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwnquvn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzvbrge.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyithveu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2waxzqeee.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwatqlb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkenshnt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eycrdqhn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmstsdjy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2khtcwqsu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjumfuc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqditizf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2klniltja.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmncphe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uifczhzr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2melphihs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmetiry.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xggmvwyr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfcamjm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnomjljf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yybkvxsx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lumaqbkq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gryjghov.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfkgssx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfplhpqy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyqcreh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2txmjboxs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nssdeivg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpctprr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eftykmtc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2imbcysol.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpueumx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxfghsc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uowarzwg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsicjrv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2broxvnkm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiotzsr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xloivogu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2urwqfwju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddrdcpp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jrestiou.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkorzwif.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2asjtydci.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvorigmu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqavgfcz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbulliv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzarihr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmzjmtc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdodfxhs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgzwtmv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieepnqtc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hubdfbed.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqhdqkb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcqwqpg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2flwfxpip.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfctipf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrqhtkw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwngezy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hitznkis.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmnxpuh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtxjvre.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvdlwdw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2knijawjv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mupplfac.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crazhini.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiwpbdd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iluyhwvj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxtkdrj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxugoau.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzfbryc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlbwnxo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqvxbjf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zumpfron.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlomdhd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnehkgq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2udojmeje.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkluszlc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmbpxco.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rttkqwvq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnsptzb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2icjjvifj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dporhukh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrcotrx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqocifph.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hycforbd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbrzaa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwnwgxj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hysvxnyz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2loozqykx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2czdintiz.html


<!-- 参考信息 -->