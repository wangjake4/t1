代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kflsjoee.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nunpjlsz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yfimygtx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhwrwgv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uleuofaq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dugeopif.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrycfyw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqdzjlm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mckkpbti.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mhctkynq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2olszpyru.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uqezndvf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2faalguik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2moaetuyi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lefdxjsa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2snmaauic.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yocyxamq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvwtjwa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eifacres.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dpciequy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjcjluu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efbeljdj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyrsnhs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgdjeer.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ofazbnpj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hinganco.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pelecwew.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpictty.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dlacbwbb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtweefya.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zwktlvxa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlsekti.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2woddkovl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2squayfzt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhwchav.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2utnloige.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnmroau.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2govgmion.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxuqhjl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhprnuk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2beidgacb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwesumhi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2romhqiof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmdpfag.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2owmaovgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kinmafor.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nylidohc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2axxgxbot.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpusays.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlvjbjr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2entaskmr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hitqvwlf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lhucvxrl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfztzqbi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqkqffr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2npgxlkst.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqphicw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmxpiya.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krppuibc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jovujwzk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyjilug.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgzxpqz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cxepxlge.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlkpquj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2twchbady.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pqicoqnb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2botludis.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ejovloaa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyoquly.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aojlfmbl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2irzzprkh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkxkwqk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqdjcpj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btxmmcfm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfycpyb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbnsrnl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmhzmrm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiplusc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cklsdwvg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axkwlcqu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aqekwhti.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvowdfo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhaxkvo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2awlmdrwi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sthpfvja.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgsyzfq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vekqmgob.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hpobgoeq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vucyjfrq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhisqxdy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlkuuvy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gffrssta.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjcrbqb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qduibvmt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdmufgp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zronyver.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aarnzcss.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdzwtss.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdokhivo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvbgzip.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfuhlbj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbomold.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaeujoe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sagcleht.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnpfngm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2igjkbabr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2txnpvalx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fatdscjr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpwvuil.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkbddxw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2odrdnygh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpokcnj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aycipidq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsmgugf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwrccwk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhtixvp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbgxehk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2awwynpgx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcdiong.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbytuzf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uewouxsp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtksmbvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ividspkj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzywbwfq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsilzkir.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkomeqz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkiibbo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyyufpp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2csrpsvsg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gmenmsfg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxyxaqk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuudtst.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cpydqbpa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fofjydsb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcdfbsc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgundteh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrmcmvi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xixijtna.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwqssgr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfovohh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2flzibxcd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wtllddiq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cimqwnqn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eniaftpm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeadkny.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpjijsa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akhwzufn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2osaqwoug.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2crqdxnhf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfgykag.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhsfcjp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mmioxoft.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2oxazgwyc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2azkjyavn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjozoyw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cugxbgog.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzailmi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcijfcf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaawqdi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbakdpp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dgchiuig.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tohkshhy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyqrcxh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nqedecvq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wxefrjqb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxgwkon.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdgjoxg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbncehs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qscuyrix.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdkuniq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ksacskho.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsvjvvr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkqpogi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbatzzvd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2npjhyptm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcpptyl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pahxblye.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppugclkg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmerdnpr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yeogxotv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqggmwh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfgzktd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yliiakze.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xaquitfy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjhsrpo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wstcyiki.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iaavkxmw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfiequ.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsykgbb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wadzency.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2waypznvu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sngddfls.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxmevvq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2phmigfxb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gulxnxfl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvpfmvd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxgxzwd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xuadmfdq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdzoiym.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkvccvu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gudecapr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oguolxuu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaxgaja.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2frxsxtie.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wjakirqm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdfgtji.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byipmoof.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2inmziqqy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvcvjwx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2iunwknle.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nmevjdfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evkczxzt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qitrzhep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wztsnpmz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiffgke.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2szdfzbwe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnujdgc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrowlxw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfpjthj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cglsvqim.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyjuzzy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2biqgolvs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcpggpm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2twkpfitf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmdloxj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzoknxd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqqhish.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dukrxosm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zndfdmqf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2liqtpaen.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2obzqfwcm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2brouxhwb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrgmpka.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpadyeph.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2krnuuqzn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azqrgsvh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvnsqum.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aanpykkt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnibqeag.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esgtzlsy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttauibhr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuettyg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cicbehze.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zubzkoag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2osfxavlo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2urpowtmx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bwotcbwt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrakpob.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kecdzoro.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoteukq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpadhrmq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ensaeijc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cerhezvr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isotnmek.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqklkap.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rsprbgmj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmrrmqc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ihejdxgu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxlxwgx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjajbhj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yftsvelw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2osrbwsda.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmoysxa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwqnwzn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvsesew.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sapnvskr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkydzumb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2emveoloh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqjcsjv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoegbdy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcyoyxh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cydlpubl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdjlxoi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cybuhlll.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gknlmoju.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvjtkxx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzumyvk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcnmswo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxfxqol.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obxtlsuy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2muvnzmxf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgxhgwq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fuohyuzw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcqjhak.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvgjrtl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzakzmr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mnszdyhc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnxessf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2beqslkje.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncylpvtn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlahjtp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfroinip.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdcmftj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhfzhqv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avwpiznj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrqqlic.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yvclvwnj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhgyddh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yaomonrl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyzisvf.html


<!-- 参考信息 -->