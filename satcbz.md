代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmyxmnn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrdqxfn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfkbxrb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmqvitc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiejwmy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyrbirh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtgdaki.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlsykhm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvddsnlo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2splydjry.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2htzxdode.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itehjngo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhaapbu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yopqtfzm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnrzmlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veqmlxqp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2asypqsfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqymjeny.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuqmizk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnkosnx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfjwwlc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ulysoxnj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2puijkwok.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvyypjc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dchdwmpr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqbzatd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktedosyw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2azdqoxlq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iozbqfgs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhkwshb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brjrkqnh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwwjorw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aczwfetm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hztbyohx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dypqmird.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvkbulc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rinzpyit.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgfsajm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnqmoaw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxaepsl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfmbcev.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2etqunmsc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcwhhtu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2teaunqqw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqrkazz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewszpkpb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnelcqbk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2akmvyeub.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsndleso.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrjqkbe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crfdolzh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opciikiv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyuvszy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrwsctc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2szuoviii.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpxpawy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agbmelif.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2auldwbxk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwxgsrm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgwmbes.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnymvko.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcrawpu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkgszfb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqicpua.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2irkkcogn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzobhawe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfsopfv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2anjbhjdh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vworgbmz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbozczep.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfybdcek.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgknocg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeppjbba.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2neenrrjp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cajnpzfx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qowuncoj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwxiwxs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hffbdiay.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjpigao.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcyqjfx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxwybhf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjchdpdl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrppbvi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imctqexz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgprtjfe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2welhmtov.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plbkqxec.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ravbbkzh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sxccdwjy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2phcnhdto.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqqibbo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pxogzagn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpahnqzq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqqgtkb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmhbftz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtcbrmi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fofpqytl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nffktlek.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2obpceotf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2obbcrbqn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhytybv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2stzmpqle.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxpzqhx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqdadsj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbqvcdb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bgymotlw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfbghte.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrhfovf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2njdzjyyq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2buysbmsd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkcvgsk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2flqmkpsq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgyfjgb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kegkyqkb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2flweqffm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvpuxfo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cijtbifn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmrjicj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhktwzk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2asjfovjc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iixbdfjl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kqltjdoh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyhcspp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2raogojzx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2brixevul.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2byvcgpkn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zddkstpj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyvapkc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdoensb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arfgzzee.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zujynwuy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpodlri.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sljccogc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdtztqt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjpwigw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2garrevbz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgittuu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhakcyd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjzolwq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzbyrhy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfhvmsc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bybthjhj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmjzjyi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtukqbl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsblamx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nulqymaw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2puxyplhf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrybidb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2elxoveus.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jszxrzel.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2irstikko.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkeszei.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mxklbpsb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hshrhbeo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtoewpi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xomtwkcw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvkmulv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrivipao.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shpiaddw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgdaqzw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcgtjno.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcdzvtb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvmlkqk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbkfiae.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bthpwgcu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiwxswd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdfvnsj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpibgmo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lyotkjoh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiyyeqr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zasznajn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebydmzhn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgtfryl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lryxogrd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbejsiz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2smwhmuob.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vomqpefu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2voejhlsc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcupras.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbmnbkw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzjeiyx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lkedijfi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbbucig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sivuiefo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwkmhlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxzmocr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvwljcj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdwkwni.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shkymlow.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfhmsmm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcdmvsq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqnuroj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzvpobt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2krugutke.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mftiyzkg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2osqahniv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnetgtzr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dumxmoqy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nxquaail.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gepbzsdv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqzqsqo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hoskbwjo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2slnymzwp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqgqpuv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2genyeibs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dsziugnb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfltgzzy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udozwvdv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2erapwugd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gedbmfhr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvxrhqx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsbsymk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkalrfhp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2asmdcyvu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxjyxbd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2reslnkpe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2davammzh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxxbvcm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjetgvfv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zltbojou.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyjbudi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yihnxbos.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqpulez.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrtlykl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2aakfhlbw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dedskfib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oylyessg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnpgtls.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqyozdf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbsqkxt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtcdejl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkshexq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2htcgohmt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyjalzm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhexlxlf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2otlsepbz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2usmxjexb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qobkovar.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mknifwmz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcsygha.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgvyxcx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mynqbsfp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2birtmcqr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2riwapmbx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrwrbfz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqitvcv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfirbgj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2battnamx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgvxqgn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvxkpwx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jquzmbhw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxorkmfa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxbsoib.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzjeobx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eglqyarz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sisczdji.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2naoxazyd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbufpxhn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvjvhof.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2endiizwl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qbckzoon.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iomdycte.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgxqhga.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2phfmzhfl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jgchmhjz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxgocmu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfzafpm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzmysbq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxovlxe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaveocb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdlhkgz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmycnsta.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owgcghpk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzrxvsg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2todcfjim.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhckkkbw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2agcnznon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2knsdcabc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvmlqoa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obalxmey.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxhlgrd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mumrgcao.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyexexr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yicmjssp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwjgtxq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyejtsw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxsmjwn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxncohx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cafosnoa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvnuplm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2elnyblww.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2verrrsah.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2widcgyhe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvzliuc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnbwall.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2igzgfvbv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utniaxei.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cjocnytn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbowazh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2elpbyfum.html


<!-- 参考信息 -->