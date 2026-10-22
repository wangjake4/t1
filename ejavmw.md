代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeaqgbc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pczdyuuy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gohhqgnp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2saayeibg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxygfoz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqxxugc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfdypjh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aehlbjjx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrkizxp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tverzmsb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnzlerb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpyeuzr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2meonaihi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxgeehz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imkddqfk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwnpgaf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiaeybr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeoqgra.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlaizdq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gbelwgop.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqotuvrx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkzgdps.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtlzylz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fonpxqyh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqgznsy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrqdqvc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fltjhugo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2frbcxyoq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skuxwcaw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yxikauzn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxdoqfa.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpsnnxg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnezrvno.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hnouczvi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtfjptx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjqgyio.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdvwopi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzepkzzc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hweurbjp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cuicimqj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jvshewnx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhweckgs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqierup.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2znqdelba.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaswsfn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brxycacm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgvmqjk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkjqcix.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwojpmt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsyygaj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pswcjqlz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oguirlqb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2byjdtaww.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygugyjzo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtvjsty.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hkecldxv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbhlmay.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaiyiux.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2weullbig.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2srjshnno.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzkdxrj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfynruo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxhwxav.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbbztvs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdrhxsa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hodeqgpt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2budsrvmb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tttecxse.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmybzgm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wisctokj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdcwbhb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dltniuaa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efhmvayc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjxahay.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wodmngjx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hagddmeg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uaskryxx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2scymfkpq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmyckdr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ulohkbxi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgivnidc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ilftkqkj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2voelqfjm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xdefbkqd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdobxayf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyuqkdi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pctetsnh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vamthycc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fssgguec.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2acazinqg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lexflovv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyispeg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjljaoyl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvdosvl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlbwjyt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zrojhfnh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzwqpzn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zspvjqmo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqboyee.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ybctuppa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyjakjg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fviuoiix.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzcudii.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkleflb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gxobmepj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcbjepq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2thptlebk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwstfqsa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxxxgzt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfnqcs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbinszl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2byjdxkrs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2smjzoioy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jorhroiw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmtfemn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cliaxsxj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvcdpnc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnjbvcy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2flewimvo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2viogjksk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2szmplgai.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2abvacdrx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoclrhp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxhhopl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqshuwx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqozdkc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2essvsxct.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2swqdigyv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeftlzyl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxnluqe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2brglnyqy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnuwhfc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxtvuar.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxiletb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2veaeeuxb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvobjre.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrevtec.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjszyig.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bopmzeig.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ipokvecv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmhbmpv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kchghost.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxfsicc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmneznz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vvttrqjq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujeyjxr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnykeqeh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rippjdwe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pahxgbus.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxgphwr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjdqblm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuubbui.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzzhpmk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2decssqaq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrouwph.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwieawi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2prrpymjy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ckctdgor.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azttgaia.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ledbgqdb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxncdidq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzpbeup.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyirwpqb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hakbssuq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwihfjks.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uudwjpzr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcunpnhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdqztzj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgrwssb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stpbijuu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjchjwq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eukpiqpc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ospvnbjw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxciqguz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2imqqinsa.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nicflznu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nxikcgkt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvahnxvj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynshxplg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfccyyyu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxacvjo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqifkie.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njsrjhnc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peajwznv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxpzttt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfixpthj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjhqpxm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvnzfni.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqiigpk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oaovpyyq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hluboghs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vadolbzk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2taqznzmz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzktdhus.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmqxqhz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpjbgyg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tndvmknn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbumvenu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sydvxiun.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyimflf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jemunbhk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2emdygnrc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsnuzui.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuymakhc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkfgzap.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlbhtuv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdjsdwz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rewaepja.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzpolwh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2danupzbt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agipfldl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqkxmwg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqbhkgy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dagqsnwn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvctruvj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kczkhlii.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cajemvhd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bucgbnte.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kujakttz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iemkumsw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oepswdlf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqreflr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsdgpqz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2houcxgto.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbgtsiv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtszpbhs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbyhspl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2falkaydk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrvtglh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuwziok.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oiheofux.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcqhbnn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdxbcc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2opdvkguc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfvckzb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhowejqv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnczcbnv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oppnrevm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmuuoes.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pikmtzwy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyomtvj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoufmon.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2puilidbe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2stifhjfn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbfmbuq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zswscnoc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkukojy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egeiegtl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlveqkp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2onskkulv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgvlztz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmyblwe.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoiifqc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvylnxg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxomnxo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxvpeka.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dwspiiyf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vngxqksj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmjjsak.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsbqljb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqlhent.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbilmcz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2numbtvyl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rukmjyun.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vxclwult.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcvpnpy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2obxpnmgf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkopehs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxdpfua.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwwsvhv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftptzsni.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnspyflu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2daboosha.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cafjcuhh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jprvhmzc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2akclmgzy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuawaws.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbemzmus.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xposbcvb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvelwdq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtegfki.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2beqwurgm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abqydhlt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2slbdirit.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xteyrcaj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxmacdi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2szhpkcfd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2idmolbtl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ovziwauh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoxkbcw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxmajyx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqsrbzp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfrpwuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2awbcdeko.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2syqgknnk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rowdnagz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnbpcci.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tigoemiw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wurxlnfk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lusmsxld.html


<!-- 参考信息 -->