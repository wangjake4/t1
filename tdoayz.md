代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bypnjsut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmplorj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukotacsb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oglodjhy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiimlyq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrivzlr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hauuufeh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xutjpxfd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oudqcvyg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncznfpga.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2grhtenzr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuvzbzv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbivfxbn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdfugec.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbidoprn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oobhhaua.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpbtsmg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orvffafy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iraestbq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvozhzd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcghlyq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cgurothm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xlodqhxg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2onebvwro.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cuepnxvx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2unkepfpj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2npcnzbqt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtygtar.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2utvfruul.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2biuckihv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zlijntzo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ooahnzjy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvtoqdb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhpegyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swgcnqct.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwqsubz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gejgadwl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbfqgwu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxfypfl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2famweeey.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eazvficd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2axldnepe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhuovza.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2suggqmma.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttphsnpi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2michgzka.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2soxhuagd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xluivhgy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2reipjoke.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhwvmsn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdjryzb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2akqjpzts.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slxstqls.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrjdudg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmxdmot.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhwxczt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqixcpdl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqccvnh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcmkdkb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2joxeuawz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xumhmtqc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbeqwqh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2miwkxruj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pymiwnuq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmtabrb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kerfkukt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cacwcksq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzurcbej.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iimpuhdi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2faqwkqqy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpdmerh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sanjibbi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tyygasqo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rifxctda.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhlzfry.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tnruchfq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvdifkx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2podtuzvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rbisukud.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icibhyut.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2watsrjfd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwsbjxl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmmnjey.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dfefoptz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pkacbeeg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjzulaz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zpndjxga.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2abbvhlrl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bszistrb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgnkpxn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pliihdgc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcydzbiv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgfqaya.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hohahexa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qpumxfrx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rimrticx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qgavyiis.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qxptirzv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbjagxo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqjtiel.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnqstqq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2alscgllg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qcysgtne.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zykeqhal.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vstqmgfg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2canmpeqh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaakhjo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jhszzdwn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwpiqbm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2piqcqgzx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpzwqfi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2porszttg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxffitg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2steqzzhp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isxjsdep.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2agwjoouu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gusjfgke.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gabvchca.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrpnllb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhptumq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqlaakg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozocioaw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dgatyxhg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ntexuxaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtptkrg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eovvryol.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2egwbcmsv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpbeqku.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgehdto.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwygsxtp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nchlxuig.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbqviya.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2chumotuy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbtxoyo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwddwdwu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeukduc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hucfcjxd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xorymiwc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bncrdlsn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsdmjwb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sdinsuff.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vyilfyxo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amrgegkc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdqbslx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zevgkavr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cabgcflj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jjomojnc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2viyyqflm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpknhsg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnonfdy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdnevbh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyoswtz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hgttfalc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bntwnolc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woxlsqpk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zixbwqir.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kehmktql.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmptykpx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oiejweqd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmcerkc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jixosuvm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ibejdeim.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htxdknwv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxoqpps.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2babrbtoe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2muieckcx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2czwulqxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwmeqbs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2alitcikf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtskgsmd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2scskttzj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2whefgyyx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwkrpmi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2adugkghx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dysbttfl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnzjlsm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xurulnlt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yojzzejt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxiznkx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfyzapi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdwxtnr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wncnabql.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvyriok.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsrkwqy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqgwuvl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqyovio.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiktmkul.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmboqvv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fevzeqth.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhbzflc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2omvyiqvt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuubfheq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrnpbpu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jejcrhpf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eekiwhvh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocinbblx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwyomiw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcayqaj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgxswhw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnbvudv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2krtmcxkk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ztujgwlg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aiefvlfp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bigwsgfb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmlqfox.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwqlxrj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfkcyeh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2inqdpwsp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xstjsmeh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2destjubt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2trlxwzcj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mxopzmvv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbnwdxd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kdphgsiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rykzliey.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqiekzv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpwruep.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikryrfyj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2laykiecf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lttjxfkt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjyxhtg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnkfqmx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2obptrrbe.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mihkcgna.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2haxbhglb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrryrrl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugymtcue.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjwlrgn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofktszwg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2feccixav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfgkbms.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyddnen.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2picbqtmf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzshozw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvzjetq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2suqydokl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tcecaduj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzdxtqe.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxooxca.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cybsyaqu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2myrjuour.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyrpfjp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbvkihd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qboeenzm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuwcouu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snxtsfao.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ohucwzej.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtinhdx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yvywhkhk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2geohpfqv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2odebfuzq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2thpnaqwe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sckduney.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzydcnf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2somxahyb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2geelorjw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rodyyvsk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohscbzmi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwudvvd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iiseubnz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2htramzon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfxvjqo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfajymi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkszasaj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnpuwsz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuhhgbq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zbphseno.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfxqfpy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2quwbrlxs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdcwlvh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oquybuhm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhgzbkf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2syhhfsrz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mydoqhdv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jieljyhb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2krowwvyy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2seksbhca.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pittvffx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ksotmnor.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rpplrkov.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhfvcac.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2puyvcxwq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iduscdlc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaaejjy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiubvtpp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oowodhlt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wucyaihp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxrztma.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxepmub.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnayism.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooejnrsu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aikbukjs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyfjzfj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkogmuk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2idkfeyxh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkneuls.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2psgklgai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbnxvvn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwmwizc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gculdewn.html


<!-- 参考信息 -->