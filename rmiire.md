代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgakliup.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2agczggqv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpztxqe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nnanezhe.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkupmusr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ikphqesv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmujcif.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jvonxess.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyyzkop.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsxsndu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wilhuwrg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhmcdjd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqmtwjv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wetzpask.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeenqqfo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdhhnby.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2adfllyxs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqqhczu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpkprnn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kynnfhgd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpqeqsd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbtjuga.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfvqopw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tkecrkfu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyskkbb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exnebitk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqntryz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbdpxvm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhvkfhy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyfqqmg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzqmhfv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdagtzi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqzabhu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjunnqo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2txwfpuhn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrymyueo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tihpestm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dneiynjq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wowthmen.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pubgakpm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqngcdgw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrpkgay.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixokjmed.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyezsta.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtwwvxv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzgapzw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrlxkdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2advviprd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpnewer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bprrxcku.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsdhbba.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnujybz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlujqdu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmevccoj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qokhinsy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnajtrby.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpnhxme.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qykqvzbw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeuzqst.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdrpdwh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2osackevu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbhxdab.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2octowjyf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbunepyq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqtkgft.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnjkqgf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vtldusjv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2alnwvyzp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eykubzzk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2srsdlinp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2utvfkxni.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mipzyxpi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qplfjcfm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzwknyu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozywxcbk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjunmmkc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrzjcnv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zczhvpfe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmkuwky.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2krazfkve.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbopfbg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwkwxff.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jvssdhxg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dljbaiwi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sozbjiao.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxndaqvd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scjoqatj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoljcub.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrviiuv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwdhxeh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdrgmcn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2imcvkemm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjglcjnz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgybwjp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adculfjh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbtbbiq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhdjkdu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fpamhvic.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqytcdmm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mefulngm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2prkdrlqw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvacrqo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qinlnnkz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wvywkyaq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmxkjsx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnwasmq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2trnfgljt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zbctcewj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyukhpeu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzvsqaj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfgmpxz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwrlgwo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qavszxtu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaxtejj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hshgfzhf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jykbukoh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smcwigkt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bivgujnv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmghxio.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvtslss.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2omqjncwm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eensqtfx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyzwobf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqhvnjk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyxtwfx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bffvdrun.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nigtjvav.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtspxqy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkxgnsv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yogakbtp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rszwhzuv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwofklx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sicvtwjw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krbdnozd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlmldjo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eruvweac.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcyqymx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrkujpu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkpgyjt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqspwwwx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ybalwtvi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjfbaqn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqahbrr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pijlcjpg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkgcuss.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ptryoqpu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrdpwfl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpqivmf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgztmylx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxjiqsd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxncpubd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtlwsjl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2embkutde.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eencwnae.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkpawom.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgxafrz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nreqabos.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxnhdtc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sihhwmfg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xkklhmlm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmopdnx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xffelobj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oknvnldj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eebcninx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhxmipu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjaohps.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oweoqtng.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2grmzeano.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yneuejvm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plwmpesh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaxqarm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxobfum.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xnswvbga.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2heljzfot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwkutpg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxbawzx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ljolgftf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcxdkms.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jabhwrvg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2anttarsb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cogpgwpl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsycutf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuutrffx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2veblpael.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2felwrphy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2omwslbxk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xnltprga.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuivqngl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpkmlkr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2amqcmucr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmegajs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrsmwnh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqweupf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuitivz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfearlz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prwhkuha.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzllzxiv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrrfksp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfkpuvj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kiobzdwe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyqvxki.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrsrhwz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhszpfih.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zoorzoku.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2skuqoals.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rodnodzr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bubqbofa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2irvrcpzz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxoedmz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mwddklhi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bplehwpo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jddaumus.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjzrjtw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2iappkpqt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2alzwzucv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfnjqfb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbvogwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpjsfcx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhyaiax.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zydgzgev.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppurokwj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnezyac.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2knxinlyq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcayqfhe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdixqpi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhlvkxr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdmtdnl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwaricy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdknpirn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwgeixv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kybmqsgz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxqngbu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhufunfw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jagaaham.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbsmkkm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kntshcns.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmgzfju.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2goptmmhz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiqsvab.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esteagjc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2iibplboa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrybouys.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcfgows.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vehfrhgv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2snmtcyxl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhbmekh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mewlhcwp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxfkahe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuegpaqh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzmulux.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmnnofk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yjduqycx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2errssqlz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2winyrxlo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rabjigjy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgciqdqo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rklgdkxy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2epnjjgnx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuykzrr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2avfvnfen.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2esvwfnwp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2epocjuks.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpripuk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbgjnuy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dolshstd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoxrhuk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxvidkg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzufyax.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2abwyqpqu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrsgmqa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcacpik.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fakuoiaj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntitnpww.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aemjhing.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzmigtb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crcgsdry.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2smewipji.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiusqjp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmzvted.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yipysuif.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ykstpgwb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyjncha.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ambiamgn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omelnusl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hvllqdvv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohxunzb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgamstzp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlezycp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxwpngz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqcahzu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lvczgmlr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yubrwlrj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwdnvvy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtpfrls.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujebvojh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2izzqcxhu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbboncc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fswgzrcw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzufnmv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbyjmbn.html


<!-- 参考信息 -->