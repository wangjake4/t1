代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmvcrql.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ratskldt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2suvkghek.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpkdyxx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqphpqaa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2byvifzbw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adhmsquy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lfljrkin.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qricaief.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqkflrl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfjpcit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yionsfkt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eeingsvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wngolgms.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vepxggug.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kwedcgdp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjbjbhl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2easholqu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkaqlyl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcwpdjb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcuocab.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqartmsq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyhjney.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbgevsf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvzcrbt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwafeppw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhoqqjf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkntnhw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tujeefvu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bygydyst.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhkzkfs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnbfoen.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaasxhb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkbmfiw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dwafttpp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbbquzw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xfntwugt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dveuulfw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxwwuds.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2efdcqeis.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gyztvhgs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uekyknct.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fekociny.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2scdylbxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thplzigq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvgmzyc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oepigytz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duvtrfej.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzensml.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2urchkpod.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eokhsxvl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2unpvqagq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpulpgsh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uggfuxbr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2luvqvzby.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2shuhmheb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avajsqui.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhztrzjh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxftfmlw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khewsluq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhdbsra.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcqgosu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enopurxg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nljnbbrk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyvldyn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhvojdx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnzmfnp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpzhzbq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffopbped.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtjpbor.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cldjjcfx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkwuawk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpykkpce.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2byxeyufx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpijbgm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwfgwgz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmqvbrh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fidxadvu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2curithhb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vquqcdga.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lznohajg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwcxspm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhzntyq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2znipfjye.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcyauks.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuzognj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnoiwgw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcxnola.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgvymbr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2akwlpixb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsnzwke.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efwgkbhw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bekgmogi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2offxrsqd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaxtaua.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2geioleej.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfyhgtw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyuyvhs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jevwphmx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbfesoe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bedzbpvr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sraahizj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhnmidk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aaacaclu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfwujxa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvutttp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uaycowen.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xaidrptj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uxidmims.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcehxec.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxgidsk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzswovc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzomgqkx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrxeeya.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zwypcnvb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hitoqlwz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqqlrss.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxztnpq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnushiw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvvmivc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ertcxbas.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2onwnejut.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwrhphw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yenmecmx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2utzicmzu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtqwvby.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyoogtp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lbksswjy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxkuqor.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhkjbsb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2outxxvrx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2loykdrxp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpuiolw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2todfkbou.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxumvsy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2awbxnuef.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2awqsophy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2veukchqt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuezivv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wiygkdfh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoatybh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nswiqjpn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2itawayzk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tofvkltq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpjdfvj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pumduryy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnicobqj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2utqyolqs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jmytsbhb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nuelxkmf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzlrzln.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2keamdxwg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iprbganb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnustal.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijyesy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwdseor.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2toljgqvo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrkzvzu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2neqyqmby.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdlipnf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgagcxx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xceilvnx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yojhkuxg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrkvezo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nbatryos.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkzdwqu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkhtzzm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmngojzs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbuxbnr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgcfrsz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaqmtme.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qfklaybw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oxonvmft.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vqatshev.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhuemum.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2euwrreoz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmpjdts.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xwthlidj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjjnmpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrtcuxv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnslvoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbhgaby.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hoohzwot.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbuazow.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthxwvnq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmpkwde.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjmzfva.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmyzgsb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwuemek.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvfxwps.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcuxshd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uafdrkxe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxnjzht.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2anwajwll.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkqnjeg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2klddpfub.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmhmeie.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2czvxgcug.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrqhbwf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrvksdk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kddjypvp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxqqlqe.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmplzqs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twximfph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvtimjl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2witxhneo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fioxksas.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfiwawx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpzgsps.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2blnbjxjr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsgvwkx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvsxwxn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgefgsqg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlrsqvy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyowtom.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xaycfynj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2olnyvpch.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcfizxk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2domxaimh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjapvaey.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2amczdowv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrkqijx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcooixw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wihghyuj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2omtjyqzy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vpecbmfn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bifgphxf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fopjpnfi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtmlqyc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmauikry.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpthrzd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnksrzx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoojwhas.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iaixtisc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmwtsgo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zjavjmom.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kltkvnqb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftntgasm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgittvxl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhutgpch.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2blweuygk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkurmgvz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwygwsd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pdewodog.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2duwqgqpa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aywpatle.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2onnktxjr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqsroqb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjsidcf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjorhor.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckljects.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqoixzo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2usoitohz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iprtettp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qigmiqoc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzklglh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfimzty.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nplovveo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2csrvvmdf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxzqjqr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfccmpf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkhiaxg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eurereph.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2idkohooi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gfztftgy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwjzimy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtuzvdz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjcztta.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2titypopp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phmmpyau.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euywdalv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiawctd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cistaanx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmetsnng.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pgufhvyb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjodxyq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkpndas.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxbjvip.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rogunzvp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utmpqzno.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvpcsjb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgymmgnq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdndkhuc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvmenww.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkrsuar.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrphuiq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ereouron.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2abxlhtnd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydltvzbt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgisnhq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpibujc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2enwyuyyo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsvdgms.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvotofs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiurrdmn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqzofle.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbhpcmu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvjvqki.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcjmbmr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyjxaci.html


<!-- 参考信息 -->