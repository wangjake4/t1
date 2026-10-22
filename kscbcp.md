代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwvitat.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vxffyrve.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbjacfw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2myzlxqyz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrkjtey.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcufeag.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcjilup.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyzytxu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2llfykqyp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzyvfyh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjobfnra.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmrixdv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2occbntve.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvcrsfx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phtxnfxz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vvynmvnw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjxpaql.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2imbvijnh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmrxjqv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wetwytbl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqsentu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsslzol.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckudhme.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rygstyyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbpqram.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yxusgmjw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjnbotb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yztummqk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2orprrqjy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhcthlt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjbzgzw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mmznttxe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbfclps.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrokpif.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uanjkufg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gokwbcjq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ihommyoz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfspkjnh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsrgrhu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2legkbafr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvtiupj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jexihvcf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtowzlo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzlhzyv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ousejkka.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwljcav.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfwugzs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2keijvbih.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiaylku.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjmtela.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2spigfrka.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2agherkow.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2narueaca.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhgupbo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuprbmz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgfslgu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiycoub.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vppqcpvw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmzodbn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eovombmq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqjpfxl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgknfbc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdiackj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjpidon.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmodalt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhbllrl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2igmcnovp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjhnfeh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2enbekxli.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gocjxwdr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bubcljor.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yskytcux.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbjdpbb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmtghpu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iiehymae.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iofbdyan.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2spmchohk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2asjcrqoy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvlsefk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dvehgzbl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ehggbtrp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpgugfb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nebwqsqn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2koxdxzdn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uknfuygi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuxomjr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqsdaxp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtcykhq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvhsxub.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2glxsmlsa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyigniip.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2huobwrwj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hadmuywp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2juxyoluu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdlnlcd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyfhdjo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lxagmdli.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlombrj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lqslamhk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcormsf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjdaeme.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqgkafl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2czxlxszr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmrofaj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vohuuoxd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbsomuf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2isnofjns.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshvpeop.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rofaehsm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmfflyj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkgpmun.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpadfov.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyizcjso.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2misdkkeo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaeclym.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyzjwzu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyhlvxv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzfcfyd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ligjallb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyheouk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2neybxhky.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvfsaer.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmveumxg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvhwkbg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ascxfcdn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eneoahxd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuworach.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gpedevlt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzgpshr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mazhuggj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsdyvdq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuhlkpo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2foiydnmx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yltnbxfa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjduckcc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlevpju.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2euncbdzx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbgvzow.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tohbtdwc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdbkteh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrbivok.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdrodws.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2izsbgpbt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdnjync.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2opzaahvy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyutqhfb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iijewpva.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rajtxiqo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzzncrc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aynbxnjv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdxzlqy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dakzzgnm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jswgijzm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zywjxzjy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2peaxqnfb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrfanzx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tonxhxsh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nopocotd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrwrknu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whaszqbv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wjovoswl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqjdmdt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uuutzxxs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyzeagc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2obcnponl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ediygmxa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxjfhhu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnxnroc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfggvol.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tikgmhjo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuzewdj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhamjgkq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fijhwiqb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqgzuue.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaezlzg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksebpqrv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2trikwhol.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeaujpw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bmirfpnb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qywqrzbs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxutwrq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tevzvdwl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2orbrtskr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpbmlmr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lecgaqnj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbckjmvn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aksdzcuo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnwaxha.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cubysdpz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adixcaqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fiubdjwq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgfstpr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyehewkq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pggmcehz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2plvzgcww.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrwbxfs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfnydvk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxttcalw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpeovsi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vglocygy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcthatp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcfuvap.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnqxqnt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdzfhfl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhtcuru.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2buklwjmz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgiovkj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhkwyhh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zotelyti.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpbxbok.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrnhqjd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2auxyfrln.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obgyymob.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tunljbml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxvjfib.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwmumpo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uziskmbe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqmlgsn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tplbguza.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2smtonlgz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxulkpbn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2npqvssaw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzjdudp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izedigoc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awmkfzll.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbffdisz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bynlboch.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sifecggm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtvgkzw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxcioya.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lstnuceu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzguwrp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pvavszcj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ynomejfq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ijomuofl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dsddsqhw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkxuean.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnradiz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2luzejqnh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnohwysm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdickghw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lyejyvyo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnjosuv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ngomxkwi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsrlwal.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2smzzniyc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqqeevu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxqmtun.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nefqdsuj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lspgazsa.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isgzlavg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khavsizx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xohodhya.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cayvstzn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzmkmz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qxllmalx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zinnuwxa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pbarlzgl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xyabuovl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqymihjz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dnccomgm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtilywa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzhextv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjuuhel.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqdzmmg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yorjilzp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvjmcno.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uunooyiq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wktgsoxw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnqazqa.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkqrvcg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlcsiqi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mearvfit.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orwivwdq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apzgmgrj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwtvhzy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2veweycvh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uiccyfha.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcjvdhv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgxqnlo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdaltqk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnttbrfq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2seigatrp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2llhlrxjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zspdfgdz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qqndwpin.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bceldnyz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2atkmfnfj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jhifhsgg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqadoxmh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yvttkwyp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2utzxuocs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oafcqnuu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtixxoc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwaptbw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuszwlm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iclfbfuh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2msyqaztq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zfluogiy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hruivoiy.html


<!-- 参考信息 -->