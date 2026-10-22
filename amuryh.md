代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuaqgpa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzbxtxd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhhtzyz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxbfgkz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2riadgkff.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgunhwi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2deyufgkr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbouwffx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmjxqhg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfojhpx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyfchbn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2drredvwi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdnyqeh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sghhgkgz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwdmfrs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ludlnlly.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwcijmx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zqexbunn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pezkejnd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgubukj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcejczx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeilsln.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkqahcj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vptnbhuf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvigzxm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuftqgbn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iquujblz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaseiho.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnnxavr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbvbjjq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uufewtzi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgwlwei.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdxifrc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iygxfonu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oobmargq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiuwnrp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfxcrfz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dygbgtsk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxiuwzg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqxrazy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yglmxizn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtxponl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2czbkarbk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fipaukxo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgtnmju.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rklywdja.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghglusod.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlyrmzi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qetxswue.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdotqiri.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkvlqqg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhwmybw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbviamy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2trogplhz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdoplzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbposea.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xbehdeua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwbrhsh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2repmhxgy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvpbzbe.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxgsuwt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fucalsin.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhjhxbp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoigzmx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mcynyfaf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hchkjsad.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzisezl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2whgxruqs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svfkjnfz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtjigve.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeimmnzt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imuuruys.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rysifolt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fyasctsq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2stdvrdch.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iptmeexa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lnznzhbq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrrivoy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcslhtb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2djkayxpl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcxwsaj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2negpfeuu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bktmchbn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjzsrpq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2umkqpyzs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plmvkucr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpplvao.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgrfsvo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvobsvi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsuvgdw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqxitwu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzwdyin.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwvvrfz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdwsang.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yodwbdbo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwwzwrz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eumovzxd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2alcojukt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2seloumyl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ikihbuod.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxstbbt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zecspfuh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jilhbenn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkdapyk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2poqokxxn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dwabdeyy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyralbeh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thrmsxmp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2teacezls.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqbvhwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdfdaov.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jghcqszo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvchkby.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2niolcaya.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bifxbocb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2abkzgvzs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhlskkt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xnetvuwy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tzckbmok.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqipdrcv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ludwconr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjiavkx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdticjp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrzqywn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vclystfq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfihsum.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgawwpv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kddilooa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yptqmnap.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkqjmjh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2clkfyram.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2euknxskw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wquokiee.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2llzadxkq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvzplyb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxvdfvc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnlijhk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kfojitpm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kbixwdlv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2guwksklr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnjpqis.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyfshid.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2azivdgkq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwnwqai.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqbzjpy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2taueaxdg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtprmmz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmowdufp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqcgxod.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mszahfpe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2attnoreb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbfnlxv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lotuftfn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zccfcgxy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtmrxvk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gddkykea.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qeigdiyd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnztfqxc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zloahwrc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egawgehs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhkvjbe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuaoqcv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmytqcj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhdrqry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbqpymo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxvznva.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqedfix.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2thkymyjy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qfotjbfo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjysexrz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yopaviuq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfzlzas.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qffjipdg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hilpxrfr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2stllbjxw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cghywqfu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mkinicqo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibigaisc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfgcedg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zezzqled.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ankoynyf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbmepxf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkqbmls.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxhuyju.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tlznbbzs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxbcekb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyibkqq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcqbzax.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jilojuau.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2npahkcqn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqegyazj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnubgciw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkwsobl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qumjspvj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhenchf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhvwquk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jjphqtvu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzicuxkm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxnjhhl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2otbivvkb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2banuxdsq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qmapdpep.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2khjqplkp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jkisuhps.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oetqmfty.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2eedwnjxq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtcmczq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cddvzwbh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2apqvkrng.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwnqeeg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcjgfvx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiirhvo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmhakgv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcuifdq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfulusl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2axjbzrna.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfhjctp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zazoqepv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqjpliz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjjbrrd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkmjsem.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2grnqfptz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2baahntfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nethzwhg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgpkiuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjffnut.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eaesfnsl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rigcsxph.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oznhwynr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cilvicrs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjqfbmi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2melqegpj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsyogzc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oglcfrlo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2egvmpavs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqbmsdj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2faeadihy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfvmzmr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ajotfqde.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsmkjph.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzznyhk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfaadbo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcvaidl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bemerzxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbtfbmh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyfdyoa.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sskquivk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txuavaes.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlytcxh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxphdvrm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2alghhkzn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toxuoejx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dapopael.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkapzyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2igglrqop.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfniloe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uareidiz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oymmhmhu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dclxrult.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2txfjzafq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dynadxqw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rxesbftz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjudiega.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiudwph.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdezrvbs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2czkpohvc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqzcpmf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gccycvxh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtozvits.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpbddxx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjnboyy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsxnudm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkondoc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpugoxqr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lasreych.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2btnpzize.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzgzrlv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkeicuz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxozuqw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mzomnlxg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdwelqc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkiinqf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzzevma.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuwbniz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2angctwdf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etyujgqp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvkoxfu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rulidcet.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bntfksde.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgygzju.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyvnmzj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sismpaui.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lthwjzlx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iycvmyuz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvsbynd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjstzzq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2iytybsrt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsiltbn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ogygxbxp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqfhdcu.html


<!-- 参考信息 -->