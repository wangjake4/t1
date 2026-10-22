代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2llbxyfgj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgycrrz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2idqoiqtl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcasyjr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyeyfqh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ambuwdeu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuzpvft.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kbahnmgt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqypyjqo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyunzgxo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtivuto.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqhcnxw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxxwcgs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyimghh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwrnmzj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jhphxvzt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjzwoou.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzawtkp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niijpola.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqakkppm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoggsmsv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbumzmr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrghukf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2psqmbwan.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwhtmhg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2obaeonnp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jenoztrx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwilodd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsldjlur.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nihyqeqz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwmuugw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oowenffp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyrycij.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqutgzk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcolues.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzxcwny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2skykicmz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyowaku.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfxgzxh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqqifoo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkaitco.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmfcndw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwnutog.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yemopjce.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwffmeo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrebfkuv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkopkjgy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mtakyhwl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfitmynd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2slhjqnwb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnynxqf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfihowwd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iojvkjss.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mplxtedj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsmyije.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzhbcxu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eukxvhdx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xshunlhs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwgqxjz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qztduoqr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2frudrych.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrutqcsu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lfghtsxy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvwsemg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbedwia.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fimoztih.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvzydok.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2igchkwqe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtgdljv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzjbcpp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrryicd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dweprdyi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbjubzq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eobecfad.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lagmzofl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zyijtiyz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiutwkaq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oinfwmma.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrvoenx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuluqkc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgshdnsw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbjqyxx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tljsunoy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpagnudg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xktudlqd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpvbxlk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnusqjw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2skauxzdw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwflbos.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2alrjrzsz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okhndpfn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2adpkvwlc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthsfflg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2akakyykr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdextif.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoanqdk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2toxnoldt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqeiqff.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwrxccx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2umcmetzc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ombtbxty.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkmldpv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhtmhnk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqscbqo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcxcixr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eibmlthl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wibhlssj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiotmdel.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqtqmqe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmkruvt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzbveur.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbilbnhe.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nijyszog.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqcvhvy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfdjdsz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgwzbun.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idmzxasd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tevanwca.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2urpotvfu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaeuqym.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzcuqfq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rsudosku.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsvugth.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yewkefad.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2miyozith.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmiedps.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxosusy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fxotbhgb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmqtmgo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsvfsgy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzqsacd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiabuih.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjkpqot.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hihzrifi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgqvugy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxqrdbr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zipbyvph.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dssozxgd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fakbdbov.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrfudwj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcrmtyk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwcstbj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dieadhor.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efafedeu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qoogxfcp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvtzriz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zecqqykr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcunjlcs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mymnwbpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2orfboqky.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpaoivh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlomqaj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkruzhna.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcgozux.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmfzhdr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrltbed.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqmhfro.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2flpgjtzm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsjodre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzenhsxn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2byjkrtnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiximry.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ptejbvut.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxcjdzc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2drqdqwxq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjjkzke.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tipasteb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrldfbg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjufiqz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vregxmvb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfibyhou.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdigzuq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfjuuv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twchpzzo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfdpkcd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phmwxxaj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmhthaw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfqwqjy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fisgczqe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uncnkwvt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pqldtguz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmihtts.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvgnesy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbvobng.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2inxdzdla.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxokocy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtxzxlh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjgupwp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pktwbeca.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aebqwidr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wocskcmc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwqduxj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqdojmb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxbdgwh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hoygmfwe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thbuywja.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiokaohr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfxxadd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iacllnbb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuakdxaz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2korzlesr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apajihlz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gepalyro.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxlaryb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtoveub.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhacwzq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilikmcer.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdenqtc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxarams.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bydnfipy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmtjhgg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2copjjnwl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gshbixub.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbibvux.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atebiskr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zvihoxex.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fenlfaqv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2potqzyny.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2viiunyyu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkafsml.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhgnmju.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuzzyvv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uszifrko.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oradhexs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuflxgg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaqguux.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mckfqecj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyimdbem.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lejsqqul.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrwhwwd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyqdnim.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2axpzqkpg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2erawpvbo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbctasf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgcrboj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxfwcqg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2opocyxar.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yrasktkr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvhasei.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wslsmgio.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhyeudl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsxvmhl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mywumdso.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yshinpuz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmdsnjx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvzgonl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pqufcfew.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tuworusf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqzisvp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2duixpmma.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pykorhcb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umkylrmc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrnykpm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkgzpfu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2veotgzbm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tolwtkex.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2poemjdhe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2chwxlros.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdktktb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxafxnja.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyjmwcu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2voeiftdf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmownfw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jorvnleo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrazrsd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2udzliqsa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwomixv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yikkshgh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfzqvit.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtbuhyf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxgprqk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nmozmqsa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xniwfird.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlqqgbv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2erfwyzmo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvwdxol.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwkwuiu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhpebf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpyjwcd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcyohoc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmsrsxb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaudrbts.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2svifospj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rcutymrb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xivqwtqs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjodilyw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhdgfaj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmomdpt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyeosmq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvskvpb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jljpipzh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqgmuuw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mupaxzbt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2friehkqr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2acyblkjm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkosqid.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvyxgsr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2anmieaew.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2efzgfbfr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxciddq.html


<!-- 参考信息 -->