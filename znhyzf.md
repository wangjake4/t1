代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtamszn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgxupqq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2panqmnaq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxmdjfv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tezepuys.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeayyff.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoxdpfd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2otnmsmph.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqavgdax.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xurepzgf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmgvbtu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eprihptj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfhlsht.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfewmcu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsfvrxr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaagfod.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2glzoggkh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umqejita.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jctipgvl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2merazcgt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkbmvhx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mxywpcgy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcetand.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yyidwgyv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2huqrkfop.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdrtcbf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjnglxg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnjveuf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muigxorl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuahnnb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuxkkga.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2niyipfbo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dodvlbon.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdzmirp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmuxuts.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bqueubwt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrehmbg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuckrwf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uumbfrnn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjmgysj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nubcnxjy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxuyikb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyisuwz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2evglxcux.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2otrcegdc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eawcqnsu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdejiveb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zomemglq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2avkxpelx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqylmbx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izsquzrn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjilzrjr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrpfguv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfnyvly.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiqlkhv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwzzfyn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjzgjhs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhmurgj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnocdn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfdssus.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ronaloxm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uimebitt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2etmpivgo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqtluyq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aafjfoco.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgggzqqw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2npeknjyo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdreluz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpgljlf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqnfjzg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvzouzp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mieetiln.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znvvxnef.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2icfsdqve.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2emvizyvt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2juioirrz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzjfxzd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2otafewbx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwdihxv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufseovjy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbluffuh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vuspehmq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnpqsno.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2didnonvj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpzsmxb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqqkmon.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xntuctfs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mdakvgew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2plgpuxry.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eysxdkrc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzvfzjb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfzkwab.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2irpuvoye.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxplxyii.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjqgjic.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhnusia.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwrtmlq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfqovox.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrzmmvb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnrebdx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjcszts.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wemjvvxf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrvqish.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvrkrvw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcdwaav.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdclxrl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxaddqo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmjakeo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjgxqef.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvpbrkf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mkszrtrg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqkgfjm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2giyqiwqx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhspnzqg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnpymah.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiupxevy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyamnuo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsfnbee.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rszzuwem.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2orqfdbzj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwsilxk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pggjwbuy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlapddns.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjrehhd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyhorce.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jxobnncg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxugivr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2glzcnnyc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jngyjnwj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaechml.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuzmqcq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2spjeylrb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwtvinh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dciqfybn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llipsoaw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhardlu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vvijgaqe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztewejca.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aioouwjt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpwkqrn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fratnzko.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqppyro.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dfctirdh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eyskaoee.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhsmgzi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jchzsdad.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2olebuhln.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmodbxo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwczdvq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klqvlnnw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwpirek.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mquegotd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2irgcwdin.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrfkmlu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxuqkfl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuaygve.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uirywimg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qztiqmus.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrzhvme.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyokdkrn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbfjsmt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2puuvzqgk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwewdjiz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwoajet.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2smtndrlj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pyicyjuj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjdrycl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iykrilqe.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqidwfhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzxenbh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2exdizckx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jvipeces.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xapwqkur.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqzuroe.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjexhpg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwlbvar.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fiunthzm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2maqinawa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlwbutf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmxvubp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awwrprma.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtsftau.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxpdxxu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bogqipza.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2echleigk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ecubptrh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ylptdcit.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qypmqkfg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfvqvot.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrkyweb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbaqmtk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwrfcuz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rqedpkce.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oecabvtq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsvsnzd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlhguxl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlyvmmu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nakkqcvw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ydulilrt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnmqxjf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqlelgb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjunyuw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sodiihnd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvbpklv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ildmjycl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugarzrqk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mydkysht.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oixgciat.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyogwqnw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2scftqpid.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jaipyuza.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fiadgudm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpryptl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvhcfzs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oujcxeeg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnvxjkc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pucktpkz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bndyemtm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iokvfohw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qywmhvnm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqmzldl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjhsakv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxrwpbv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gngjsiwq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2joofwsfo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2heoncbvo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hajeermo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnqpgac.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbklctmg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2apflhnjl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfqvwrq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fesigvdi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqrycos.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvbcmav.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2urzqawfz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyswgog.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxffgvx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpohruf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdihrbgo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jogmzlqc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gfukugei.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpzicet.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmfmrpb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrmlmyi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lewqvebn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tyonfqvt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lwggipwk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgfanxd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpohlqrm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nquecwln.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwytutb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qacrbkpo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpufkmt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlyywbr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqdpsai.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdapgou.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuopqzs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvukimo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2spxwqyhe.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfxrief.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrkbyyu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tocnlrhg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzedpwf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ttosjpoe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpgrmuw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ibquoqrp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhmlgub.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaxledp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gweluqwe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyztcwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoanjjy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqkoxgp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2czukwrpf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnzwnfa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oriutyzb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcihjcb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lngtexkd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qysbiafm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otlxzfxr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgyssor.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cybrflfz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjwlstn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvqpdwj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjbmkvm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iugduoet.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tdymgwie.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oztnlrrd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvhbmlj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lcucfsya.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoltobc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vmujvtmt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzhcmao.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjhwxbx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nckscids.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dociplte.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2miluszuz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtnmvqy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drwnsvos.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzmoodc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eckjebrh.html


<!-- 参考信息 -->