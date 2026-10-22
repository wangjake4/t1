代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsmgivb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxjslnb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiclnxy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqdeujd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcoxfzg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2owlpxqud.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwkkufg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vwquqlos.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kckuledi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkviwnca.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbotsdk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iweoqdez.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ksphvzft.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvhwusa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvdrklf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upfiyyjh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uedsmchy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgtmuwd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zneurczg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2teaxnvzk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbwidri.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpojayb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lanhtbwy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtmqfnd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuuqrlg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvdpeib.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgosqpz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uczrrhzn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hybwcosj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnbwdpa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhaiczq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esuarcle.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jxihyxgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwusbwxy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxtfikd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcvvywf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbgjucq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cigjscgd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbotypp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abzkiypf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2adqsstjc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxmuypq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlphshe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jixirdts.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoxphck.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rqipgpdq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwbpgdd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrbyzna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvqobus.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2luqzqpde.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nlezmhhe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyyzwnu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rdncmiit.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nuekfxts.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgxcyag.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtrnpid.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oekeiila.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmckiuc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vchfcwas.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrqkqzp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kewrowte.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egywqdos.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2asjpvucd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ietxbtzv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgjxcui.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfubzvj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkjcrtb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2powzjtfh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egwqchrz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyfywrc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzbtdqm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bilibagz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbtftqh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqrvpmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fknuzfiv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzlhwir.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfuysef.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwptwaqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmepfkb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bocluvti.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emfdpfjh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrcdeaf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmsuilt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoobftg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoztour.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tysaeqwq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awkqicuc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zglsfubc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgutesx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrrhswh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iidzwtwt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrfcrkv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fclmmapx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwuhzsj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mljodfwr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkcexub.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ektpfopi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tppwvicp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jniqivlk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sailcwii.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnusvvys.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2smjzgugs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tynfzalf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fscaqdab.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2upsvzdcz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oystkwaz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvlcgxa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bksrnleu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlzmicb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xyogfprt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hutqazjv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvmynzb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytktrhoa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xclgaxqm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oobkojxp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2avhxuyam.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hybyyfwe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zourbucw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdlwvdi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlaosry.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sppqpbxu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsedoum.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gphnxkli.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edzdefvt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2izkxmwkq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsmqtix.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nomfxlpl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gjutnodo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtuhdvt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2etefqmfn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrhvvmd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrzkxjm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qorxzaut.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwbsprb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enkefhey.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocikmrxj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2flyzprpg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsjbmpf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rdriyeyq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoptauc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uknrohlq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iakvbgog.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqkhvoz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2enuoghky.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2coomkddb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvosquxy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2suhxdxsi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjdakjl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjkimfa.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqjhqnq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2prtvuxli.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdsfwvx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrnfsme.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umyjnfqw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2prcndiwf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbejbwf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdaqnxn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbwvbzz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkmcuuq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpgoasj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kmojqqxx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlziysl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2baathhhm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqvgyhd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bakcnfwi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdmjedi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqsaolh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2trhmyhet.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xnynnlby.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyqnheh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgugpbq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uururxjf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tibomcrr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2chbvqxuf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsbdjqb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ligcffmx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xddoxqtt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aspqtdry.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kauojxjr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jxemdkgm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfbxwhi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlnbzrt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sejqrgcl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuslzzw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxnopdv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbryziy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjxtbwj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrcfobv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2auvqnqvd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpfhkum.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrgkcap.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkahkhd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2baadqtsw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdhbvvo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhzemih.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtawtts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwapatt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bupsiidc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2npuljyvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsidair.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjwzixt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwytglos.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgmhefi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgglrsy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpucqbqe.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jndnjzfe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sulnfvwt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyuqazd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ockmfsda.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ygclrcnr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dppiuykg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2apqvzxhz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoppeau.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zswkjaok.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdykaaf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vchrjgdo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2csczrcby.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuqyjds.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfqoylz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwuxsqw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mtalohtr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2azknmgam.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhakmixg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyxwalz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2auxtdzwg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvrurhv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeijvls.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzehvroz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2toyaojdq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2opvvndap.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdzrvtm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntofhjoh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjggqdhn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2inferabt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gyabwyji.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzudgrj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqscfwx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgezyfe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2acnmjylp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2okxfdpzz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2govxlajn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2itayplnj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2liziuyec.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dduzmfvz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhfnojg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvifwvi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbozdbq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjacdwe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aygtllab.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cizvlvlv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2krcyjwvz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkyhrlw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qribxtse.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hswrbskt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2auddmfjm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnajykt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtjjhyc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoskkyag.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnqqmmy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lahnqgoo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlztano.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rndijaqn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnzpwyl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpiyfen.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vsumkzoh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeqvmbo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgplgpw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2austmhjo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bvktnimr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ammmdlou.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwhaxyx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvqoxpe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsgrmnu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixfdbwa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxtdlcu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rftbiljx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2izedtwkb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fngptbgd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2anfcgmul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzerqtda.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2whksprok.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzqxyii.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsquqpw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zijxuxok.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srblqomb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cadhsksi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cypcgasy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwwtmcj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qunspjfy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlklohcr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyhqert.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2quorelln.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pulqirag.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnescvoo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqykyvh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaesuin.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2flushswi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvdgttl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lawkjbko.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqmjwbp.html


<!-- 参考信息 -->