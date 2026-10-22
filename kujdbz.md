代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmsdbyz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2afpuylvl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxvxpu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtwetwm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xldqadpo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhtljwh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjojruuu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmgsbwb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2evnoalzf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqsstij.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqkvswf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtikybr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvwsuto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxzdjcs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzjescx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2smhgfabr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ituhhfyh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rammnwdr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgjovki.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzobmvua.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvzsdrp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnnoumv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqonuflx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oibzigqa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrjlicp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2keoybquf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtijyknh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrpifpj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rxawtrww.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yawawkxi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bopqesrr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyoesrk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbozpod.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbxdcpl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aslkufyc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kojglysk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wzouxdso.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2roggufal.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbzcim.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpofhrbw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiqgdjy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbrnwzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaaaiqv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjenzro.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bahwnoze.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uaumsmqa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjilvucx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsapqtub.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoharnc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcgverk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbkbnto.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2haobsjpi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpkmopb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsqilne.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvqqwhu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yyztfhwq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfcbbob.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxczapri.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iozhfqna.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqvvjpg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oepdnaan.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2djhpakqd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trqofniv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2boztihip.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2paeoqsko.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cednhiju.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmslwrlx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ravrykyt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzylbset.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhevwytr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvjmcgo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2evhehotm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pphvegeq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvufqrs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2spfojire.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkbsgfb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaetila.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbbwrdy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfbllcw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxnuicp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsgwkbs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxvegdq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpqzsbx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dntvvnyb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2oblewxli.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfwcdkz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qywzdzvi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ssygzszw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdnxhlj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqunmpaz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zrabyfrw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dywcccmm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqijwhj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ridnsdcj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrlpnkq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eklpfntf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkbdldh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krhiyasw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dswwwdjr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwqfsbg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2psnhdnyk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaoemgg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfutgpap.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxlijsf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mdplptro.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsrdgfo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2doqpnagv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kbztrust.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoabrqp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2njhxzfly.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmxwnor.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfkenos.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyypbpu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2atapfpzm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uawlkefa.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytydjxnl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lduzxrnw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkchdwl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpjtkve.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvgqxtb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwmzsfn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlirzjuf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqcwmoc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcveqtu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nehcvpah.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oinxujeu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oadrbkug.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2llcmbguy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vyceiqgd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iccteugs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mjegxniu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkteuzl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jabdexea.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxedcqf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjrarfx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mljipmap.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgmokyx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwckfkg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxrunpm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbkrhne.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ttavsvii.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2beojyrcs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvcgvkq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2geeotwiq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2abcaspez.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uahwekou.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pubyvzns.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhgbjoh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzgerzy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rllrkond.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavqpja.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yltfvlue.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nhotqheu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgpwvab.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmemueu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nskslonb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2anuwtgpa.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rogwpunw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnfslkl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrevuud.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqilikmu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbbsbbs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlcnhkk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgkypob.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzlapjd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhubmuy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bclvuzvg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2paxrdibl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2viqdwnvl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzltsmkq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lacbaybt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kanhqrio.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwlpoqi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2unrcqkmg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2asxkgdry.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsakqje.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdqaehw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuwdfqq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2elqqttof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmmgyhr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kicgkmfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtvbegy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjzevsm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqqzylz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjgizyt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kltbugvb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpruzct.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2scnnxzxc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnehcxiw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nthzfesx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhzfbrx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nizifosz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgwqzty.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xecxqlig.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpdoyfm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbytvzb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lprkldha.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqvrvwp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhzplvq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2seuvqbot.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kagfrnqp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmruxjau.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhghsfri.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxnthme.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqooxbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyqzrrr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2djblewua.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2goyplnix.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkuvscb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aifnduqb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdantrj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ldchdiiv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbjwgzo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrxnziy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2swnbtrmd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2godddnnj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2judoniyo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lsemyexg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2izyxsfmv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2boursxag.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2drqryokw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwynvys.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvvdeqb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cvitphkc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qafmtacq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kygvpuun.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxxopey.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmhbxkq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzbjlcc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2julgmcvl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmddamm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbtlnyv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiftgsae.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaunjys.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkcsitn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2evwzkpkc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdnklnx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuaavgk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bymtesst.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2byqaooba.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjijtyt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkdanui.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nibwkzwr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oyojopra.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aikeouwe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdqpweh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmmpncy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmppvjpm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qfauqead.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qieocmra.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwgkthm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmkvcpt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fomoayei.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcznptxg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qpynomcu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwvkwuw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2roabyspo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ontitnhm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrnmens.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlanjqq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2olpogkpr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2srjisbli.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ukshyptb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaekywm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaztyfo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpvionu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nokdtitr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kclicenx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2feuooljb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkxrhuj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twvwdmwz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2csfwydgb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuuuvjg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ermaxuxq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjpidkb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlntrwmn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjhmnej.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epaxskhs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2esiglxgs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjchotd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnolovb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqncnolo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orwadeux.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjnxtnb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnteuzg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wslrfpzw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2diibejto.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyqlqgp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knnrzrma.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wccjlvfi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrvugei.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kidhcxyi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oscbtuox.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zduxlvvx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxbdmdp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrmyfxl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qluludzf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvppyqo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybhxie.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaonjco.html


<!-- 参考信息 -->