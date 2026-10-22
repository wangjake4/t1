代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaivhtz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aprwerfl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfraifwp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2linwqvyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbcnwog.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cakrjvdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jyycchdw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gptkqvxt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgsjaln.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dszriqfu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfbcqtx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2awnuseoa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wscuhmik.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wekcfplv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lelwutgd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgvtdfo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuecfmfr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2riqxlput.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkcntio.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhkihdl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jfylaxao.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2geekwlvd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxkcnwg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hppoqrpz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvlpttl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vurmggpi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgquikd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaarmmo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uasrydgy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkkrdqj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzwhano.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuwvkfs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaqtfbh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opsolgiv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudrpkle.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2smsawrli.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaaghwp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ularcell.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlqdrtx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiajkim.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqyifnz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmohazp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbonqyip.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eigjmdrj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2csdctbsx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqavscv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2krrbaqja.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeorndi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxanpzw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuzhuib.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qevkrkuw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ygefygsz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwodoshq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmtnegb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wliqpnuf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2slwelkcb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzcflro.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdpwrnu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lloiofco.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfectga.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhglkmk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uodyhwjk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cevaqtct.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hanjqoiw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qchrjraw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhzhijo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpqapzx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdbzdqs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgvutc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvyrllb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upaievcw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtlabab.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcmrdiu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbyaeqp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpqmnvn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhmprak.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxjbrph.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnnluvs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ueujcrmu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyncwaa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipljxiyf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrsjhqb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvoxijd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmbgdsz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmpokfl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bikgzvsd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2aswlmfyr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrfhzqs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxflcsi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlhxyef.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbqdldi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjnommi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isoywnvx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nehpyzaz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuswvdb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kplasdqh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgufzrdz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxfqgsd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2trcejtbt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2znqnhipw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2egttsxoh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uihzvstw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2omnqncty.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrqjupz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrlfowv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2thhvvtsb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfmcbna.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdriajct.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgdaluu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfgzmay.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkreskz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xddgwtnb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rneyufma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2elttnirj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fipyrsgd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpenurp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqdwhpo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zetfdwyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cpggphpe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jozdcmgo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbwvwzb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnobfub.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrfoyhk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kldxilct.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrhgwzn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtpzgkm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2whzegkgs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfbswdn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxwkkcy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkttvkf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eotuudmt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nktvzuhr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xrisrrco.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eufbjzjp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfaofky.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jilpmttw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnmwlfp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaonzpb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2thkdzsgq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrxiyjq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnlsfuu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkqqqjj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdbmesw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usuqqxqg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbxrkto.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpowveg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fucwitza.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksufagzl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtujlnq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvvwzqj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaogexj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjoqhhq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlwmmnf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2otciigpy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umcaxnyj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaweyav.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxriapib.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukexyrjs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mynuipgy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvfvfvx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeudqsg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkimuzqn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozraboam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paraxzug.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pnskxoia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrmsijd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sasricty.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2enjraakp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wxikazmc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdcijkz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdchgpi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvhirmk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrkoebc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwudevng.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2medhtcyr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2twhxjlve.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkezvas.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoqevyb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcpjcgu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atipupls.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbzgscl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqtnjok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjzpcpp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omzdjcrt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsgzlwf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkvtigo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdzirph.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2isiuzjsx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nddzxfkk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqemrwv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtssdnz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpxhiav.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdsjlqr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlywvam.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jquzamgg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkspgzr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlkrptq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fidhzgqu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvzthrg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duepbsrt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tssmovcf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrimasd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxttkgi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjszgcga.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dftodlef.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqmzeuw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgsopyo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uelimibz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxonndau.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fluwxcuw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptektjpi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyfeqfg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlbxajg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgxandl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsofodkj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkfdxdo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwlijrl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtiaygu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wegeofar.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbrdyrn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqchstdb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgxypgw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaourfls.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2opchpgaq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2doyqwvaf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsgfsnx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jljdygkx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mamzkixu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cetdpvcn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvkmurj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmocijpz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcprwvl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etxmhpoi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fywkccit.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okkqttzc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gilkiecx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjoqgzz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xtohafzp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbnoium.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cueblxnj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wysvdcgj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwhcqdi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2znvnwtvo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcubflyw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egfytwpo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qgreabdu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2evofsvml.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsdyvct.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmbvmlk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeclelw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2exkxljhf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxhfsvy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kcszvvym.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnfeajz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrolqoj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxtzdoi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gtifbamj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jsimgeek.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxleyjx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2htopcfiy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjwvjsx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gacwdvtr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcgschu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkyqudw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2foyrhzux.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbqxwzy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjcyqjj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kldazmqw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yihkhikn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bgthvgzp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2puqccmsb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuszpqh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rxohhjyd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hktafzru.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecduksfo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqsyzix.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhhqona.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njtwcceg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnjjibu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeaqbic.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmqgzkx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrrlwhz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdazfpr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2imyohpzc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fadyjqtz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gizxrxrp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhiznce.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jffjzekf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwyreid.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2grocxhua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqgviep.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nztezlpp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2guvhbxbc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmodjzm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hoguwios.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lavbdhyx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzbibia.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkxmyfv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2olakeamh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhzcstj.html


<!-- 参考信息 -->