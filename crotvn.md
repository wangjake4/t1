代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hewijurg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjjoxec.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjjtzvh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2csifwgqk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vexprrhb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nycvhvrx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhmrysx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsgbvhy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfsplck.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcvtnrs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhzaavr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqqjstb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mduywezz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2maylxtoy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhrqiip.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbohqol.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvjgfyx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eksqyqmi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqphbjod.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgefrpl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uffdxvyx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdptaas.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2helrotcs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpgqjxh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwfphfv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhiubxp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvkjiry.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ajibcvfv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ledetygt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmowuoor.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpgsiyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2byifkcsz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2faxzslhb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjzsxhz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpwxrea.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2aieazecr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ievdjkyv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ituokany.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcpyetu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khdknunc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqxtnay.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2idhkiiom.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaoryhu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nceovnke.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2inqldidy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2faqsrpda.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvccnfzb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fepkzguh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkvltfn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yykklchq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2poqoxcdq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjacmlc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnbqubc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cadzjecs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkksuqe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdowzce.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ndunlbov.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2djinkyhh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhnvvza.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyqtrmw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzrlvge.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjngdfa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hgncyhvm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2idiusnju.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pvatgolm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceigxngd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lecgvyth.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgxdmjj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoryewx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcvohkq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjrtemy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrljaec.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2byhsedwg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fspoeqfs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbubotbj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xltldgox.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbksrcsx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnwikrt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uscikeci.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oalquoff.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjhujpw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiqqidi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2arwdhhcn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxukhdaj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2puojejpt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfwouqq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwqsmbe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwyzrpl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gathbbwt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfvzpnd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snejryuj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qucinbqc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udwmneuj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xpenfxiw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtugabf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2omzwuncm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfffujp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njttqrhv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vuramtch.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2taelxtqk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwpnbup.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2elmnghog.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpbjmht.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnfeltw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vucswiwp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncovcbun.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tducyktv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjgzsph.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2maozzjhz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnksnjk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeiafpx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmevoaw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsjkapz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2suooyasi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxrsvri.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xvirsjks.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtmccnc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2veryxkdh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpsxjgw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbtdpif.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbilnjgz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aifqgxsa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kydrioop.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhcfgae.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfitdbeq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvpjaqa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2shxqcffb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqxwlby.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhxwwqx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2coujrfui.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qopcqvew.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cfipinoq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpqshce.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvzfkee.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgvqnyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2albzsdaz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jractqav.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmzxldw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuoknma.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmlndma.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oayqgckp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdepidgu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abrtkpvq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkktbgeq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fcclotqk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamwzhat.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcksssm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcyinti.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bnknjhrz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrcijtc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfygqsmx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2amykbaxn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzwygzu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqjjvmb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxjjnkw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2progoqca.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecywqxov.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzapficx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvsqku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itmbotfd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2watpzcve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpivblve.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vomutcgx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2daxrzodl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrxbbrm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iokgifyc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qksngcxy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqdwhhp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwtvvqr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwnekqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gawrdsni.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cortdqlb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2klhulthf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yssizvnh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygxssod.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwlaluz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtbjoky.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvdrsbu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dyldlrzv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aakehsue.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2olywouhs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpupruk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjxsuik.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2luhfccig.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgbkabn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdvrvpw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnrpdun.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xabruxlf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jszglcqr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxnpaxa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyahjgig.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xutgtkiv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iddgmzwe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrbicrv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhqscgr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spbtctyl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hakytcxe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lztcjxwc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aopuyfmc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2khoslzgb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2opaxontf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tustjetk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdzeblk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzfgxnb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxjmofl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjvutgc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vddehalm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2liuhokqi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abnbgvud.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcshwav.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfiryzb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeaocag.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yazjffdl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zaligcjm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avkhiqhc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiczudy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpifneat.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thcvuqnq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2imvkewky.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtesqhi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdndpfe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2witcegms.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuaxziz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgynrpka.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pybnzkaq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfvedsw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2isldvpnl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcsmhhs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vetkytha.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kizmdpsp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcjdvce.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2othdykho.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2litnndfk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrfhvyw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiepyqb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vifixshk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyricxbr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiffymz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhzwaqo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugukoesk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuxbohp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kezmbaal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2meyqrepz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrkifuo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwambefh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2niuzgywd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyjzfow.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mawleddw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lxepfotl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyfcsbv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvpihpi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvgejbr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqaoaed.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmkbqtl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2engqxzme.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kcufjfay.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2djzbrfsn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmmyctn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dafjmsrz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvfigvp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ompxqkee.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgmcsyt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2llcbtzmz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqzqgcm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyqpabz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oljjtlgj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbckhlj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2joezultp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiovkzj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhuejqa.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avivvijp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tauhblns.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbgbflu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfheehq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2heojbmia.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2koqbdihp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgzfshw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tatdgfun.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfwortt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2toyrdall.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvvxipn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxpzrgx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkjkvau.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcznybw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ecclfytk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnfcyky.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhwzaof.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmfnhxl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cnebtfro.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lolaujnn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdetgzo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2biabfzlh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeojfqk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wticcuwp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvasljj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2valoxkdb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xssungbj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhqvhxj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gogtbpyt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdugnsj.html


<!-- 参考信息 -->