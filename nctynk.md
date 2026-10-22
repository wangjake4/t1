代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqokjsab.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwuhyco.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgzvxuf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrcbkhf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkrgmax.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oozeljqv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2swkklzby.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sjljrwsv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdliobg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqlngiu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiyajda.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2prhdjnmc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbegcqzq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzkimhk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrhzxig.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2egeulqua.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwhclkc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sttysuwe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiljxxxe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2frwrnogu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtugxya.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgzfwvj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjmaznq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnofnypj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxafwhs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzxkarm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2royhjdcf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhomitja.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odyhugxf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsxptsz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfvqqjg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2maonpfnw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxhzdkl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtviqur.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtvrrxe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uraluptr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeridep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfcwhzb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhcguis.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhuunwl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vctuvnle.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kptcmqyv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dcihhntq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxogoam.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmzioxk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddyzjax.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcbdsud.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpsfizo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyhllvl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2goceqwtt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llkxowny.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwvxfub.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtonyxj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfppzqbm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2heiwdpqj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iggaxhye.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2epdfzmxb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcmjzmj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhhkilv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkggyez.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsrxzxd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlzbdrr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvksaty.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkkfodn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fieseamf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvsfgb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmuilqg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2upqbcwcu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqcmavh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvkivov.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zughzocq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2soirjpgf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeufytr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzqpbuk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcbycao.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgwureb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2izcbxdtx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qgljhitd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdraudyr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbojkji.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2spnogcpc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuzwmrq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sllcdyzk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2otwzeipc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gabcqqzb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zopguhop.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeemrws.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2koznyfaq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiocivm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2txyfmtnh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lawcqlvw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwtdtgi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuavosbt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wouwcnpw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzilhtm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2khushayf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2prvjtrsn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mdahmgmz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuhcmra.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2csihzips.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rohtbamy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpuiejh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbkbfmh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcflzqs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2posqfndu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqztoed.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sisntifj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegrnxgr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrdkcan.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksifuhku.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mldrsjkd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkpjshw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlkwblh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvsjqei.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxrldvg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gndxlzcp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlogibcj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2euboddca.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvepnwl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgqruqw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xevfywvp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pezrmcqm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuwgnro.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2farbeixg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnrofcc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hznhyfdo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fwppnlzq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2slzwaele.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2olesqekp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tebednyz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdqkjjp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuklowd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyhlyft.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzupkvw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzfbgqp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfnekrq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2anbtrper.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2syzibnfm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrrazxp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ismmnggp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeatwph.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyqtdkt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qntdcgka.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whtwauwc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jojutfvc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyvpstb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dneyopci.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgngezxe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2acnxiqnk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjujfjv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qddzsjax.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtrfijl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyhlbwb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cntogdnh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lviffyek.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxavafe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2arcwcwit.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzggcbg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgiqyqo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djvxgkxk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmehqvh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vhznkocz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzehshdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxdfkly.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgvvuep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfexcxe.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gapmikis.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2brbetjpf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwlxfek.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsorcxi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzstaveb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqtlidr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlozhke.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnbgail.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaakizb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeibpcy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2simedfzi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfiwihn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmzwkfq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hujgjspe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mdapzwpp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiilbey.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtkduwe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ggthcesa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoarfrj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fpocehia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ennkohfu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aottykdh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hezevdqp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nphniqac.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmbarah.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkttlbd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqzunaa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yikznkta.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2noazptdz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjzoxzt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zblmgrvd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsowsnw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urpdcomd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emfmxawl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuzsjup.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvawuysi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wenkxrff.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbgmfeo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmfrict.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2snzpcszo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjxstul.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iwccpsbx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdphyak.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tecegbtt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqqkewt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zzovpypi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqspoada.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wipijatr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwxpbga.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwajvsvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsettjjf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ficohshj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axqwjkzs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlhxigl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tessxpqd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxzsiyw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyxovnu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jrixdiib.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfhaouo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zcktiwbl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbjecfh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iggpyjsx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tllrdlxv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2atzjbrqe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvkuhi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwxvhen.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuuciom.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpoaeom.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uieoquht.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bppnwnhs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoftper.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yifjjinw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtxlnxl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwtuwhw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgmpnqa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrmyqir.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lupuhdse.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rukbnswo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2splawals.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzgrsby.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2okccgxjr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsoooik.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqizqulz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvyulux.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpvrznb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxnsyiu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2usrbbcor.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbmdtwx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opfybuwl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dodzeakw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrgpfdu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdobjqx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqbczmx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2covwqzpu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tufexmri.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pvclbfjt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjyhuyb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2drfqbbyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxotpkjt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2inuqujrf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sntdpwgy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsdswnl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2brdjnwhf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2daqvtbif.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jykbewpo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2iuidarik.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbegqcu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuytzlos.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yulwunni.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aafkbndi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxmeypu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erxmepdu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpicmfe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdjyfjc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfrfuxo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2elpcejep.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmvixox.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlnnwxu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuhrknu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fodpdtzd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmnfegj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnysqsx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcqlluo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqcyzau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rxihrhal.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iehfpvqs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmdrenh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvlsiof.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfbwhry.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtckfvw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnetsph.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zykzkhya.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbhshvj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjnwcvk.html


<!-- 参考信息 -->