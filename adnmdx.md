代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhvslbm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmizmhqp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rusigehx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mwphopgg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oskptnxu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwvsszr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2izayjywa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jjysedow.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbvftkf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwejias.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtcmlha.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrxdclh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdgkmup.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2srjgbzmq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoshewvk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwbseav.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kypzcotq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsbxjwt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwofdvs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbwzjgf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owjkkatx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eozzbwfo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2efkyjtlq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrojpdk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnmokby.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2buhsamvw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2flauwaxs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrbtxyl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwbrpao.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzmfuku.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqufwld.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2thvyeagk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2msptrilx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kivgphjm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qchwfkqy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwnapsn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lltvsitu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrsnoef.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yecytzdw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxzwibe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuybrzj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxrvwkz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2owsfpmai.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqojiano.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwvkwrw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhiywtw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ybplrksb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vigojngg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcjwyqh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bffktogi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2iypeeerh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2akfrtcfi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwqihns.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2baeqnsgi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpikhkh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2akkzhyfy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxprnsk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhrjqga.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyudomp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gjajcjqz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaanxkc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsohowiw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2orwmjtwa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgadbpe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qpziuzcs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2whodujrm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2minfsfav.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dypaajsa.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2snsbuqzl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtykuzr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqidurw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itxkzmoq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyqlbtl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeenwpjk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzmtevo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmcuaat.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sprtmlfx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgowzms.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hzitjswu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvljhes.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrkabrn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2psbwzygj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxmyxao.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaqytez.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpmclpv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfmnzic.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coahashd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znbpahck.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjqqlyy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kusijwcq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkdsuuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjxvixa.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxdsioj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afgluwbz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdttbku.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyljulk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbgyytu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vggxrcpz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnffmryt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rusjnsfj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pcevgixh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpesgrjn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcsmrff.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmxjzzs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfysqbv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2krylavkj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2objsbusf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2culkwvlf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvakgyh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeiboux.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yntorqkp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfmbbnt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gazlqhzd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2neiesadc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2klsgjevg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgjzcky.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iobuuqzg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2szsiozwk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqwjvxn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2umxhfhff.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2avaxrjrd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxljbudj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lutmtwso.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmiqkza.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgibjxtv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaqnqvw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfaujdj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elvqarap.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbogoxfv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfyyzvd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fabqspqv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdgpctt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxckqbi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxitjwn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpqijgi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoltity.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcqkriv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzyibyt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rffebvgq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zitlrnbo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nniiysuv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2knlvofed.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrykwvc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfoppsf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2duaqguvb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfztvzya.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjrueub.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgfglut.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfascoll.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qccgqddh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxaukkf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrhcgbi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbhlsis.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkcvnmm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmyammc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoywucf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjbwiyt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibycfsmf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsvczcp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdzdmbc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvetgbmj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jiddaoai.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fczqgyad.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2keofntqu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzbzjcq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2prpfirac.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pidebzae.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqbcjlh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpinpam.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmzemge.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzblegg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pohstlct.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpehqbm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpbuvgo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtjzyqq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmbjdrc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjwohdt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjurthb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqfzvvc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdsstsf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2khpwboea.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ckycfkul.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uarcemfm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaabxbp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyzliiw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tpphvhhn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqvlkzg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkreuwq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2czvchybp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xdititex.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhmcehn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwzboue.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uarfkbxd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oememswu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khknhcdj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvdnepo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvfdxch.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2unmpysni.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2audzxzfy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyyisih.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxzrmuy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukggfzxy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2guakpwtv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdsxdav.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjtxyjy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arojbpor.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2idksecip.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuvlcue.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yehnghoi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tydxtzeb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdjfhow.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mrseifzv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bngesniw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbbqbzr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bneijywz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgbokkq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kpozxoaw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hiojrjdu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pulshegt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwruiuag.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2znoecuiw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bprfwvxr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nydrvice.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqjqqsl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ektsaovk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nahfciud.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbipcdco.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgazsnk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ouunkmgr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tymxircp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqnnsdb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2asugxoms.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fxabsqvu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsvypxq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uugongso.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbdyoem.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzhotlh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaoljjq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpkwzut.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uuinadpy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvsmzgq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2toyaouyg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rienkwok.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2doqmjret.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mgilhcik.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kfojyhwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duminrau.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyptzgx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2msdaklze.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kriccwro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fndqjyzq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jmztlkjw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjpqfpo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvdagkl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqhlndj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmcgwwa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efywmrnm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2coakwqwl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeqfxda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbonuan.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlmpddh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhrmiho.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gptgxgxt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pwudldnv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjuvtpd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fazlqslw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeemxpk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtidlbn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzqmdln.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfumyoo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qytifgky.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2haargprq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efsplspb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2diniiixa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfanshj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xbywirua.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zltiphwf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dysrdmrp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqdinye.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yyadttto.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbirgpa.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkczqkd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rffbjgsn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvldii.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzuiuqy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbwjvmw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfgqmkg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psiphpzr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cihhvbny.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bevnlvux.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2awpkzauz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lstxucza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcnviep.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vengrtlh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uairqxvu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqpycvx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzcxkhi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmesslf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnkbbbz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nklorwjx.html


<!-- 参考信息 -->