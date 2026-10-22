代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaevchzo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yygfwplh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhhtpbn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2luwtwctp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxdydfl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2twqukcmq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwkrcvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhailock.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmtauxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kioytgzw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2njdmlzci.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeyhpqq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wayenmsu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjgyqqr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdijbcj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwrbbyb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kiakgpav.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gehsockn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyotsdjo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgfytdk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkskjzjh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2krknwaab.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqanngdz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbpskmt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdifbwh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeyhalr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zabeavne.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvryhwd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoqaiox.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ieromhej.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjqzrnw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fpikvaco.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dubuwjjf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiprmjnx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwwerkj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iutastky.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrkaifj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeuiytq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lezsrwuz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sautphkn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hybhdsbs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcgwblj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvbekdt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrktloxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgaqnjg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrnpurj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnzskpq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2olbujisw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2erweagns.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdcujue.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpwcdxf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpzpnkt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zszvehjt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzjfzii.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unhicmgw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fllmxxjh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbsasqu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pabgkaag.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fozjlsmz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2famygmlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxsdxlb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsllhuxs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzxsefe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rloqiwbo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akogyjdh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2araiadoe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtudkcb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xkibzxkn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxgqwxy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hjccjfco.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nlldjslb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiequxff.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhadzjk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsaaqey.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqdrtmm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppccssmy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjpcuqe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxdjecw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxaouhq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2izchtelk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fizhvjaa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiapunn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqowmwd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2syfgsnyp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2alfjuuwq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbroeew.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuscxkd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxufjtc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbftfizr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjjaguc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtngcsa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvhabnk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kswenjyj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2udlybnvy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2adcplgxj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfnqlqh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yukhqduk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hgositpu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ponsdhlk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxigfqj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2guevvdbo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2reszcxrl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nivcxhtz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwtnsta.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uoibwfkh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpebeqi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2umitwnbl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzihzxp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyhvzaf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cydmzvuz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ceasdrgy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyltvfig.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bukdgnmm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rikyibau.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scppjlcw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pmclwiwg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rovymcxb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtlyvoi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okqpdeum.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtpugbn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2txofzlwo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmdbftc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edevmyut.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdnjwpk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjitnhv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpnlgwk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqcwbvn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aydftxwq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2srhagpeq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhxfvgc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjwlogm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2msdgtoib.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdewvyc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqilawxd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lljypmhq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2alczhhog.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fdljwofz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvlidyo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2aohwiwzp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfnuzzk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlkrlxb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwyhfhi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhcfhbh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwpftsz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lvikokcv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvworuuy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cytdwzfn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlgmpdy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlmzphb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fztdergd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkufnsh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vyptuciz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhsvgoc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2psfrgnfe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2stndjmwm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqzcuze.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2awfmprxo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuehxgh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hskulhad.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyaqbcq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eormbcvc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiebbjl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmztkrw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdooiban.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oztcstyy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrexwui.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pktmuoow.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2okacyftx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqmdvtj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fclrvihl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgoneou.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cteoizik.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btuxcpsc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgabeat.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcidxwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyvuasz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2weqdxzyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfldaxuo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjamrzc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2odiercxh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxbxvnt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmlleli.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrwgvww.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmimnry.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cehuurqm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvwvstp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2czpeahst.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rydkoysv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2scovquak.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grprfudh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpooymm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wgykijbn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2avqaqbxm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwiywdh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhuwmky.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sonxjtzl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2essgoeii.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pedklulm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjeyseq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nryebabs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfejjqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvxtbtv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsbrxby.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiaetgl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdwxfqe.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gspytlfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fueqcurq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgerwzn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnqutmt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tigiftwg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2unuvhkip.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2igmmajlb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmgnmoe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrpldsh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxomfei.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2laekhgch.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2opbaxulu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnqzked.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaykozq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rizjarsb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwekupmd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lywlnyoa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2igyyyxef.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uekbgffx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvykamvf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2osxlacdh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkqcrbc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jodnbovb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiwfqtk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxpjdua.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbjozsv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dusfhqco.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsactxq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdksdpcf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bojkarbm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhmmtbf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqegwxa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjossrj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2urnhzyye.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmkpcxb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhwbdwj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rqypplxw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2evvexoxl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqnyjdl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtybkxy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaxlsin.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kstluinj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2momvdjvf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oezmxrwz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eushbukm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsarusb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayouyuxk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2syfnflgc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzjfihq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhvtcas.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdddhewk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlnuiin.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwltuoi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lujdevpf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bddwjedf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dffsamql.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kszhzorf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrgkzeg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wctnybjl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jswjfaei.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnksznkn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiomqaq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2symrzwxa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzwtyrj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcqmsal.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eosaiytw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aituvitb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2emvgxhcd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mphikuzs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2frmfbkho.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoydnqm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqqnxno.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szkqxism.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrpayvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2afygmrgq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pprwcaww.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqzjyne.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqltqdv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aszmjpjz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2etiyomow.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaxidjt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tynqenpf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnqwbnu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggcvluo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxveuzr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2avsfifli.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dubbyzzz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvktmnsl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iaedftrb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2apxziayl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kelceflr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqqzqtt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpvxdme.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2annpibax.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jlftiqfc.html


<!-- 参考信息 -->