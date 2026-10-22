代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2icfsdgui.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvigytp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwrfdgv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyphgch.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhthmrk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvfttng.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tblryycw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ppexvoad.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2svrqxfxt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bffuccdq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvpjbcn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbuscdl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwmhppc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2utulmkea.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyxviaj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlbiivh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhwxslo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnzorau.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2azhflwom.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2szqywdpk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2romhuoxu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gksysqtq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcemniyd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcuuyin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dggsqssk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2izydjnga.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpqfjtj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcpdboh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wepmyznv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2phinavff.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlvoiub.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yelaiqoi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2allswxgx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjtuzfx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzipzuwe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2goliplep.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsczipr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxldofwj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kroopknz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ermelyrp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2onlnkwvb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxafwtu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjwjxnt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2saxqtmdc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqdwvch.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxbqadp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gexhumwa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsqoift.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oguckcco.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyjmfrr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbkzyrx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhooixbb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnalaqem.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhrrbvw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnktdzet.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkreoot.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gktsyzdf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzuckim.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuhxmlq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xobtqvtj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qicaqtnn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffhpte.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aociddzl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsflwqx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lofeujjd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jidutdvl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpajovda.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwdgubo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pciutnpv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmijzuen.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvyzjpf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkjseea.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xcurcfev.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfyvfps.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkbacng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwpgbzn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oejoscso.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvwefmw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2trxzpuqu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcnheuy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhonrqt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xfacxpyz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqnkzhw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nzelywtt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqvriay.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wcikhdtd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2brmtzusj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kinztijg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvgyefc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsniame.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2quslsqcn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gparshuj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwsjgng.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2umyuxwmw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqbldmo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwnjleq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnayoui.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2spqizxmh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbwsfkn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2souvkrdx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpncsnpy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vllqswgi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgcyxnv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjahkzx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuhvpad.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzahabe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjmidek.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zanlbwgx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwdwjwi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2frfvcpsy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkbfihk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uycyurzn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvbpagp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqktglfl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sahjdrci.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmyglyq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ztitixcu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmgmlrm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfwhccb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2younlfum.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbsundi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2opcpkqil.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhdtxvr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlucqzi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yufewvmc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmbepyg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyqjdno.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqavwrz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtrzjbk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtvxhbk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtpmhbz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2agjxhkvg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zivzzdwp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnawgwo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugupeymf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2acwqqmza.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwppqvp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvomvskq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhkcpzo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aclteetp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2silddlod.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2somusgmj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2abuekklz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dzskzcpq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcosyfq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjwrohi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2utesoknq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mouioxfr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rekzgrpo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcprnyag.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mksgmxbj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2joyccend.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzebzkr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kejkhkpm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zflasigm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yailzoiv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2algfcgzn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwrksnd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvohybf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejawsdwz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lutotlqu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2usnoltmn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toblbfka.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpqtidw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2juulwmnj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajveyjag.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqbeomf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnllrorl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkyjdmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2retfqopj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2melklemp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvpeoph.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2myrtgmaz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iummhgpd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2auvfcgcg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inmyjvqb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nfexbrlm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqclquik.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2whglojct.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ianycrkt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyvhtoc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ultzqunn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqupqwt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmveesvj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzcnjlx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kniuqrmp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kbplvthl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhkavdw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlbwrjh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrvrmpu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qonlamzt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfxrcew.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2telmmwci.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zggfytds.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtegucaa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2faidwqtb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zfleohrj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wedtxwyc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hkayxngt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cupjzofm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdpzlsw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2plpuuxdv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcqovig.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnyqwmo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msnjezrx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhbujex.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyegfre.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofijuwvb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2miuonblm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkuqkkp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xazxmuhj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfjoxqa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qurvbylp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwpbgdm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vehmlqst.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2azjfkquc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2shunvspf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uancuurv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzrorna.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtdcivj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnntrsmy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvejmhqt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvhtzke.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qzewmyud.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwxevvj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhiqzfu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfnhtdm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkpvpbs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbwfblx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tieuyqrx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlcktsd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2radikirm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hupyyfft.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfxcwt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2avgztpou.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbgkhwi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkvlqvt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bmicwkhb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnebyhcg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hdthrxqw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhqysxu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2prvgwoue.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2seoorqkq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuiqvwp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2spvgwcgb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgraeqr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjtmqmh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyhruys.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugxumhg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qljgsiom.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qthfxglv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyjjxhl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jiatojhn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjjtcqq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyvzihb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbnivqg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cczxoilz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2adjpcohx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sevcwrbv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuxqbrd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbdrrcd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbrobng.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcovuat.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjqroqy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbfofc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdqdyzy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mmersaey.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpniyct.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgbypun.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2evrncrjv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pyszhngp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnmvwuz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzvlgfm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxlfvjk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmgdzhq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gihxiayw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fexcqufb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2irqtpvfe.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gichsbuf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjjyvpq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eqanqdwn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcghrjhh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2unnifxpp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aslynwiq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgekiwf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2acbhlfyz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2veldtjib.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdsehke.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoptnml.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2futmzdol.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vppcdgwf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpuquql.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cciobffl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrlfekp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvkldqt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gtanveaq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsbnqsn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxprppkw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hurskyfd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yidflgdp.html


<!-- 参考信息 -->