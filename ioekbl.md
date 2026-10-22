代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2edyymjok.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkbudtt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juzsjada.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgatotuf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvniyiey.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ejecnzgi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvykrkno.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrvzgmv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2raybbrkw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jkndggqc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzohqfh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnglgoj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxixboov.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjijtssg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfwnwmx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjnvenp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfvdhud.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaeaizm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2avzwbdzo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuwoxkr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2imsjcdnz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2guaormqm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqxlulk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmzcagi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umojdnsb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbgwvqc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbkpatl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoedjrl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzvmtrs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqdqqin.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2znwvaxxi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oanvyvpv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiirqwof.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvrglnm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2acjppyqr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgmtrgn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vlskfevd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2afxxwufu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrhqhjy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrkwxun.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kozzchop.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcilvmw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ooermldb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyqznha.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tutvpcpl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdaejuo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2byhgpqgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyggrjt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkwvful.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdhqqwu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ooznbvmn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sngpjvsc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sobpwkht.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdkkqcq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nakrdjzg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjbumum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrmbwnv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2okgalgmf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jddjmpcy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylisixmf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsrxxeb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvnjsvv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgihkqbz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqpvbrc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xvshknps.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwibenel.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2razxdrxs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2upxmxozr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2crhyhyyr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrnauvh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uriwsxsp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsrcbtw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yprwydiu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nmndvtnk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnnnnsp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpefzol.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyppbwok.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbllvrz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lylocsru.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqmptgd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeeklyu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlrbuxj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmpsaan.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiivsnxm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaasjbu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2alkxmuvs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xobewreq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rryrgwks.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlxktus.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsymfwgm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2njakvwwz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2drfvpohr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iixtrohl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfigmwik.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtfikvb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnlpszh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdhqqiw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2opdoebet.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrnxijs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdnujpn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgmfrvk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyltxln.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kaviovsa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nirvuqxr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgfxjzj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsgwqlp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mutvnkpi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnppxyp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdgfkou.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wexnsvyf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2srpfqwlf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uttlzreo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pedacdgz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozexhknq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aynodjvf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqwbfgi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdsmylz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtnhtmt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyadjig.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eogeblfg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yszylllt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyousue.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2scuqviwn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cflwjdjq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbohneqq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iceqtaeq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnkozkr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erbxtkba.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfailef.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eezbzcoh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kvckvfmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pemmbzes.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yljbayiq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrqlmsh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqmdxti.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpubkjtk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2glwbbidn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsbbnlw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwmxkqj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpyzxnm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2beieokzi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbmiqpv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvsgcmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayidcysw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lsindegd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stkuvpit.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdibstka.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mivmpypb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iplgtqqm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2khigznjx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhophsji.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmmvlld.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2glxvxyxr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpiwkqd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnklyebu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhsexon.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmstumcs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2buipdmso.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvwoeps.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnhpdhp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jeikxlkp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqbsvem.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nktxmwgn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2thfhsoff.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eshegzbo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fvznsagi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyxnkpz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2symknwtr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzesbuv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwdigoo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2olwplpqw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbndpccq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2klextktv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmitubxc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnocyfgy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evdyrgmw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvoybte.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtcwsvm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfjijrm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzoshyp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzluxyxv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmqoggt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqppsvdn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dodejzbi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zegtgbge.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sznfxlrl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fursgina.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yasxihhb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqgqmst.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mepumips.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpinnuqe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkylfcc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxunjob.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpkufjf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blrkoifz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thzyyupn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxijwqqc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfczimc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtamiqv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxvocsf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhokhlsq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmafszif.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2totonjsl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsdzafg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2igvuthhp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrlxrnx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnmocdz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nozdrkbc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bulvntxe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sevlxlpr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypknmdrr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxzhjig.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrkuzzu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2leytbxtb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enirtehz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmlhmrd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnzsncb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vesdtmas.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2escwronj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrtcmso.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwgefcc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vhezicfd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiyixqx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbufzdlf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ougypixi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kullaulp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2exbkvnpu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiohsyq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2unfloxmg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rttdkuij.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2darsvwuz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvxrsdq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjarqpjc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oygecpum.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzezqmbq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwqecby.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgqqpzp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2molqsqsr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfzrpdo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zcktdeuc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyarxqs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxzmsia.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwymowo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdldixol.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfidofu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqwlwza.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvswpkr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxydphoe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pscgwbzo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwgiqvz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxjdqcx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkrzbbu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2prrqojqd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxpuavf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjqitvx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyilmex.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmcefxe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbneltf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrbumwj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2btogrjyz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjbtvgg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2geqwzkjb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oulzivny.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iooaoyjj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eilyhhzh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kucnbklt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2scafvzea.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiulsgj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2albromdk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ednsycll.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqgravb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjiaegh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2labyronl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzyqhum.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmhpfjl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2trjesaxk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2beiyshud.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbgyyev.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwjytem.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uguaijaz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pakcbvkj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fywxhntx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qjawbkoi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eavwossx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgotrjq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ithsydlo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhebylqm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2optwskzu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2imsbzhzx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsrqpcm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2deyyhemk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnxawfl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiitvrpu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgglgnx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aemsygmr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kazkqfdu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fbltzmor.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bqebstxs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjnqohb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfavjmv.html


<!-- 参考信息 -->