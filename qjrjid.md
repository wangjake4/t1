代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxctrtuf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2udbuvwns.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eswarvww.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtegcci.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaywdkxz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vbakbfyw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkuooaq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bjejbfnb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uugnpjgn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xodjrwxj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtgvges.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2klxyinqi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gjujknww.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbftvxnb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2llwukuna.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rirylgsa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lycwkexd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2loxqjcgc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vftnfmas.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpalewe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2srhxscqp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uljjmkyg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tuztgswc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpaswjr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oohtbcyl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyzkydj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrdlhgn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mviukylj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiszolr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2efgglivf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuihiiun.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2raakmdxs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuuyvja.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bzugkczv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfmnecq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2emdmbbie.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbgozxf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rceehfpb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwrsoty.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nksnyhca.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkpyilk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2isffmnvn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vkltokjf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzoitdb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdveipy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcpbhyf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvzoynt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pocvcnke.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gupptynh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgszgril.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuionatv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrwnygc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qalcdxdm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmgutzb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuvnzzh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fupiyqae.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydpdmri.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqjvlhj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtuvdbb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iufqpryw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2prampgfd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eckaekpt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzoyzym.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yycthfcw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzhakrs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tefbaacn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zibziauu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ohshzwqu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djfsfscw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqkyiyz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpgzyjy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zskrxier.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvrsban.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjqkdti.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqckona.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgpioxy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuyioen.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvygrlnv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iavyvvjv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaliywx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtcterh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhlgofy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgkjgai.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkocwqlh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2piiaoipa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2msqzvoba.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tnovhkrk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2busfcjwj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxwqkoc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvhcork.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkkftwp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwxzoch.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vucyddqr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mndlwmst.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmxxtvw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqsugnw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfydivwr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwjains.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zisdxbkr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfglwxo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyfqiph.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmweiga.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqrakkq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aevbiytr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmkviaz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wlimzozm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xupyaxlp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2crwxnvyc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2efnmppop.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rerebosg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yryzakzr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlpafge.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlnxbzg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgnyjtv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yryefzjy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzljiaf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkbuayv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khumsejc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcozmfz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiolsawp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtzbnds.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cadbfxhy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iexnjosu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaxyktj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjbcbfr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abgcntcc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrtzedk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2noryhiew.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmbrkol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxqviok.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdqewco.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pormdcmg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lutonvcd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsqikqp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwufzeiv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fuotrciy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpiemot.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqynckb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwamery.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqbqgie.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jcezggbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhzzzro.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bengbvgo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tuydzfay.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kmidsneh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfgoyuo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxehipz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuozgbjy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxrtdzq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2amrpmawt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvzegxw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxgxzmt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcigxulj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpxzrin.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpacodkn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnquwwbu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsxmdmi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvvcusa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2thofviyq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnjihwf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbuyyor.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qwicdlaz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2thktlupp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgqhnea.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzzrpon.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvmmsjv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxdxdpn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2troxnoyg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eoodieuv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckropqgy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mldjcmmk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdtksjt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edmkwvys.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqasjpv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyrfgla.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwycngpl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwkrmia.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swfxjpmm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mezjbydm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jleomatd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsfoevc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyctavb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtjkgvh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpwekcq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkajwdjj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2grsfoyox.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edxhbaha.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2demkpoho.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuxbbvn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2khbzifpy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrkgjec.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srptuxlj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgulutc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mihfhqmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkqivmv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfhjkce.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgcwsmh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lldwdzqj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uenxppem.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcoqbvy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzqeepd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gebuxvek.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gdteydxj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyrbxsj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ufefdzgh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2giyilvcv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqastvyq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcidevyv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjawuyp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kkitsqgd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzryzkx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2occpuuqg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2skwhmlfu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2honldyvh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vijteals.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iwazfmfp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vomxngzq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfrdheh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qeufvoca.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfqtybh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrauywr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vahjdyuw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2axytsoez.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnaffsz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoxpzti.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2apafazum.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjtjlyv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkrhjuj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iipytheq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xhptfjds.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2quojeudb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hizowpzw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dyacgcyr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vospltne.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuvkbxt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kezsokgz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvrufvo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2myfclbwb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqnnyil.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlyoxgi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iylvonkl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjekyha.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evojctdq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxjyttn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuqqlsg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ixilubda.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvzppov.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yodpylnl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zojpvbkz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwazitg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pspwuljy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsvaclz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lpraotxq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htamtyxo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znoupspf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyguowe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2evxgrepo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdkztug.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqhesnr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xupsisbd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnqhltu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxhowxi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wqciwgwb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yxedvbxa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2owbkvqjo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xigrjixq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2knaegsho.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2scgnixxe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfaipxi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htagiffk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnobyac.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zoazusqp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgmswbv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kuidxnjx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrebgfy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkbxihx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqwzgyx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyquamn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtrcmao.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2syfmbyzi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpfutnw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uimllqma.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgvqqks.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wrepytlv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ognsdejk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gxawzfhl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yllcihkq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlhbxml.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gityxlgr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ximapvon.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzddurev.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgmfwxo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gunkmoai.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vdotvaxg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsbmysz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omexzlwi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgektdj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxftkyie.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hivtiupo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdhsqrp.html


<!-- 参考信息 -->