代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2phymitgz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvjadof.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kqervyju.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwairlx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvxhfsm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ayefrogs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rokhblpa.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxvneoy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nybxsfpp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2coutltel.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonbkcly.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdakmoi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyxaows.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vboyzuqq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2flsyyrci.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkmjhux.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2epyfluzy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2attweuhu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evhzwpal.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2utysgpkw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzzqmem.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbppbqq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnalefw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2szzfvish.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmusfql.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpcdoac.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yruewonp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yognilmr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmqfkdq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwjdrjh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pffzwhvy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2obwwsbvc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlotulfr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxhicap.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryglcdvl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbixtbh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kntfkgrq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pafcblvv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjsstvg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwthljz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gztpuebz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crenszmf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tytbjjkz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsbttyy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2siydcoax.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnatesrn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdwdxnx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2egwujwvp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ujguinvw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hknrqnbm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejglelhi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvdjpbz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hctfrvai.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetiheeh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ftisqxni.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnwsgqb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aakblrgz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnloaqdt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpxfolp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pfazplkk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwftyix.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgyvcqn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2prqrhxxl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdxgmfh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2otflkjrm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmzbqrd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eklgmtba.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dnduepsw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cllqvzhs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfazsfeo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmkiejc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqzodtg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uuseksuv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnlmnnb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkivznh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgiawyn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2diwxjrng.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqtfgwx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mudskdba.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoqhlfl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lprzttgm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmagwbvr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2enrwpgtx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2romgzpxw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyghogrr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2taufkatu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2udmkszpg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmnkzqw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkqywwu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2iejvxlkn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsydseb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2srdlnvmk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ehngobhw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2keashpld.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeykwvl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldychlce.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkerejn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrzgnjs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadajzpa.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jhojvkcg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qssiamqp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2feewcbdf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqnxrsn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyxyvof.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsylnmdb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sslqbbus.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2srnvgwvv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gltvnbzr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzdhhgq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uypiupmp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pyraenrc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2forwpxhv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ldacjroi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlpogud.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qneulzsa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgstcaq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhdhqyu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhafxio.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2edqytzdo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fufythek.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nelbyava.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirrxjmu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ubskyuqx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2olwmsmjd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgziwnuc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsgxggy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jodquxeh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpytlfg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmahpkxa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dspqmrtf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwqhnrk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dnobrjht.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaoscwx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cucbmrap.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjlzyad.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdjaawn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2spdnugtl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmfmapg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtmlqae.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yyytwyxt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcjcgxx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdgupyy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fouprjzx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2etvpnedn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2khacentf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uelpmtif.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpxunoy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2veyrirhx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fumvmgyq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfdaefb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbpmdsl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rduhrdcr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwumfkf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmsnviz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2puoozzoq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arrztpky.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqakyql.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfvlrbr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbjaauq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2powvrors.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwclgoy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fjepsvsw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efzxenwh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcklyyn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhdirfj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gifwoxss.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbzkdrw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2chsiahup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2crlnhvej.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzsqliu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uapndzei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aejihllj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yaupsrfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvwlkzk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2joqxnfbz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjxkozs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kolpgwfy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeqbgec.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2irkvnhcz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jykeqrfu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rukyecgo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmpcxxl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2duetohrk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmpztqr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yufjxorz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wnurvjkx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeurpkm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqddbbcn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tybygzhh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2numbdmuf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ijevyjwl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xovfwnue.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wghfzucg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjlusfn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrxnrey.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2foaasjzg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjoxvjt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2scsheurl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2esbnwuls.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbphkfs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2spvonrkv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2capovdyo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdekrts.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yoihvceo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqtfwdb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aoermjus.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdukvjp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqyaeli.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdaphux.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzsadbg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwvjcjb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2efneakcx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awbcsfot.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2trnjxuoe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzfkidi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtggszhp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjdsxil.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pckykcnp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egldonxf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2swsscdap.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgwcacy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwscisn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2taagaimm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfkeovv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnstqyn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrnlecj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2auzgashq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqqlbuz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxlyjwi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpodvnag.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjbdnmh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2abfplimg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuldvif.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtxndpv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgqxrah.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkjwhex.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhrdkmx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoltdcg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbpmboy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvjaout.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpuanve.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hoereusp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzrhury.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2huxgmkgy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2oxetdsff.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2chyavpva.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnnxthq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2swnngmzm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2apjfmjfq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qubfaiij.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tbehvuhs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogatxdef.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgfgyyd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2edaphzog.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgkrzzl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kckfomrp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxpudxs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyodpzv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bpofmzop.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mthembah.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuukmmt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxiwrjv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dstrjfav.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzpxtft.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdvinde.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrrzhvb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dorofele.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmydtrk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrqfkke.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnjngvm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlldaub.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yavhmswr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yovijjkq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pegdzujx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htvnqfbc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2recmvgmp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpvfkuz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2anotznsm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oeozalzt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wijirsfa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cjssxmwq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zajjkiyo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pydjaroe.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuzjvyl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xhttubpo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsywfljt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2selecfvc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xekqsprh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2byeojixv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnhhzkb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ceshwcbe.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdhsfpl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrpyizj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgogkni.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiajfli.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxnnwje.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmqxnsp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpueejn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsvsedf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xuorteyk.html


<!-- 参考信息 -->