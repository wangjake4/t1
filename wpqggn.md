代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sadwzskf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ocauaqri.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxhlkyd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsnnjtw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfhkbsk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcshbxg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fliccxxi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2htymvkfd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drvuwshf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjsnkia.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eabjbmbg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpqhmso.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lksdhndk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lpovbgto.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2addvwybp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmzzlst.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2awmhbiwj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuenruk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkedokwj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfdhmzj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpilxrxs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtrstha.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mczicsqi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrtoobr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccatiels.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqpyzna.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etaeqaon.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kvybttmo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vaafvrpy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zylhmsgc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvnexhs.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2klqvmhej.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juylrzki.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfzuewy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rieiqzrf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbmqmol.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mowdldad.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tihyrukq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fladbnza.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbegqqz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzgtnis.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjprnijy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbifqpal.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfoghdg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zngzcxzj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjljhqtw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2abkwjxiv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jahctffe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkvwcxn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pddxudcb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2amerybja.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2utucgoof.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjgobsl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aglcbfut.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfswuqys.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shpukqep.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2arpjackj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsiwjrn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugixvkod.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2umblugjo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxcwasu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvijcjw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2muoivogv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cbltjtyt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvhjgou.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uoltvfsx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dguitfgd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ystwucyz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wbilwmmj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lclsxqps.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vyohmcmb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2obexzecy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmxmlgp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uewmxcus.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgmswyr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqerbamm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hihitkgy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjrjfnr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rezsfdnp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfisubm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hywxbzli.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxxuyxr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvlewg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2civqvlzl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqizvkbc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wnceugwk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmswenc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwqtcqc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdvzfwu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mijutwlu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbulvwr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2epsvgeco.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cckbnslu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdrvcnh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcrnrrs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nstyeubf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqitzmt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjbbzqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqroqmg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyznjpy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsasdfn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrdxdbz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yutqslwn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpdhdcm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxclsxxk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcokpdm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbavxfv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnivrosx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyltisv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwatyja.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hqglbbsc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pynwfbqv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pazrodks.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cniywquz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tuihnmhn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rixtdlwl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpmtnan.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zevtaoew.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2chdsqnuo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oulxvzjj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iylpqdof.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckieorwx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ircogtbu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2badhiday.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2caylaxzc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ygywyrol.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixawltwr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eapbanlm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjfixfp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tmatyycm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqbsmzs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tstgqruh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrmbnul.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaxvifs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnbzewj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kavcdtya.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zllwkfyf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xomjegcp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2csuwhvjm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwontcx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcxfvdu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqsvwye.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvurulh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2npicjilj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2srjbnblp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2axhaowfo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeavuci.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2owkimffb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zraibrdm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xafgfwzo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2irfkxcnh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxekibke.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hanqnyfq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqswalb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vswvmskq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjobdkcz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmbfuwi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdysbebf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxxjuuf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yttvypkp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvdsuho.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqlnpup.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvapiknj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrvucji.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uklqelpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rowfnznb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhepqpq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuqwsto.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aertqlho.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjztrfy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymocbubh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsobins.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjfoslv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sskllhrn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmashkuw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ramhcacx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhjqcty.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2enuvvhhh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyfkqnu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmluqyqk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uklanrlz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icsvwnxa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvkalcg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrqllup.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtdfyiq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2afbdcofg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqbsgcs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geiubtpv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2biboxbti.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2usfjqpjm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2knlhpzst.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwepusb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oelpoxfq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqjzoub.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxezdba.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtywnpj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2buhlkndb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2asbfupps.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2okjgigve.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wampimuq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxqaomb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vppaqnsh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvfkusw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrgsupd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rerbajho.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sooaryml.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgszqyw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnftymnu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avzudnwj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2glkcukky.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwahpky.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nouymymj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezchwhgb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkhijxc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvzbgve.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aabyrayr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqympowb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxgsqbk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bscwoczj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcecedva.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epvllwsv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzucubdz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2viwxhxip.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qishaqpd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ssskzpwv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ziihdigb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmukqdj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtkspfl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbibvew.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozanqigl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwqrvvl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ucltxxcn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lejukqkr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrmfhjh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2osyswcti.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flujzyza.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoojjss.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtgqjqe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuzkdos.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egdyxgvj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvyevig.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaseubi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgxotkv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwdhikz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dnobaoeu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2woggathk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zkigxrir.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tjegdqsm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ippsrxlu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zszxcxhf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwzlayu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgarrmik.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzmtujz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2arzzrugk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sabqgljm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyzlwhv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lshhpfuw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tbntpfcd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkudvfb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2voqakejc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtfepzr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2idzukbkj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjywumh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvhxzwr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqyvbyl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2axfofanq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwzenpp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkjdurm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ybthrcjh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nmndflrp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dnetvrlb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqomfff.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwaipvc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdrlllq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnzrcvs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2daizepor.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmshkwz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkizsrk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yarazabq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvezvfl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbdtvhn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjlvpou.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvkqigx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mehxipsf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nhroplwe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsjyjun.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaujezn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uncgcfld.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cafvjqiv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mapploiz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyoclgj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yptqxquy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzmsixs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neodrpbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2twiiatal.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqrxyyo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iqktuhjm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2asgivefe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2swvmwnlx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2igcgqtxf.html


<!-- 参考信息 -->