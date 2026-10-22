代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdsezmq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzmjmqz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gzquxpac.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxrfrda.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2voppjctj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qnunphfo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2irbvopac.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgipztqm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsnlhvs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pwroiixh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkieqtjm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2czgxyzzu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgjemgd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrphfxtk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhaecvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tippywgr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjutahr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdsngcn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiuuoaa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmnbzjv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2erttaakd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2refeyeoh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucovjkdb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idyygzqy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fseguebi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fseciela.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqtzfbj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kksfxfsh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvjabhd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvzjuzz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hornlczi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmqmwsa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfbeiev.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2trkpchuw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hluabzxp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyuxqpm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2grsdzoeq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zyehmbid.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mouaxgxg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yozfcdgp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dodfnoah.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjkjxma.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnouacde.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdifoslj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ucttxbwg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2autvpiqd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbxwfcy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fojlqmwc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujskhdha.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2twtykdkd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpfcdzg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amymuhom.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhqfbur.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvxxqfe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjihxys.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2klyfkpdn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slqbghzd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qpusgpki.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zirchxmh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfbfdqb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szfbppuo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2spzulkmv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scnumtwj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kylbwxbi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxsujtw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyevckd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zizuztuc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpwkbte.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeeodhc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kaubwqxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awwzgzix.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kvypqjlo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trnkhssp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoglbmhu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iykxfoic.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2otzhlmuw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2laelqsif.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmlxekr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zmynmcol.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trkksogl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxjajng.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjniplm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbjhxhp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2usliizvl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxemhlh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhdtugd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieynjfnm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yngtmvlo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lffiwflv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzdfvnb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqsnufa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzzdpyb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjwbjgt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzqxlnr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqxgukl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcdnnqv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxwlbth.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcvijjq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxfcvbq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuqrhbn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2czsizwwt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rclfyezo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ddajzlae.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nomnxrvr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2khqwydcz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2axiildtr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mplmsfkc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epbffsab.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hypmtsxy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgzbcvu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfcgghs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vujlgdzu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2innanylz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fisybifm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nztiuame.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glupwwtr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mekaeiyd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgyoieg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2slzgjzwy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cejevlak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlhzlwu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaytphu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eucldxfw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdomenu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfuczow.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2byiklwit.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ibytlkqc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkklfev.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcsjfsw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfetorrj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwktweat.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwydyfu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aikznnvr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhmkjwe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrqgnry.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtvpqwy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wincvgpc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxlxjhb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwllhqb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjsycna.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ribdmnod.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zazdekqq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdjcxoi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aumcjlpv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2arwkahgj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enrlwrlp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuzicyf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ivporvwn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ofofwaor.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2alizzfyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hijecmga.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeqaqzo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2loxlfifn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyeyopw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2chyjiyaa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmckailt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvjczzy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgdapzo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuogxmeu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfgqakc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvcrfcw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmjykqe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2llggbwhr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyqxffp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqdyikp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2drnboyxn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjslhlc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqydwjz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vuembfov.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2orqbdfvu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpqntpo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnjathi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2miqirotc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyofhie.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqwcjij.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxlcfek.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dniruyzz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbavepy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzcclfz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2szvwrigf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvqxbtt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsebgab.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmktthc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlglgait.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2llnupsge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgxnzia.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mhphrzyk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhyvvrx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oysvsolt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tljflhny.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmfixvn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrftoky.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqexqwcb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzezept.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkdhjmo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hdojpiix.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhowqhtk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvngqicr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2guedrldq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkyhcni.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gkctmcqd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjpbesh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoopbgy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuwcvmn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jahlqqzd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iomazjhz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2euwuocvr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiqwwjx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwniywv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcglfyru.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2skjzhknp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqrnnth.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgkylvr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjijiwv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2traxowei.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrsfvtd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdasiylo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqoebcy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxohgac.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dspmniyn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrnffrc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtthdnvp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2daqqqgwv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnebynrf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zegghndp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njykavgo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxievhfv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dvupklnk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdufeqbj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbfttxf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnhqthp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzdnfsx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzqrcix.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gllyawry.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcyprpu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oazmfhmw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqwbjwb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2byjpkvri.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzxmrbq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2caakcyib.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xalfgbxa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2glojqhdt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2twqwlqnh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwidkmg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2housbiae.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grcooijt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcjndqc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjmihvu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxnngxs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxzuui.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnkbkiw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wftupduj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ophhgkyn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbmfihg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqopxito.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrfuebc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvdzcau.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvtpkgk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2meiwswki.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgszlvj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tboxycxd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lusqluls.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qviilazx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chgvbmfs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dejfrkkb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vicrstjh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvucnnhc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2enlbrumt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwjpuoc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2flyvzrnc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpqfpdz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvvxmnf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhhlbgw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2klyffhbd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoyxpic.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yflcnuqz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wurivpcv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fypgzake.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwqusfr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmhaqqp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcecrxp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmsxwwb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oiazrmgh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcrxfnj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2deygaktu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llrxhgur.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usdngreq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2otmxopot.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfkahga.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgysvimm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmfrmqi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2teutndsy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2inarufft.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xezgbifo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2boztlqjb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nvycwavx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpylnwq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyenmkm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgawblx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjfzmzj.html


<!-- 参考信息 -->