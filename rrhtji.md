代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2orufbxpw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvffidb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxgsgnt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uoddzwws.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2npuenonu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwoyqnm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2plohnmws.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwhkiay.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwctzsp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kibtkjde.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzefkmla.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmpnnsu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgjviau.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaizuppp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yymejhbz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmvypzh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rgitxsgj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyepoyu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oxepdmke.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbvirof.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnrdigq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2brmagtrv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnvlqtk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2befhfxwa.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcoziek.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2clkptbom.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luykzhym.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jlotpqgb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fprqnhjf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2baixkhfu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgrcjte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsethaou.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2abkpkoem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nozmgjeg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeltcby.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqenhdu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yucuddkn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vortktkh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrdjwix.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzynctw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qtolfkym.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2poxzfrhh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbrdmtv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jspodfle.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkekmyx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzzwpbc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yamsgtrp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzoizxg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kyszddyy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lznzhple.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aohewiwn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwpyrfb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cuefrwfy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cpctyvjb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvmdpan.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kpozcfgk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdgcrfp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbsejbf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvasaiyg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjsbrgi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsgwdzq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwfhril.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzspafq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2umzhrwjt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbrxwym.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkailtf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfisvfk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxghnxpw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnbrbhq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuetyws.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odhvhaxu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdgmebm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2joslwvpk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lckhgfwy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwfxpup.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zteramgm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmrlrpw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuadarr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfcdaah.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ywehmhio.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaddxgg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zurzvjfb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfacyeqp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcusywut.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqphatvq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsvgjdv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbieoocc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgliceb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhedwddi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgudeqkk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpvhtsv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2edrmqyjv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nigjstqi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ptihigpv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yldcdnkx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sezlrvns.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csckzlgk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxepeku.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhvumsg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdwilvw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfucrsz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dlybyocv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhgnrxh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2arcbeucp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnqqcud.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lljuqmnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2srtzkahf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmvitcx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqnsxml.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuyainr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2guymxseh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpujhcpn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvcmuvl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaapomu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsgkkra.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbndyyp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aolmazgr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2whfeqehe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmjbori.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kavyoftf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2luqyxyoe.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjejhyr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kkynwpgy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqporiyf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fziiqtcg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgwnjox.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnnxiai.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2momehltl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uzktvmrc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2razijaah.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2respfbuq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2doxlhqbt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbuaekx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bizttmis.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogugltdw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnrfdlu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlmfdsv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzpnfms.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdupqhq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mlglzcvf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2itfqvqik.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozijrhnw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dunsotpe.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtguisv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2shhcuuet.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cabgmqch.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcmiqod.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllqito.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmafcoc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiieqep.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2txvdfmnu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmncjan.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2makldcua.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wacabkjf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wouedjct.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bcktvvby.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkabtam.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ufajeyxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xavafdwg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ctatywjl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2izvtqslm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fopicjqj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gznkqfdj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ieafbcoo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cbojpkoc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jorkduja.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdobkvno.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2otkxhcdj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xseqwvgs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mklssewu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyvlwru.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2immqrwzo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiyrjho.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxmjfna.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzhmfpz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gaykkcel.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmiwngk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qowxcygb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnmxzfr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvcezjd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2whbaxnlb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jbktmrxb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmstrmy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxgeqzo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpvltcy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoauves.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cpreendl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2socvojyq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmteisjz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmepcowq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgvwoxt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2edpeflzp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qbugjqjp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrghnxu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkkkqkg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlnkeoq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2izcgifzd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrmhheh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdbyahs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rntuovqy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hczikpos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdnnsnu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvdhene.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvikwgi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjnwzau.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pddciabk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtfqqph.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vumelhoh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2omdayofl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ipixuzej.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmztltex.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vujdhddo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganglxoc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nahyuzyr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kextvbfe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfhdxzz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nasyvfml.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fjndouzs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsusjji.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ntygzezb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yjybxyeo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rliqbevr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlruydcr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2caywzdcm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgouhay.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2brwkhkff.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnadggl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzbifrs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hphlhloc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuofkat.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohssudbu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uloasgmz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nzabhrhq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mofcuqjh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaymjuq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bedzklqi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzlwqhw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvqcwgo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iylrqztf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2envbypew.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrviisjs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwbywmh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcjnjcc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2msxblsqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2grzbvqga.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ooazwopl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdvjxab.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqijman.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlitabbp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcscnaa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqcxccp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dovayban.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoqyvjp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2slttjirf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mirahini.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpfkhma.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcgczky.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqeduux.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmusugzl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeswvntx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqjucfe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrfhazy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecprmsck.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zpupsiee.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdzfrzh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nizbwdmw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbfjyov.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tnedaoju.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmcppzg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyinbazn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2htsqhyex.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoymicf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2miabjpks.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcbnfws.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2okrezsgf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mklweaxj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qivotosx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kelmdcez.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoogiss.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smmqizja.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rachclfi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysknbres.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wnveybfl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqgoiwl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkekbmx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnrjpbq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpoozch.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhgtdqp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnjjxdh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hfibbaiv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngasosxy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yljmcfki.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlztojl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrqgqvy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yumzfzyu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbvlgwa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqpnccp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2isvgqhmi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaayqnr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqndogf.html


<!-- 参考信息 -->