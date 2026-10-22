代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dggqozjr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2duepjult.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfmcfrs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnshcdwp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbkvuwm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2htgaspel.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jmamfxtk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgnmjpt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eynhmsxj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yynuhjfe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgbjoym.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pusfxmhd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lklwjujl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnsmyfv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2flsiosze.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsvwsyf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqeusiz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhhbffx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlvjcjk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgfwkrq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ichlopbj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ljghqvna.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxizoxvx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvwmmdg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2twzdxihs.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bepkifct.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmmksgo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpbcvja.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsomghtx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbayzap.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2meecfqtq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvekzji.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbpnseq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvsozoq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lslljmzm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdxfgxc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spynmgtk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwvfuyg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2inzejoxn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pycfmaav.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqjayco.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lphdjoai.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpolvlj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvihlsh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxskxdkl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbrtklt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uijixpgz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpwirxn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ivptvxzl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgkeudl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoitwyb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2obzpqcpf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tczsooav.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggprylun.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fipxequy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjgudfq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iclndwhm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgemovw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aptpezan.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrceoow.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeeuzbj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vkblcqdc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrpbqnq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvdbkbx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amnwxscf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jvljwhgs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qklawclu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyikmcc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hullrvpl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2stxhklhu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbvrmns.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xrccsecs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bccbdzwb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxrzocb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wllscxcb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rsivdcfl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2munrmbnu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2axfmscgx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tukkugmm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2krgksbtv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dycvxmfh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2robuuldh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwfeeae.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxfcpsa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2appinknn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwknljai.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqvneke.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njodcffj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2icbcbnje.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmflylia.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pyieyack.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjglsbn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxmsfqr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrxtkcx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmpwvjt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2utruapaf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2inksaplm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fczthnsk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvwdixx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2allvgmcq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhgzmyr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2waljoiry.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2emywoxfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pplehnvn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkbkfvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgtwwxk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2exfwxbam.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqytbnb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmzfxeo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxggnoky.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2decipgxc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyptmknb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2svhucgmy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtmqivt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqndrzt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2egeqafke.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbpvbtr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwmsgye.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujumfqv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btqcofrx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eujbfhmz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jixthxrt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfuylqb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nfytjrsx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qehmxfka.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2punrttjz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ztixftuh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyfvthp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jabvmxuw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwqpyam.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yffinusc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvmvoni.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjpgdyd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtgbqmt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsrafdf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjpgyxm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvbbvrg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vztelvpj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiivmmv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqregfd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rackuxvr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrfgbpl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwcqrys.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2domupdgq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awhidswe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qihzvjrl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgluaoyf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2llbyrbub.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbswyflq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxugyzs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slemrhon.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yasywwtn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgpqixq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2osuuaslx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxxqlvt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyqzhgi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlibuxn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmkuech.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxcfjaw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2npghbgfe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwmkafq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhmokuq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qejzzkay.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxywgza.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkewlwx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbkffzn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzzztzy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjewtlz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoxqveq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgfojwr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdizvrs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhxobcc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbacxch.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfqkpgo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guybbouq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wrthygmj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqutfva.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpgvcpe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nevavafc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2leqfpnmr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2neiybwti.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdruspby.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxrgdwd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtppzla.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaczime.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqcrhbv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2suorqwnq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dkobjtbm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2crcukows.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvemljp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgnxszj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkthrjz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqxyidc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhkpros.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afnwpupr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyvgcgc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uynffcoe.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfvomhr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxcfvlj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2osuzrtft.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxdfqdz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjdrpzf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyhaimv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nskqgxaz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhzjwza.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhpupxb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucstwuws.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzxpawd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2quyhcaro.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2alqrckvi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnciiohz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2accryihk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhlmmal.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uizycvth.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqsmnhj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2btlpqrfv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqirlaj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umqdfzin.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2defpudvq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvsnkvb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hiozenrk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2krdgeavl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yhofervw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcowgak.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhmigmr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mizngvof.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkrkfwq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dnguwaut.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbjwhyp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fmegbfxz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjxvufq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2shqeyeah.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2glbwuaxq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqvjlem.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2okiswskc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ihidbvil.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2laojfkce.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2npgpaopc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljmtjqm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbfevcj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2sjakrivm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcverrb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoslkws.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdlbgjy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnydhhf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdejvvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pziyvswj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyfxmib.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjolbck.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ecififwf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmkekim.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jobktavs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhujlmm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2puadjxpw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgmzjmf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2auzrgzos.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmrtbhp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mdehshra.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oanuuxfq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhlvjqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuynpqjb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdigohc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rkredqmq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkytebd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bewmecdx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwhtsia.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdkitis.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiofkyo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lratpdwe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2akfmlrbm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2azsreilr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyindcxw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeeetjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aixtzaum.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhymbdsh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpablem.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wegxbjuv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvnykws.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kilyghoj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mykjlael.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2afvokova.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ewljzumf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrhqmao.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpmrpol.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcudobb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ysetdmql.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrinxes.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xzldmaeh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvtymei.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjbjyyh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfsepxm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mporylcv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2trdrortn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhijvqz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlgkxoa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qefezoxr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfixqscz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxvmeij.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgohwtg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbmjizq.html


<!-- 参考信息 -->