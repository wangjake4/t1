代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2azmycfjs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2arxnuilg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpnycfz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhihmolf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcauzku.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2izqfsopi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydbnxqx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkeficv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vyouliip.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxerdcnm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2giyagowy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdvydog.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mmctnhug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnxiplt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqpvzcj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kblqpjvs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvtkkhw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdycnvhy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfksdvj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtosddgx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vnysivjh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ombcfibw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjqqzvo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbckebrl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgvznkd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nptrhzyg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpxcjya.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsgvzdt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2equiewhu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zigvbyyv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gauzetja.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxfxqts.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2brzisckp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2teborbvp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyddksk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ghavcmvr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qagocoqk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpwuszc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmbqyfy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyxtnmr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwqzpkl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmprqggk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtttxrjr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2muiqupek.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcnkcfz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fscxlucs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdrtsax.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwghdrk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxliknnf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2upklhvzn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aabpqiot.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2evygejlg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyovqoyd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjrpsju.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vptoehzi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wzygrpkv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghikcief.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cptzrqnj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blmzajyh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuwcguz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsjrcdf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvbmjh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcnoklu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2smhldkja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frafsmvu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaddojj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpfmumb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhagedi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tigegcnw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjswhjr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zczznqqt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aokrozzb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjvsjmq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2reyzjmwp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2esmbvkkj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjfxdfn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtkmbvi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mllyiiyk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioclaunc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiakyms.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbwdmlp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iufrinii.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkikooao.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2htfmeytr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcjomke.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvehxca.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2utjdheht.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2eeedpwle.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2huyzfdgh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsvxvek.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2liisigjp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2amiygekm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbotfbh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyqcyce.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqctxon.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcrieag.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkqzqry.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ceseddcu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jahwhzws.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ougmpqfz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oeazalmo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvcktsc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmbtydm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbitwqqg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyasxey.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2smiwvtpf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bckspudu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqzjvje.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjwsztk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hehpvery.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhranum.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqkftwl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udwclqlx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2raoloxsa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amyghcrs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqsofwm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mstxplez.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ulganlcq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2twibdlxy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeooxgl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2acdmrcjx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgnkhkt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajigrlha.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkdyegd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iihfjwyq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkxqsqd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjfjgrn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2upxboxzb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvsdnxa.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2twefesgx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kznjwqak.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmkqzwl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeknvdl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adprxmnw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfuymzz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfezkjn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoqvxzv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lruiwcbh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfbivba.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ntssxdrw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sykfjqqq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moprkoxu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgovzyc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2odzrtrpa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xohglmwv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cfopguaf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieudumzh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbflvzy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2axwpvvum.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ineodejs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeondvg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtyxgtv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vchhzbdv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhroks.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvafsdc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxymphqv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbsythn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rardtxsw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqwrjmq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyufesi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpaohdp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zoorhbxf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fejbkjrv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qbknaoyq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlrimhf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2akwidzip.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pksczzka.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axrthgmh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkfawdn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqldiyri.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhbwsmi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2osvoszmd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkkipor.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhprhwx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiknmlq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2aavouzhf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgmipve.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2olaspmlq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzaysuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjpmxdp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2taxadfpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wohzznme.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asvwjjai.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfassxh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zosteony.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xzieyylz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ympnjraa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cktnunhl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsaiqrh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pqznuvak.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yasjocxj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mekuxcbl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtarqvks.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnbxfau.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgpvwlj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuzqyzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2occleofv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mfimjtdz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgntitez.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhinqcg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxrwfby.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvqxlea.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiixikio.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdqqvwy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuyxiae.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2khjjwdko.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bstezwft.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpwfpqg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nytpszbf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qwernjbg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2erixxguo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgljcib.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sdanjkeo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtivhsue.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjtldpp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yxidzxam.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2czjetnep.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2poeyjmrl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkinpszr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcowyji.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsmcqvf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhwlxas.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqhsvnp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2egfeyxnk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpauujke.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hciutwlq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2umajejxa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqbjrdw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyulygfg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxobxuds.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvzvrvo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gparqoft.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbxfnui.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjwzxyy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjuuxhk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2evyzlsem.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjubnrm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvdvyny.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tllyxuoj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2troxgaug.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwyklbd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znmkixyt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbdoagy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqagpjo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kneuorwm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2syftzzsg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnvetqg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvikhpah.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdxdffa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prdrivtb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tcctcixs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jagmyvsm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpsizsh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcakpnzy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqeedsa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhilkyy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbfsdjs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbamjly.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpacnxm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frwozbrc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgnlxbo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukokfiad.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvxlybe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgbtgym.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdezlpo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyjdmho.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2drwccmex.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfyhjmz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tynzaayg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfnihqy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dppudbpg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqilkkko.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2acltcsaq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2monwxlms.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zljcebbd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2povxpont.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwcidyp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjcgtqy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xbedwizz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxgfxiq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxbgvah.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xblibjjh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyklpcz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpporsu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwtptpd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pajpukrq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qydxtelv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2curmgodo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjohnzz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkdkvsd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpbryax.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiglgby.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yitaqabj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdyfezz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cintqxji.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnvrdqk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmlqbfx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsguwfe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgycxtg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwufpha.html


<!-- 参考信息 -->